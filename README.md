# Denson's Note

此项目是个人静态 blog 的源码，它具有免费、便捷、省心的特点，静态页面由 [Hexo](https://hexo.io/zh-cn/docs/) 框架生成。
可以在本地编辑也可以线编辑使用

## 运行

- `npm install` 安装所需依赖；
- `npm run server` 本地运行服务；
- `npm run build` 打包成静态页面；
- `npm run deploy` 部署生成的静态页面；

## 涉及

- [node](https://nodejs.org/zh-cn/)
- [Hexo](https://hexo.io/zh-cn/docs/)
- [GitHub Pages](https://pages.github.com/)
- [GitHub Actions](https://docs.github.com/cn/actions)

## 思路

- 使用 Hexo 来将 写好的 Markdown 编译成生成 html 页面；
- 页面存放在 Github Page 来托管页面的访问；
- Action 会执行拉取 main 分支代码编译后提交到 pg-pages 分支；

## 优点

- 省钱且免费，静态资源全存储在 GitHub 上，自己也可以注册域名绑定；
- 安全且省心，不用购买服务器，不用部署项目，不担心网站安全及流量（流量估计是想多了）问题；
- 本地调试预览方便，只需提交代码到 Github ，页面自动生成；

## 自用

如果你也想 Hexo 生成博客并它部署到 GitHub 上，你可以这样做：

- 首先将代码 fork 到自己的项目

- 修改项目名称为 `[自己Github名].github.io`

- 把代码 clone 到本地，修改`_config.yml`文件

- 提交代码就可以访问了`[自己Github名].github.io`
