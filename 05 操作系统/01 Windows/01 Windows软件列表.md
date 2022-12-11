[TOC]

# 1 TortoiseGit

官网地址：https://tortoisegit.org/

# 2 TreeSize

官网地址：https://www.jam-software.com/

# 3 VS Code

## 3.1 安装

## 3.2 插件以及美化

1. vscode-icons ---  主题图标库
2. 美化之添加背景图片

```css
/*修改vscode css文件，workbench.desktop.main.css*/  
body{
    background-image: url("picture/vscode-6067736_960_720.jpg");
    background-size: 100%;
    opacity: 0.9;
    background-repeat: no-repeat;
  }
```

效果：

<img src="../../00%20picture/image-20221023235814333.png" align="left" />



## 3.3 卸载

1. 控制面板卸载
2. 删除插件

<kbd>Win</kbd> + <kbd>R</kbd>，输入%userprofile%，删除:file_folder:.vscode目录

<img src="../../00%20picture/image-20221023152400969.png" align="left" />

```bat
%userprofile%
```

3. 删除用户信息以及缓存

<kbd>Win</kbd> + <kbd>R</kbd>，输入%appdata%，删除:file_folder:code以及:file_folder: Visual Studio Code文件夹