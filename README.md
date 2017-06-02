#### 游戏介绍

本贪吃蛇源码包含两种版本

1. 正常的版本没有其他难懂的函数，但最大的缺点就是由于终端需要不断刷新带来的终端闪烁问题
2. “cursor goto”版本采用了Gotoxy函数移动光标，达到局部修改显示的目的，使游戏界面不会闪烁

两种版本的贪吃蛇均实现了速度选择、计分等基本功能。还支持游戏暂停，重新开始，退出游戏等功能

本源码仅支持windows操做系统，不支持linux。预先编译出了x86、x64两种版本，分别支持32位、64位windows系统，一般情况下，x86版在两种系统中均可运行。`但强烈建议使用自行编译得到的可执行文件。`

运行时可能因为字符显示问题导致程序表现异常，请自行修改源码中的相关字符变量重新编译

本源码主要给同学们提供贪吃蛇的一种实现思路
