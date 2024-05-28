# Ruby Game Example

* Repo: https://github.com/Mark24Code/ruby-windows-example
* Author: Mark24Code

-- Guide -------------------------------------------

# 0.下载 Ruby

下载网站 https://rubyinstaller.org/downloads/

直接下载链接 https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-3.3.1-1/rubyinstaller-devkit-3.3.1-1-x64.exe


# 1.安装 Ruby

安装  rubyinstaller-devkit-3.3.1-1-x64.exe



1）注意勾选 添加到 PATH

2） 组件勾选，可以不勾选 rdoc， toolchain

3）最后一步勾选 MSYS

会启动安装。先择 [1] basic

![msys](https://github.com/Mark24Code/rime-auto-deploy/blob/main/images/windows/01-install-ruby/step6-dev-chain.png)

可能需要等很久。

如果中断。也可以下载

https://repo.msys2.org/distrib/x86_64/msys2-x86_64-20221028.exe

直接手动安装，安装位置可以在  C:\Ruby33-x64\msys64



# 2.安装图形依赖库

 双击安装 install_lib.bat

# 3.开始游戏例子

准备了2个例子。windows下可以双击打开

1)  ray-example/text_draw_3d.rb

2) flappy_bird/main.rb

----

# 4. 卸载 Ruby

C:\Ruby33-x64\unins000.exe

删除 C:\Ruby33-x64\msys64
