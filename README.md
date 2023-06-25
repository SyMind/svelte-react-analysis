# 比较在 Taro 中使用 React 和 Svelte 的区别

## 方法

### 1. 初始项目比较

根据下面步骤来初始化 React、PReact 和 Svelte 项目，分别执行 `taro build --type weapp` 命令，比较各 `dist` 目录的体积。

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

再安装 [Taro Svelte 插件](https://github.com/SyMind/tarojs-plugin-svelte)，根据插件文档修改项目的配置，并修改代码。

# 结果

## 打包体积

|        | 初始项目   |
| ------ | ---------- |
| Svelte | 169kb ⭐️ |
| React  | 307kb      |
| PReact | 193kb      |
