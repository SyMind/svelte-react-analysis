# 比较在 Taro 中使用 React 和 Svelte 的区别

## 方法

### 1. 初始项目比较

#### React 初始化步骤

```bash
taro init react-initial-app
```

命令选择如下：

```
请选择框架             React
是否需要使用           TypeScript
请选择 CSS 预处理器     Sass
请选择编译工具          Webpack5
请选择包管理工具        yarn
请选择模板源            Gitee（最快）
请选择模板              默认模板
```

#### PReact 初始化步骤

```bash
taro init preact-initial-app
```

命令选择如下：

```
请选择框架             PReact
是否需要使用           TypeScript
请选择 CSS 预处理器     Sass
请选择编译工具          Webpack5
请选择包管理工具        yarn
请选择模板源            Gitee（最快）
请选择模板              默认模板
```

#### Svelte 初始化步骤

```bash
taro init svelte-initial-app
```

官方命令中还未支持 Svelte 项目的初始化，故先创建一个 React 项目，命令选择如下：

```
请选择框架             React
是否需要使用           TypeScript
请选择 CSS 预处理器     Sass
请选择编译工具          Webpack5
请选择包管理工具        yarn
请选择模板源            Gitee（最快）
请选择模板              默认模板
```

安装 [Tarojs Plugin Svelte](https://github.com/SyMind/tarojs-plugin-svelte)，并根据其文档修改项目的配置。
