# hello_vim
[TOC]
Learning vim, vim-plugin.
<img src='https://i.loli.net/2020/11/19/O4Emq8LFjoIaGHc.jpg' width='80%' height='50%'></img>
![](https://i.loli.net/2020/11/19/a5pkoCtMX9r14wR.gif)
---
## 原生vim
原生vim本身就已经比较强大了，拥有四种模式:
1. Normal mode -  navigate the structure of the file
```
Normal模式下浏览文件的结构，也可以使用命令。其他模式下<Esc>进入Normal模式，编辑文本时大量的时间都在Normal模式，该模式下使用命令功能也是很强大的！
```
2. Insert mode - editing the file
```
Insert模式比较简单，主要是编辑文件。Normal模式下可以通过a(光标后面插入),i（光标前面插入）,I（行首插入）,A（行尾插入）,o（下一行新建并插入）,O（上一行新建并插入）,s（删除当前字符并插入）
```
3. Visual mode - highlighting portions of the file to manipulate at once
```
Visual模式下高亮选中的部分文件并可执行一次操作。
```
4. Ex mode - command mode
```
Ex模式可以执行命令，Nornal模式下:可以进入命令模式。
```
<++>
### Nornal mode
|key|describe|move cursor|
|:-:|:-:|:-:|
|<kbd>h</kbd>|left|:arrow_left:|
|<kbd>j</kbd>|down|:arrow_down:|
|<kbd>k</kbd>|up|:arrow_up:|
|<kbd>l</kbd>|right|:arrow_right:|
