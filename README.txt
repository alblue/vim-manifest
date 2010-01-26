Vim syntax file for JAR Manifest files
Maintainer: Alex Blewitt <alex.blewitt@gmail.com>
License:    This file is placed in the public domain
URL:        http://github.com/alblue/vim-manifest.git

This is a VIM syntax for MANIFEST.MF files, along with known OSGi bundle
headers. 

To obtain and install, do the following:
$ git pull git://github.com/alblue/vim-manifest.git # Or 'http://'
$ mkdir -p ~/.vim/{ftdetect,syntax}
$ cp vim-manifest/ftdetect/* ~/.vim/ftdetect/
$ cp vim-manifest/syntax/* ~/.vim/syntax/

Run (a new) VIM on a MANIFEST.MF file. If the highlighting and syntax
is not automatically displayed, then you can turn it on with:

:filetype on
:syntax on

These two commands can be in your ~/.vimrc file to make it easier to 
automatically display these types of files.

If you wish to work in progress on your own fork of the repo, change the
'cp' command above to 'ln -s' so that they're in the right location for VIM
whilst being (elsewhere) on your system for Git. It is not recommended to 
put the ~/.vim directory under Git control fully, since there can be many 
different projects editing VIM files but only one .vim directory.

Alex Blewitt
