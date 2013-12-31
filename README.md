# Vim PlantUML Syntax/Plugin/FTDetect

This is a vim syntax file for [PlantUML](http://plantuml.sourceforge.net).

The `filetype` will be set to `plantuml` for *.pu, *.uml or *.plantuml files or if the
first line of a file contains `@startuml`.

## Install ##
1. 编辑.vimrc
增加如下

    Bundle 'https://github.com/dolfly/plantuml.git'

2. 执行安装
```sh
vim
<ESC> #切换到命令行模式
:BundleInstall 
```

## Example ##
````sh
vim test.uml
...type some code
<ESC> #切换到命令行模式
:make
````
Then you will see test.svg  
