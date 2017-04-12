# opener
Find and open a file in a bunch of directories.

## Installation
```shell
#Copy script file into a directory you like
$ cp ./opener ~/bin/opn

#Add an environment variable if you didn't
#ex. Add the following line to your .bash_profile
$ PATH=$PATH:$HOME/bin
```

## Usage
```
opn [command ...] [keyword]
```
You can use the following keys to move cursor when a list of files is printed. Arrow keys are not supported.
* Move up: k, h
* Move down: j, l
* Select: Return
* Cancel: q, Escape

## Examples
```shell
#Open a file using vim
$ opn vim java
./src/some/dir/MakePHPGreatAgain.java
./src/some/dir/SomeClass.java
./src/some/dir/UsefulClass.java
./src/some/dir/UselessClass.java
./res/i_am_not_java.xml
#Now you can select one of 'em to open.

#Remove a file
$ opn rm Cthulhu
./IaIaCthulhuFhtagn.txt
./lib/Necronomicon/Cthulhu.myth

#Staging a file
$ opn git add Mettaton
./ut/chara/Mettaton.png
./ut/chara/Mettaton_ex.jpg
./ut/chara/Mettaton_neo.gif
```

## TODO
* Nope!
