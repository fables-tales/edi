#edi


edi is a simple command line tool that attempts to boost productivity. I found that
when I was working on single file projects typing the entire filename was annoying. I've
also found it useful when working on subdirectories within a project: if that subdir
contains only a single file I care about right now I edi it. 

edi is configured with `edi set [file]` which will have edi open `file` when the main
`edi` command is typed.

**Edi configuration is written/read into/from the current directory**

edi is git aware. Each person gets their own edi line, and this means that you can
specify your favourite files to be opened with edi

##Installation notes:

Just put edi in your path. I did this with ``ln -s `pwd`/edi ~/bin/``

##Todos:
 * Make edi have queue and stack based editing
 * Make edi automatically queue conflicting files in a git merge situation
