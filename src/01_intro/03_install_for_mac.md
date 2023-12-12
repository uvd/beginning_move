# 安装Sui
为了能更好的学习move语言，我们首先需要安装Sui的命令行，大家如果学习过别的编程语言，可以理解为安装Move的编译器


## brew 方式安装

brew 是最常用的MacOS 自带的包管理工具，如果你的电脑还没有安装过brew管理工具可以用下面命令行安装,
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
更详细的安装brew的教程参考 [brew.sh](https://brew.sh/)

首先添加官方的 tap 地址
```shell
brew tap mystenlabs/tap
```

安装`Sui`命令行
```shell
brew install mystenlabs/tap/sui
```
检查是否安装成功
```shell
sui --version
```
sui 1.13.0-64fe2b6871

## 预编译好的二进制安装
官方已经在github上 `https://github.com/MystenLabs/sui/releases` 根据最新的分支选择mac平台的已经编译好的二进制

> 注意，如果你的用的是 M系列的芯片请选择 `*-macos-arm64.tgz` 结尾的压缩文件 ，intel系列的芯片选择 `*-macos-x86_64.tgz` 结尾的安装包


## 从源代码编译安装






