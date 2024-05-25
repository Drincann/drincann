
  <img align="right" src='https://github-readme-stats-git-master-drincann.vercel.app/api/top-langs/?username=drincann&theme=nord&layout=compact&langs_count=10&hide=jupyter%20notebook&hide_border=true&border_radius=0' width="60%"/>
  <img align="right" src='https://github-readme-stats-git-master-drincann.vercel.app/api?username=drincann&show_icons=true&theme=nord&count_private=true&hide_border=true&border_radius=0' width="60%"/>

# Drincann [![HitCount](https://hits.dwyl.com/Drincann/Drincann.svg?style=flat-square)](http://hits.dwyl.com/Drincann/Drincann)

> What i can not create, i do not understand. —— Richard Feynman

Two steps to understand how a system works:

- **Get a general high-level idea.**

- **Deconstruct it from the low-level and re-implement it in a simplest way**。

[笔记本](http://codingfor.life)

[知乎](https://www.zhihu.com/people/gao-jun-kang)

[CSDN](https://blog.csdn.net/qq_16181837)

# 一些有趣的项目

- [Mirai-js](https://github.com/Drincann/Mirai-js)

  Mirai-js，一个运行在 Node.js、浏览器(UMD)下的，简单的 QQ 机器人开发框架。

- [pico-code-snippets](https://github.com/Drincann/pico-code-snippets)
  
  在 Raspberry pi pico 板子上开发的库，抽象了 Polling 过程，实现了基于事件循环的无栈协程调度器，为上层逻辑提供异步 api。

- [tiny-text-crdt](https://github.com/Drincann/tiny-text-crdt)

  一个 400 行的 Text CRDT 的玩具实现，它在分布式去中心化环境下实现了最终强一致性。
  
- [py-coroutine](https://github.com/Drincann/py-coroutine)

  协程调度器的底层调度逻辑的 python 实现 (eventloop / eventqueue / asyncapi / io)。
  
- [js-coroutine](https://github.com/Drincann/js-coroutine)

  适配 Thunk/Promise 的上层协程调度逻辑封装。
  
- [c-coroutine](https://github.com/Drincann/c-coroutine)
  
  尝试使用通过 c 宏实现的生成器、Promise 以及 epoll 在 c 中实现一个协程的抽象。

- [Promise](https://github.com/Drincann/Promise)
  
  Promise 实现。
  
- [angie-dotnet](https://github.com/Drincann/angie-dotnet)

  Web 后端开发框架，实现了动态路由和中间件。

- [soft-renderer](https://github.com/Drincann/cg-soft-renderer)

  软渲染器的 c 实现。

- [captcha-identification](https://github.com/Drincann/captcha-identification)

  使用卷积神经网络的验证码识别解决方案。
  
- [koa-shutdown-gracefully](https://github.com/Drincann/koa-shutdown-gracefully) 

  用来对服务器进行优雅停机，以平滑重启 Koa 应用。
  
- [Pico-Go](https://github.com/Drincann/Pico-Go)
  
  最近复活的一个 vscode 插件，几乎是在 vscode 上开发 Raspberry pi pico 的唯一选择，fork from 半年前停止维护的 [cpwood/Pico-Go](https://github.com/cpwood/Pico-Go).
  
- [noteServer](https://github.com/Drincann/noteServer)

  我的博客所有代码都在这里，文章都是 .md，整个博客几乎是静态的，服务端只提供了从文件系统生成侧栏结构的接口。
  文章托管在 gitee 上，用[这个脚本](https://github.com/Drincann/script/blob/master/autoupload.py)自动推送，服务端会定时拉取。
  
- [angie-java](https://github.com/Drincann/angie-java)
  
  一个用 Java 写的玩具 Web 框架，底层是 socket，简单地解析请求报文，简单地响应客户端。
  
- [hebauURPSpider](https://github.com/Drincann/hebauURPSpider)

  用于 hebau 教务系统的爬虫，可以生成某个学号范围内的学分绩排名，它的设计很糟糕，现在也许可以勉强跑起来。
  
- [py-functional-chaining](https://github.com/Drincann/py-functional-chaining)

  Python 常用内置容器函数式方法的链式调用包装器。
  
- [uploadImg](https://github.com/Drincann/uploadImg)

  用于方便地将图片上传到 oss 服务，并生成一个 markdown 图片到你的剪贴板，它的设计同样糟糕，但运行良好。
  
- [serializer](https://github.com/Drincann/serializer)

  一个简单的 JavaScript 对象序列化器实现。
  
- [ReverseProxy](https://github.com/Drincann/ReverseProxy)
  
  反向代理服务器的实现。
  
- koa 中间件的实现
  
  - [koa-bodyparser](https://github.com/Drincann/koa-bodyparser) body parser
  - [koa-static](https://github.com/Drincann/koa-static) 静态资源访问服务
  - [koa-etag](https://github.com/Drincann/koa-etag) etag 中间件实现
  - [koa-router](https://github.com/Drincann/koa-router) 简单路由实现，使用 trie 实现的动态路由可以看我的另一个项目 angie-dotnet

- [answerbot-gpt](https://github.com/Drincann/answerbot-gpt)
  
  让 chatGPT 自动回答知乎的问题。
