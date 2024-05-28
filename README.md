# Ruby Game Example

* Repo: https://github.com/Mark24Code/ruby-windows-example
* Author: Mark24Code


# 0.下载 Ruby

下载网站 https://rubyinstaller.org/downloads/

直接下载链接 https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-3.3.1-1/rubyinstaller-devkit-3.3.1-1-x64.exe


# 1.安装 Ruby

安装  rubyinstaller-devkit-3.3.1-1-x64.exe



1）注意勾选 添加到 PATH

2）组件勾选，可以不勾选 rdoc

3）安装 MSYS toolchain

4）最后完成的时候，会有检查 MSYS

这步比较冗长，依赖网络。建议全局翻墙

这部可以就让他进行。可以继续下面的步骤。安装图形依赖。

```
gpg: 目录‘/etc/pacman.d/gnupg/openpgp-revocs.d’已创建
gpg: 吊销证书已被存储为‘/etc/pacman.d/gnupg/openpgp-revocs.d/ECFA82DDA6851F6A6C528ED53887AB2F60148761.rev’
gpg: Done
==> 正在更新可信数据库...
gpg: marginals needed: 3  completes needed: 1  trust model: pgp
gpg: 深度：0  有效性：  1  已签名：  0  信任度：0-，0q，0n，0m，0f，1u
==> 正在从 msys2.gpg 添加密钥...
==> 正在本地签名密钥环中的可信密钥...
  -> 已本地签名 5 把密钥。
==> 正在导入拥有者信任值...
gpg: setting ownertrust to 4
gpg: setting ownertrust to 4
gpg: setting ownertrust to 4
gpg: setting ownertrust to 4
gpg: setting ownertrust to 4
```

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

注：msys64 可能被占用，无法删除，系统重启后可以删除。
