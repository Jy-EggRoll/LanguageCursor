# 语言鼠标——LanguageCursor

根据语言模式切换鼠标样式！

Switch mouse cursor style based on language mode!

## 1. 介绍——Introduction


Windows自带的输入法，在中英文切换上常常不随心意。本人用过好多输入状态提示软件，但是或多或少都有软件兼容性问题，有一些软件的功能太杂，性能也不佳。

The built-in input method of Windows often does not switch between Chinese and English as I wish. I have tried many input status notification software, but they all have some compatibility issues, and some of them are too cluttered with features and have poor performance.

我只是需要一款简单的能提示我中英文状态的软件，直到在GitHub上发现了[DynCursor](https://github.com/alvinfunborn/DynCursor)这个项目。这个软件基本上就是替换Windows自带的不常用鼠标样式，软件占用极小，性能毫无问题，提示功能也非常合我心意。

I just needed a simple software that could notify me of the Chinese and English status, until I discovered the [DynCursor](https://github.com/alvinfunborn/DynCursor) project on GitHub. This software essentially replaces the rarely used mouse styles that come with Windows, has minimal software footprint, no performance issues, and the notification feature is very much to my liking.

**推荐您先仔细阅读原项目的页面，了解软件后再看本项目。**

**It is recommended that you carefully read the original project's page to understand the software before viewing this project.**

## 2. 修改内容——Changes

- 大幅优化鼠标样式（与小城子合作，详见最下方说明）
- 删除了一项指针样式替换，不再替换链接指针

- Optimized mouse styles (with Xiao Chengzi co-operation, see below for details)
- Removed a pointer style replacement, no longer replacing link pointer

## 3. 功能——Features

- 中文状态下，鼠标正常指针为飞行的纸飞机，文本指针为荧光红。
- 英文状态下，鼠标正常指针为纸飞机，文本指针为荧光绿。

- When in Chinese mode, the normal pointer is a flying paper plane, and the text pointer is a fluorescent red.
- When in English mode, the normal pointer is a paper plane, and the text pointer is a fluorescent green.

## 4. 使用方法——Usage

下载LanguageCursor.zip，解压到任意目录，先阅读内部的文件说明，安装对应的鼠标指针，再双击运行DynCursor.exe。

Download LanguageCursor.zip, extract it to any directory, read the internal file description first, install the corresponding mouse pointer, and then double-click to run DynCursor.exe.

## 5. 开机自启动的配置方法——Auto-startup Configuration

1. 给DynCursor.exe创建一个快捷方式，剪切这个快捷方式。
2. 点击Win+R，输入shell:startup，打开“启动”文件夹。
3. 将刚才剪切的快捷方式粘贴到“启动”文件夹。

1. Create a shortcut for DynCursor.exe.
2. Click Win+R, type "shell:startup", and open the "Startup" folder.
3. Paste the shortcut you just cut to the "Startup" folder.

这样，开机后，DynCursor.exe就会自动运行。

That's it, DynCursor.exe will automatically run when you start your computer.

---

如果您觉得好用，请帮忙给此项目和原作者的项目[DynCursor](https://github.com/alvinfunborn/DynCursor)点个Star，谢谢！

If you like this project, please star this project and the [DynCursor](https://github.com/alvinfunborn/DynCursor) project on GitHub, thank you!

---

## 指针修改介绍

纸飞机光标PaperPlane的原作者为小城子：

[小城子的网站](https://xcz.me/)

[小城子的哔哩哔哩主页](https://space.bilibili.com/284065805)

[小城子的致美化主页](https://zhutix.com/user/182854)

本人对文件进行二次创作并作为项目的一部分发布已获得小城子本人授权。

我的个人介绍：

[蛋卷儿的网站](https://jy-eggroll.github.io/my-page/)

[蛋卷儿的GitHub](https://github.com/Jy-EggRoll)

### 1. 鼠标指针的安装方法

进入对应文件夹，右键“AutoSetup.inf”，选择安装即可。

本人已对不同主题的文件夹名称和注册表项名称做了处理，安装后您可以轻松分辨。

**注意：安装文件仅适合传统Windows系统（32位、64位），WoA（Windows on ARM）不可以使用。**

### 2. 纸飞机光标（PaperPlane的两个文件夹）

#### 2.1 Light

亮色主题，全部为小城子的原文件，未经改动，文件夹中有预览图。

#### 2.2 Dark

暗色主题，这是我在小城子原文件基础上制作的暗色版本，鼠标形状全部为小城子的原版，仅做了颜色上的处理。

### 3. 语言光标（Language的两个文件夹）

**注意：虽然语言光标鼠标主题也可以独立安装使用，但是更推荐搭配此GitHub项目使用（尚在开发中）。**

语言光标功能：根据系统的语言智能选择光标的样式。

对“帮助”“文本”“候选”三个光标做了修改：

- “帮助”：从原来的问号改为了纸飞机飞行的效果

- “文本”：改为了荧光绿“工”字形光标

- “候选”：改为了荧光红“工”字形光标

效果为：输入法语言为中文时，纸飞机光标具有飞行效果（调用了“帮助”光标），文本输入为荧光红光标（调用了“候选”光标）。输入法语言为英文时，纸飞机光标无特殊效果，文本输入为荧光绿光标。

此项目主要受[DynCursor](https://github.com/alvinfunborn/DynCursor)启发，目前主要使用的就是DynCursor的文件。DynCrusor已经很长时间没有更新了，也存在一些bug，但是毫无疑问这是一个非常优秀的项目。本人决定在DynCursor的基础上进行二次开发，让这个项目变得更完美。

#### 3.1 Light

亮色主题。

#### 3.2 Dark

暗色主题，但荧光红和荧光绿两个光标和亮色主题一致，未作处理。

## Introduction of the Pointer Modification

The original author of the PaperPlane cursor is Xiao Chengzi:

[Xiao Chengzi's Website](https://xcz.me/)

[Xiao Chengzi's Bilibili Homepage](https://space.bilibili.com/284065805)

[Xiao Chengzi's Zhutix Homepage](https://zhutix.com/user/182854)

I have obtained Xiao Chengzi's personal authorization to re-create the file and release it as part of the project.

My personal introduction:

[EggRoll's Website](https://jy-eggroll.github.io/my-page/)

[EggRoll's GitHub](https://github.com/Jy-EggRoll)

### 1. Mouse Pointer Installation Method

Enter the corresponding folder, right-click on "AutoSetup.inf", and select Install.

I have processed the folder names and registry item names for different themes, so you can easily distinguish them after installation.

**Note: The installation file is only suitable for traditional Windows systems (32-bit, 64-bit), and cannot be used for WoA (Windows on ARM).**

### 2. Paper Plane Cursors (Two folders of PaperPlane)

#### 2.1 Light

Light theme, all are the original files of Xiao Chengzi, unmodified, with preview images in the folder.

#### 2.2 Dark

Dark theme, this is the dark version I made based on Xiao Chengzi's original files, all mouse shapes are Xiao Chengzi's original, only the colors have been processed.

### 3. Language Cursors (Two folders of Language)

**Note: Although the Language cursor mouse theme can also be installed and used independently, it is more recommended to use it with this GitHub project (still under development).**

Language cursor function: Intelligently select the cursor style according to the system's language.

Modifications have been made to the "Help," "Text," and "Candidate" cursors:

- "Help": Changed from the original question mark to the effect of a paper plane flying

- "Text": Changed to a fluorescent green "T"-shaped cursor

- "Candidate": Changed to a fluorescent red "T"-shaped cursor

The effect is: When the input method language is Chinese, the paper plane cursor has a flying effect (calling the "Help" cursor), and the text input is a fluorescent red cursor (calling the "Candidate" cursor). When the input method language is English, the paper plane cursor has no special effect, and the text input is a fluorescent green cursor.

This project is mainly inspired by [DynCursor](https://github.com/alvinfunborn/DynCursor), and the files used are mainly from DynCursor. DynCursor has not been updated for a long time and has some bugs, but there is no doubt that it is a very excellent project. I decided to re-develop on the basis of DynCursor to make this project more perfect.

#### 3.1 Light

Light theme.

#### 3.2 Dark

Dark theme, but the fluorescent red and fluorescent green cursors are consistent with the light theme and have not been processed.