---
description: ZenScript与CraftTweaker的诞生与联系
---

# ZenScript 与 CraftTweaker

## **简介**

ZenScript_<mark style="color:purple;">(以下简称ZS)</mark>_，最初由stanhebben编写，现由Jaredlll08和kindlich等人维护。

ZS是专门针对Minecraft进行修改的一门语言，与模组CraftTweaker_<mark style="color:purple;">(以下简称CrT)</mark>_挂钩，使整合包作者们达到更轻易修改游戏的目的，省去了作者们想实现一些简单的功能却又不得不写模组的麻烦。

ZS适用于Minecraft的修改操作，要使用ZS对游戏进行修改，游戏内需要装载CrT模组。这样便可以实现ZS与游戏的接口。另外注意，ZS脱离了Minecraft是无法单独在外运行的。

CrT模组目前最为广泛的使用版本为Minecraft 1.12.2，1.12.2曾是Minecraft的巅峰时期，故CrT的使用比例也是最高。在旧版本，MineTweaker_<mark style="color:purple;">(以下简称MT)</mark>_为最常用的魔改模组，同时它也是CrT的前身。

CrT的前身本是MT，但由于前作者stanhebben停止了对MineTweaker的维护，Jaredlll08等人便接手了此项目，CraftTweaker及衍生系列便就此诞生。

Minecraft 1.13以后，游戏经历了大重写，Forge及其各个模组也不得不跟着重写，CrT也干脆趁着这个机会重写了一波，故在1.12.2之后的版本，魔改也不再使用老一代写法。

> 在1.13及更高的版本，CraftTweaker改为使用ZenCode，不再是ZenScript。
>
> ZenScript与ZenCode均独立运行，并没有多大的联系。

ZS基于Java语言编写，是一门封装型语言，需要基于Java运行。

下个页面将会对配置ZS的开发环境进行讲解。

## 相关链接

ZenScript源代码仓库：[https://github.com/CraftTweaker/ZenScript](https://github.com/CraftTweaker/ZenScript)

CraftTweaker源代码仓库：[https://github.com/CraftTweaker/CraftTweaker](https://github.com/CraftTweaker/ZenScript)
