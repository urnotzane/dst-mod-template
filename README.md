# dst-mod-template

## What is this?
饥荒模组开发模板

## About the files
- `modinfo.lua` 定义mod的基本信息（比如名字，版本，描述等）另外它里面还可以添加mod的配置信息
- `modmain.lua` 游戏启动时会自动加载的文件，在里面可以调用饥荒暴露出来的api

- `modicon.png` is an image of the icon, and `modicon_blank.png` is a blank version of the icon.
- `modicon.tex` is the compressed texture that the game actually uses for the icon, and `modicon.xml` is the atlas file describing the icon's bounds.

The `/other` directory contains material pertaining to the video, such as the cheat sheet. 

## 模组脑暴
- [ ] 加入服务器时发送至某个地方
- [ ] 范围内自动浇水机器