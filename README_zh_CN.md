 [English](README.md)

# 思源笔记标题自动编号插件

## 简介

这是一个为思源笔记设计的标题编号插件。它可以帮助你为文档中的标题添加规范的编号，使文档结构更加清晰。

## 功能特点

1. **分级编号**
   - 一级标题：使用中文数字（一、二、三……）
   - 二级标题：使用数字编号（1.1、1.2、1.3……）
   - 三级及以下标题：使用多级数字编号（1.1.1、1.1.2……）

2. **手动控制**
   - 可以随时为当前文档添加编号
   - 可以随时清除当前文档的编号
   - 不会自动修改文档，避免意外更改

3. **格式规范**
   - 一级标题：编号后直接接标题文本（例：一、引言）
   - 二级及以下标题：编号后添加空格（例：1.1 背景介绍）

## 使用方法

1. **添加标题编号**
   - 打开需要编号的文档
   - 点击右上角的编号图标（⑪）
   - 在弹出的菜单中选择"为当前文档添加编号"

2. **清除标题编号**
   - 打开需要清除编号的文档
   - 点击右上角的编号图标（⑪）
   - 在弹出的菜单中选择"清除当前文档编号"

## 注意事项

1. 插件只会处理当前打开的文档
2. 编号操作不可撤销，请谨慎使用清除功能
3. 如果文档中已有编号，插件会先清除原有编号再重新添加

## 安装方法

1. 下载发布包
2. 解压到思源笔记的插件目录
   - Windows: `%APPDATA%/SiYuan/plugins/`
   - MacOS: `~/Library/Application Support/SiYuan/plugins/`
   - Linux: `~/.config/SiYuan/plugins/`
3. 重启思源笔记

## 开发者信息

- 作者：[你的名字]
- 许可证：MIT
- 项目地址：[GitHub 仓库地址]

## 更新日志

### v1.0.0 (2024-01-xx)

- 初始发布
- 实现基本的标题编号功能
- 支持手动添加和清除编号