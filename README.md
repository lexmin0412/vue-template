# Vue3 单页应用模板【WIP】

Vue 单页应用模板，用于个人项目的基座，免去每次初始化项目的繁琐过程，使用的框架/库包括 Vue3、TypeScript，依赖管理工具为 PNPM，构建工具为 Vite。

## 相关仓库

|仓库名|仓库地址|说明|
|---|---|---|
|react-template|https://github.com/lexmin0412/react-template|react 单页应用模板|

## 技术栈

- Vue V3
- TypeScript V5
- PNPM V7
- Vite V4

## 搭建步骤

此模板的搭建步骤如下，记录下来用于后续其他项目的开发。

### 1. 初始化空间

通过 vite 官方脚手架来初始化应用模板。

```shell
npx create-vite
```

依次输入目录名、选择 Vue、TypeScript，然后 cd 进入目录，通过 code . 打开目录。

### 2. 配置 npm 源

在根目录创建 .npmrc 文件，然后填入以下内容：

```shell
registry=https://registry.npmmirror.com/
```

### 3. 安装依赖

使用 pnpm 安装依赖：

```shell
pnpm install
```

### 4. 配置IDE

推荐使用 VSCode，安装以下插件：

- [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
- [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)

安装完成后，打开 .vue 文件，底部区域将会出现一个 TypeScript 版本，点击可以切换（选择与 VSCode 使用的 TypeScript 版本统一或与项目依赖的 TypeScript 配置统一）。

### 5. 初始化 Git 配置

```shell
git init
git remote add origin git@github.com:lexmin0412/react-template.git
git add .
git commit -m 'feat: init project'
git push -u origin master
```
