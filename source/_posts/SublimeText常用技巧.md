title: Sublime Text 3 使用技巧

date: 2015-12-29 11:02

categories: skills

tags:
  - Sublime Text 3

---

一直在用Sublime Text 3 ，真的喜欢，但是在win10下面状况不断，还有家里的网是让人愤怒的长城宽带，根本无法正常联网安装`control package`。

说多了，都是累，手动就算是安装了，但是依然TM连插件都下载不了，已经不能用脏话来形容了，此刻我要心如止水，淡定淡定，在中国，任何网络情况都是正常的,淡定。

以下仅仅适合正常联网的同学，不正常的绕过吧。contorl package都安装不了，说那些有撒用，然而并没有什么卵用。

<!--more-->

### 问题集合

1.电脑分辨率太高，尺寸又太小（笔记本），导致文件目录树的文件名变成了一个个口。

修改`preferences->setting user`

```json
{
	"dpi_scale": 1.0,
	"font_size": 16
}
```

### 快捷键

快捷键列表（Shortcuts Cheatsheet）
我把本文出现的Sublime Text按其类型整理在这里，以便查阅。

通用（General）
↑↓←→：上下左右移动光标，注意不是不是KJHL！
Alt：调出菜单
Ctrl + Shift + P：调出命令板（Command Palette）
Ctrl + `：调出控制台

编辑（Editing）
Ctrl + Enter：在当前行下面新增一行然后跳至该行
Ctrl + Shift + Enter：在当前行上面增加一行并跳至该行
Ctrl + ←/→：进行逐词移动
Ctrl + Shift + ←/→进行逐词选择
Ctrl + ↑/↓移动当前显示区域
Ctrl + Shift + ↑/↓移动当前行

选择（Selecting）
Ctrl + D：选择当前光标所在的词并高亮该词所有出现的位置，再次Ctrl + D选择该词出现的下一个位置，在多重选词的过程中，使用Ctrl + K进行跳过，使用Ctrl + U进行回退，使用Esc退出多重编辑
Ctrl + Shift + L：将当前选中区域打散
Ctrl + J：把当前选中区域合并为一行
Ctrl + M：在起始括号和结尾括号间切换
Ctrl + Shift + M：快速选择括号间的内容
Ctrl + Shift + J：快速选择同缩进的内容
Ctrl + Shift + Space：快速选择当前作用域（Scope）的内容

查找&替换（Finding&Replacing）
F3：跳至当前关键字下一个位置
Shift + F3：跳到当前关键字上一个位置
Alt + F3：选中当前关键字出现的所有位置
Ctrl + F/H：进行标准查找/替换，之后：

Alt + C：切换大小写敏感（Case-sensitive）模式
Alt + W：切换整字匹配（Whole matching）模式
Alt + R：切换正则匹配（Regex matching）模式
Ctrl + Shift + H：替换当前关键字
Ctrl + Alt + Enter：替换所有关键字匹配
Ctrl + Shift + F：多文件搜索&替换

跳转（Jumping）
Ctrl + P：跳转到指定文件，输入文件名后可以：

@ 符号跳转：输入@symbol跳转到symbol符号所在的位置
`#` 关键字跳转：输入#keyword跳转到keyword所在的位置
: 行号跳转：输入:12跳转到文件的第12行。
Ctrl + R：跳转到指定符号
Ctrl + G：跳转到指定行号

窗口（Window）
Ctrl + Shift + N：创建一个新窗口
Ctrl + N：在当前窗口创建一个新标签
Ctrl + W：关闭当前标签，当窗口内没有标签时会关闭该窗口
Ctrl + Shift + T：恢复刚刚关闭的标签

屏幕（Screen）
F11：切换普通全屏
Shift + F11：切换无干扰全屏
Alt + Shift + 2：进行左右分屏
Alt + Shift + 8：进行上下分屏
Alt + Shift + 5：进行上下左右分屏
分屏之后，使用Ctrl + 数字键跳转到指定屏，使用Ctrl + Shift + 数字键将当前屏移动到指定屏

延伸阅读（Further Reading）

书籍（Books）
Mastering Sublime Text：我读过的唯一一本关于Sublime Text的书籍，书中介绍的插件很实用，但对编辑技巧介绍不全。
Instant Sublime Text Starter：另外一本关于Sublime Text的书，我没有读过。

链接（Links）
官方文档：http://www.sublimetext.com/docs/3/
官方论坛：http://www.sublimetext.com/forum/
Stack Overflow的Sublime Text频道：
http://stackoverflow.com/questions/tagged/sublimetext
http://stackoverflow.com/questions/tagged/sublimetext2
http://stackoverflow.com/questions/tagged/sublimetext3
非官方文档：http://sublime-text-unofficial-documentation.readthedocs.org/ 甚至比官方文档还要全面！
Package Control：https://sublime.wbond.net/ 大量的Sublime Text插件和主题。

视频（Videos）
Getting Started with SublimeText：https://www.youtube.com/watch?v=04gKiTiRlq8
Sublime Text Pefect Workflow：https://www.youtube.com/watch?v=bpEp0ePIOEM&list=PLuwqxbvf3olpLsnFvo06gbrkcEB5o7K0g




