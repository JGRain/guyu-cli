# 学习搭建cli脚手架

## 安装
### 全局安装
$ npm install -g guyu-cli
# or yarn
$ yarn global add guyu-cli

### 借助npx
创建模版

$ npx create guyu-cli <name> [-t|--template]

示例

$ npx create guyu-cli hello-cli -template dumi2-demo

## 使用
创建模版

$ guyu-cli create <name> [-t|--template]

示例

$ guyu-cli create hello-cli -t dumi2-demo
