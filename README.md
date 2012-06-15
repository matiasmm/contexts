CONTEXTS
========

It's a simple python script to remmember opened files used when working in some named context. As Mylyn for eclipse

INSTALL
=======

    git clone git://github.com/matubaum/contexts.git
    cp contexts/contexts ~/bin/contexts
    chmod u+x ~/bin/contexts


USAGE
=====

Create a new context
--------------------
We are creating a context called "bug123".
Go to your project dir.

    cd /my/project
    contexts bug123
    # Here it going to ask you to add your files you are using separated by an space.

Add another file to your context
--------------------------------

    contexts add bug123 another_file.txt

Open your context 
-----------------

    contexts bug123
    # It's going to open your files with vim, but you can edit the file to open it with another editor or ide.


List all your contexts
----------------------

    contexts ls




