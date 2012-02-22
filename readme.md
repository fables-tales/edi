#edi

When you run edi for the first time type `edi set [file]`. Then when you run `edi` in
the same directory edi will open that file in whichever editor is defined with $EDITOR.
It's designed to make it easier to work with single file projects or projects with many
subdirectories with few files in them.

edi configuration only applies to your current working directory

edi is git aware. Each person gets their own edi line, and this means that you can
specify your favourite files to be opened with edi

##Installation notes:

Just put edi in your path. I did this with ``ln -s `pwd`/edi ~/bin/``

##Todos:
 * Make edi have queue and stack based editing
 * Make edi automatically queue conflicting files in a git merge situation
