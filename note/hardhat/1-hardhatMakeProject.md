# 1-hardhat创建工程

首先需要安装node环境,由于我是mac环境，且已经安装了brew包管理工具，通过下面的命令行，便可以安装node
```shell
brew install node # 安装node
node -v # 查看node version,也可以查看是否安装成功
```
创建工程目录，安装hardhat
```shell
pwd #查看当前路径
mkdir fyy #创建你所需要使用的项目名
cd fyy #进入项目下
npm init # 初始化
npm install --save-dev hardhat # 安装hardhat
```
**小提示**
官方文档中描述，hardhat不能安装在全局，可以保证环境重现和避免未来的版本冲突

通过运行下列命令
```shell
npx hardhat
```

如下是运行此命令的结果
```shell
$npx hardhat
888    888                      888 888               888
888    888                      888 888               888
888    888                      888 888               888
8888888888  8888b.  888d888 .d88888 88888b.   8888b.  888888
888    888     "88b 888P"  d88" 888 888 "88b     "88b 888
888    888 .d888888 888    888  888 888  888 .d888888 888
888    888 888  888 888    Y88b 888 888  888 888  888 Y88b.
888    888 "Y888888 888     "Y88888 888  888 "Y888888  "Y888

👷 Welcome to Hardhat v2.11.0 👷‍

? What do you want to do? …
❯ Create a JavaScript project
  Create a TypeScript project
  Create an empty hardhat.config.js
  Quit
```
**小提示**
官方文档中描述，推荐使用typescript