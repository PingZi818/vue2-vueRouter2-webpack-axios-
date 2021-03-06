# Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版

> 如果你 clone 或者 fork 本项目之后，不能运行，说明 package-lock.json 锁定的各个工具的版本和你本地的环境有冲突，没有关系，只需要删除这个文件，然后重新安装就可以了。

```
rm -rf node_modules package-lock.json
npm i
```
> 原文
 [直接看原文主人GitHub](https://github.com/fengcms/vue-demo-cnodejs)
 
  以下为我学vue2参考的的博文，非常感谢博主热心提供的详细指导博文，还有具体开发例子。内容简介明了，都是干货，很不错的教学指南，推荐想要入门vue2的伙伴去看看：

1. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（一）基础知识概述](http://blog.csdn.net/fungleo/article/details/77575077)
2. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（二）安装 nodejs 环境以及 vue-cli 构建初始项目](http://blog.csdn.net/fungleo/article/details/77584701)
3. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（三）认识项目所有文件](http://blog.csdn.net/fungleo/article/details/77585205)
4. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（四）调整 App.vue 和 router 路由](http://blog.csdn.net/fungleo/article/details/77600798)
5. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（五）配置 Axios api 接口调用文件](http://blog.csdn.net/fungleo/article/details/77601270)
6. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（六）将接口用 webpack 代理到本地](http://blog.csdn.net/fungleo/article/details/77601761)
7. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（七）初识 *.vue 文件](http://blog.csdn.net/fungleo/article/details/77602914)
8. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（八）渲染一个列表出来先](http://blog.csdn.net/fungleo/article/details/77603537)
9. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（九）再把内容页面渲染出来](http://blog.csdn.net/fungleo/article/details/77604490)
10. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（十）打包项目并发布到子目录](http://blog.csdn.net/fungleo/article/details/77606216)
11. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（十一）阶段性小结](http://blog.csdn.net/fungleo/article/details/77606321)
12. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（十二）打包项目图片等资源的处理](http://blog.csdn.net/fungleo/article/details/77799057)
13. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（十三）集成 UEditor 百度富文本编辑器](http://blog.csdn.net/column/details/17076.html)
14. [Vue2+VueRouter2+Webpack+Axios 构建项目实战2017重制版（十四）在项目中使用 jQuery](http://blog.csdn.net/fungleo/article/details/77879328)

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
