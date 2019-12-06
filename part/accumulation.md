# 前端知识积累

1、[手机网页避免使用 100vh](https://chanind.github.io/javascript/2019/09/28/avoid-100vh-on-mobile-web.html)  
手机浏览器由于会自动显示/隐藏地址栏，所以网页如果设成高度为 100vh，会有一部分看不见，可以参考 [CSS Tricks](https://css-tricks.com/the-trick-to-viewport-units-on-mobile/) 和 [Stack Overflow](https://stackoverflow.com/questions/37112218/css3-100vh-not-constant-in-mobile-browser) 的解决方法。  
可通过CSS 设置解决  
```min-height: -webkit-fill-available;```    

2、[Node.js 编程最佳实践](https://github.com/goldbergyoni/nodebestpractices)  
该仓库收集 Node.js 编程的注意点，持续更新中。   

3、[Web 图标指南](https://dev.to/adrianbdesigns/icon-workflow-for-the-web-an-in-depth-guide-26hj)  
本文介绍四种常用的图标解决方案：CSS Sprite、图标字体、内嵌的 SVG 图像、SVG 文件。  

4、 [React Hooks 的原理](https://www.netlify.com/blog/2019/03/11/deep-dive-how-do-react-hooks-really-work/)    
本文通过简单的代码，自己做了一个 Hooks 的简单实现，讲解 React Hooks 的原理 。  

5、[CSS 如何自动切换明暗模式](https://tombrow.com/dark-mode-website-css)  
本文介绍如何让 CSS 根据不同设备，自动选择暗模式（dark mode）或明模式（light mode）。  

