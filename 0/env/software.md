---
description: 好的软件能够带给你更舒适的开发环境，这里推荐几款常用的开发软件。
---

# 软件安装

## 1️⃣ Visual Studio Code

### 简介

Visual Studio Code_<mark style="color:purple;">(以下简称VSCode)</mark>_是一款极为轻量的代码编辑器，低端机上也能流畅使用，你再也不用担心你的视力会因为写魔改而降低了。

很多初学者认为ZS只是拿来玩玩的语言，对其持轻视态度，之后就拿记事本开始撸代码，你猜最后怎么着，自己写的东西都不知道是怎么运行的。

VSCode提供了代码高亮、括号补全、自动缩进等功能，如果装载扩展插件，还能够实现自动补全和彩色括号等更多内容，故此为首选的魔改编辑器。

点击 [这里](https://code.visualstudio.com/) 访问官网下载，该软件开源免费，无需付费。

> 在魔改圈，VSCode是魔改作者们的标配，必须人人都有。

### 安装与配置

下载安装包后，双击运行安装。安装完成后，打开编辑器，找到左侧的 ![\_\_U8\_MH2@NK3L\`W7DEWXKDA.png](https://s2.loli.net/2022/10/01/Mf6YZDFKSLk4Cig.png) 图标。

此选项为扩展选项，开发中我推荐装载如下扩展：

*   ZenScript <mark style="color:red;">**(必选，作者为Yesterday17)**</mark>

    > 还记得之前的Probe模组吗？它就是跟这个扩展搭配使用的，两者同时装载之后，就可以使用补全功能了。
    >
    > 只装载扩展，则只有编辑器内语法检查作用；只装载模组，仅仅只是生成了一个 `.zsrc` 文件，不会起到任何作用。
* Chinese (Simplified) (简体中文) Language Pack for Visual Studio Code <mark style="color:red;">**(VSCode官方中文包)**</mark>
* Jetbrains New Dark Theme <mark style="color:red;">**(舒适的暗色调主题)**</mark>
* Rainbow Brackets <mark style="color:red;">**(括号成堆时的助读器)**</mark>

> 开发过程中，我推荐使用暗色调主题，上述的第三个扩展就是我个人比较喜欢的暗色调主题，且提供了关键字高亮。
>
> 暗色调比较舒适护眼，无论白天黑夜看起来都很舒服，这也会提高开发者们的工作效率。

装载完毕后，重启VSCode，扩展就加载完成了。

如果有需要，你还可以在VSCode的设置中更改字体样式，这里不再过多赘述。

给大家看一下我的VSCode开发环境，下图是一个事件示例：

![PCXF6@18\_1YE\_RS1FYA9L@B.png](https://s2.loli.net/2022/10/01/zXcEB2RUwSfVJWe.png)

可以看到，VSCode真的非常方便，你可以完全不顾虑地在其中享受敲代码的乐趣。

选中左上角的 `文件\打开文件夹` ，再选择 `.minecraft/scripts`，这样VSCode就会读取到你的魔改文件夹了，当然你可以直接打开 `.minecraft`，在开发整合包时可以更快速地切换至其他文件。

> 如果游戏开启了版本隔离，那么魔改文件应在 `.minecraft/versions/版本名/scripts` 处存放。
>
> 版本隔离就是将每个版本单独封装起来，一个 `.minecraft` 内可以包含多个版本，这些版本互不干扰。一些使用HMCL或PCL等启动器的用户可能会将每个客户端都安置一个启动器，但这样来回切换太麻烦了，而版本隔离可以使你在一个启动器内打开多个版本，即使游戏版本不相同。也就是说，你可以在一个启动器内放入多个自己的项目以此来集中管理。

当VSCode装载了ZenScript扩展后，会自动读取后缀名为.zs的文件，然后生效。关于后缀名会在第一章的基础开发部分讲解。

## 2️⃣ Typora

### 简介

