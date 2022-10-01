---
description: 好的软件能够带给你更舒适的开发环境，这里推荐几款常用的开发软件。
---

# 软件安装

## 1️⃣ Visual Studio Code

### 简介

Visual Studio Code _(以下简称VSCode)_ 是一款极为轻量的代码编辑器软件，它的优化堪称极致\~\~(不像JetBrains系列的那些开发工具，只要你电脑达不到需求，你就没法用人家的工具)\~\~，渣机上也能流畅使用，你再也不用天天受Notepad的视力考验了。

很多初学者认为ZS只是拿来玩玩的语言，然后就拿那个黑白相间的记事本开撸代码，你猜最后怎么着，自己写的东西都不知道在哪里运行。

VSCode提供了代码高亮、括号补全、自动缩进等功能，如果装载扩展，还能实现自动补全和彩色括号等更多内容。除此之外，ZS的相关扩展插件基本上也只对VSCode兼容\~\~(因为实在是太好用了)\~\~，故此为首选的编辑器软件。

点击 [这里](https://code.visualstudio.com/) 访问官网下载，该软件免费开源，无需付费。

> 在魔改圈，VSCode是魔改作者们的标配，人人必须都有。

### 安装与配置

下载安装包后，双击运行安。安装完成后，打开编辑器，找到左侧的 ![\_\_U8\_MH2@NK3L\`W7DEWXKDA.png](https://s2.loli.net/2022/10/01/Mf6YZDFKSLk4Cig.png) 图标。

此选项为扩展选项，开发中我推荐装载如下扩展：

* ZenScript **(必选，作者为Yesterday17)**
* Chinese (Simplified) (简体中文) Language Pack for Visual Studio Code
* Jetbrains New Dark Theme
* Rainbow Brackets

装载完毕后，重启VSCode，扩展就装载完成了。

开发过程中，我推荐使用暗色调主题，上述的第三个扩展就是我个人比较喜欢的暗色调主题，且提供了JetbBrains主题的关键字高亮，如果不喜欢，也可以用VSCode的默认主题，或装载其他的主题色。

> 暗色调比较舒适护眼，无论白天黑夜看起来都很舒服，众多程序员都会将自己的电脑调整为暗色调主题，以此来提高工作效率。

如果有需要，你还可以在VSCode的设置中可以更改字体样式，这里不再过多赘述。

给大家看一下我的VSCode开发环境，下图是一个ZS的事件机制：

![PCXF6@18\_1YE\_RS1FYA9L@B.png](https://s2.loli.net/2022/10/01/zXcEB2RUwSfVJWe.png)

可以看到，VSCode真的非常方便，你可以完全不顾虑地在其中享受敲代码的乐趣。

选中左上角的 `文件\打开文件夹` ，再选择 `.minecraft/scripts`，这样VSCode就会读取到你的魔改文件夹了，当然你可以直接打开 `.minecraft`，在开发整合包时可以更快速地切换至其他文件。

> 补充：如果开启了版本隔离，那么魔改文件应在 `.minecraft/versions/版本名/scripts` 处存放。

当VSCode装载了ZenScript扩展后，会自动读取后缀名为.zs的文件，然后在其生效。关于后缀名会在第一章的基础开发部分讲解。
