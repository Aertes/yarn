# yarn

### 通过 npm 安装
...
**注意: ** 一般来说, 不推荐通过 npm 安装 Yarn Installing Yarn with npm is non-deterministic, the package is not signed, and the only integrity check performed is a basic SHA1 hash, which is a security risk when installing system-wide apps.

因为这些原因，高度推荐用你的操作系统最适合的方式来安装 Yarn。

如果有，你还可以通过 npm package manager 来安装 Yarn。 如果你已经装了Node.js，那你应该已经有 npm 了。
...
安装好 npm 后你可以用：

> npm install --global yarn

### 开始新项目
> yarn init

### 添加依赖包
> yarn add [package]
> yarn add [package]@[version]
> yarn add [package]@[tag]

### 升级依赖包
> yarn upgrade [package]
> yarn upgrade [package]@[version]
> yarn upgrade [package]@[tag]

### 移除依赖包
> yarn remove [package]

### 安装项目的全部依赖
> yarn
或者
> yarn install

### Yarn 工作流
<a href="https://yarnpkg.com/zh-Hans/docs/yarn-workflow" target="_blank">Yarn 工作流</a>

### CLI 介绍
<a href="https://yarnpkg.com/zh-Hans/docs/cli/" target="_blank">CLI 介绍</a>
