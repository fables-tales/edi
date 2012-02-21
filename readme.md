#edi

edi is a simple command line tool that attempts to boost productivity. Instead of having
to point your editor as files as you're slinging around a project, use edi.

edi is configured with `edi set [file]` which will have edi open `file` when the main
`edi` command is typed.

edi is git aware. Each person gets their own edi line, and this means that you can
specify your favourite files to be opened with edi

##Installation notes:

Just put edi in your path. I did this with ``ln -s `pwd`/edi ~/bin/``

##Todos:
 * Make edi have queue and stack based editing
 * Make edi automatically queue conflicting files in a git merge situation
