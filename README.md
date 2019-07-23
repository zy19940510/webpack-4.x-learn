# Webpack 源码解析

Webpack 作为前端领域最重要的构建工具,任何一个优秀的前端工程师必定需要对它有比较深入的了解。本系列文章会带您深入理解 webpack 的实现原理，阅读关键代码，并自己实现一些简单的功能。

这个系列总共包括 8 篇文章，首先分析我们常用的一些 loader，然后看 webpack 核心代码的工作流程，最后探讨 HMR 以及 tree-shaking 等特性。

文章目录：

- [我对 webpack 的看法以及本系列文章的规划](./1-introduction.md)
- [写一个自己的 babel-loader](./2-babel-loader.md)
- [style-loader 和 css-loader](./3-style-loader-and-css-loader.md)
- [file-loader 和 url-loader](./4-file-loader-and-url-loader.md)
- [bundle.js 内容分析](./5-bundle.js.md)
- [webpack 处理流程分析](./6-process-pipe-line.md)
- [HMR 热更新原理](./7-hmr.md)
- [Tree shaking](./8-tree-shaking.md)

# 相关源码

所有相关的源码都在这里 [my-webpack-loader](https://github.com/zy19940510/my-webpack-loader)

# 提出你的问题

如果你有任何问题或者建议，欢迎以 Issue 的方式提出来共同探讨。
