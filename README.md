# vimfiles

my vim configuration

# Installation

## Windows
clone this repo into $HOME directory (into `C:\Users\USERNAME\vimfiles\`)  
then from admin basic cmd prompt (not powershell):  
`mklink /D .vim vimfiles`  
to create a symbolic link. this is necessary because git for windows mintty shell ships its own version of vim which looks in the unix locations

## Linux
clone this repo into $HOME directory  
then `mv vimfiles .vim` to rename folder because of different runtimepath on unix (`:help rtp`)
