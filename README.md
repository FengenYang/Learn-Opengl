# Learn-Opengl
### 前言 

该项目旨在记录本人学习opengl的过程，学习流程按照以下链接中的教程进行，在跟随教程进行对opengl各功能的学习和应用，同时会将每章的练习结果和学习心得放到对应的文件夹下，希望这些笔记对想学习opengl的朋友有所帮助，同时也欢迎各位提出建议以及对错误进行指正:

https://learnopengl-cn.github.io/intro/



### 环境配置

在跟随教程开始学习之前，需要配置一些所需的软件环境以满足开发需要，环境配置过程比较重要，同时可能因为某些原因出现各种各样的小问题，所以在此记录一下，以下为本人所使用的软件版本以及配置过程，可能不同版本的情况下配置过程会存在差异，该流程主要用作参考。



#### IDE

在IDE的选择上，本人使用的是Visual Studio 2019，其对C++的支持还是比较完善的。



#### GLFW配置

我们在使用OpenGL的时候，需要调用其提供的各种函数，比如创建Context，创建显示所用到的窗口，那么对于不同的操作系统，这些函数的实现方式可能存在差异，所以说对于这个问题，OpenGL就故意把这些函数抽象出去，它自己只专注于图形渲染方面的功能，对于操作系统相关的代码，像输入输出这种基础功能，我们就得自己写了，那这也太花时间了，我们还是用别人写好的现成函数比较节约时间，GLFW就是一个提供了这些功能的C语言库，那我们就先来把这个库准备好。

首先去[官网](https://www.glfw.org/download.html)下载GLFW

