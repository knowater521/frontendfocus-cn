# 前端聚焦周刊：第 436 期

这里是 [Frontend Focus](https://frontendfoc.us/latest) 的中文翻译项目，每周在 [己思](https://ohmyrss.com/?fef) 平台首发。

> 原文：[Frontend Focus issue 436](https://frontendfoc.us/issues/436)
> 
> 翻译及校对：[richshaw2015](https://github.com/richshaw2015)，[Yully Che](https://github.com/chechebecomestrong)

## 🚀 刊首

#### [如何用 `performance.measureMemory()` 检测页面的内存使用](https://frontendfoc.us/link/86774/rss "web.dev")

Learn how to measure memory usage of your web page in production to detect regressions. (Chrome only, for now.)

[![](https://res.cloudinary.com/cpress/image/upload/w_1280,e_sharpen:60/v1586965328/kw2xzpv1oragnlmajied.jpg)](https://frontendfoc.us/link/86774/rss)

*来源：Ulan Degenbaev*

#### [Edge 81 发布说明](https://frontendfoc.us/link/86775/rss "docs.microsoft.com")

Version 81 of Microsoft Edge [hit the stable channel yesterday](https://frontendfoc.us/link/86776/rss), bringing with it the new [built-in Collections feature](https://frontendfoc.us/link/86777/rss), DevTools localization in 10 new languages, updates to the 3D View tool, and more.

*来源：Microsoft*

#### [什么是 'JAMstack' 以及如何开始](https://frontendfoc.us/link/86779/rss "www.freecodecamp.org")

A good explainer that goes through exactly what JAMstack is and how to take advantage of its benefits. (_Psst, we’ve recently launched a [JAMstack newsletter](https://frontendfoc.us/link/86780/rss)_.)

![](https://www.freecodecamp.org/news/content/images/2020/02/content-mesh-1.jpg)

*来源：Colby Fayock*

#### [jQuery 3.5.0 发布](https://frontendfoc.us/link/86781/rss "blog.jquery.com")

A notable security fix (for a cross-site scripting vulnerability), plus some features additions, fixes and depreciations.

*来源：Timmy Willison (jQuery Foundation)*

#### [前端开发的十个安全提示](https://frontendfoc.us/link/86785/rss "hackernoon.com")

A pretty decent list of recommendations aimed at frontend devs for securing a website or app, including tips on CSP, XSS, third-party scripts, and more.

![](https://hackernoon.com/drafts/qb5732ov.png)

*来源：Konstantin Lebedev*

#### 🐦 Seen on Twitter —— Microsoft, PLEASE consider this 😂

> “I am still disappointed that Edge didn't take the opportunity to name the Canary channel 'Bleeding Egde' and the Beta channel 'Cutting Edge'.”

*来源：[Tierney Cyren](https://frontendfoc.us/link/86782/rss) on Twitter*

## 📙 文章、教程、观点

#### [如何在 JavaScript 中创建粒子动画](https://frontendfoc.us/link/86792/rss "www.smashingmagazine.com")

Anna Prenzel explains how to easily program a small trail of particles with anime.js.

![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/b4df8668-e60b-4767-9452-3f641c90dbd0/4-partical-trail-animation-javascript.gif)

*来源：Smashing Magazine*

#### [CSS 系统字体栈参考](https://frontendfoc.us/link/86786/rss "alligator.io")

Takes a detailed look at a recommended CSS font stack that uses system fonts (e.g. `-apple-system`) for an optimized cross-platform solution.

```css
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
               Roboto, Oxygen-Sans, Ubuntu, Cantarell,
               "Helvetica Neue", sans-serif;
}
```

*来源：Alligator.io*

#### [Web Accessibility 介绍](https://frontendfoc.us/link/86787/rss "www.edx.org")

The availability of this free online course from the W3C’s Web Accessibility Initiative has been [extended through until the end of May](https://frontendfoc.us/link/86788/rss). It’s designed to provide a strong foundation for making sites/apps work well for people with disabilities, meet international standards, and enhance UX for all web users.

*来源：W3C course*

#### [响应式图片的简单实现方式](https://frontendfoc.us/link/86789/rss "cloudfour.com")

A look at handling resolution switching using the `srcset` and `sizes` attributes.

![](https://29comwzoq712ml5vj5gf479x-wpengine.netdna-ssl.com/wp-content/uploads/2020/03/summary.png)

*来源：Scott Vandehey*

#### [高效开发动画的建议](https://frontendfoc.us/link/86790/rss "css-tricks.com")

A concise list of tips focused on how to efficiently build animations (using GSAP).

*来源：Zach Saucier*

#### [替换 GIF 获得惊人的性能提升](https://frontendfoc.us/link/86791/rss "swizec.com")

*来源：Swizec Teller*

#### [使用 GitHub Actions 进行 WordPress 持续部署](https://frontendfoc.us/link/86793/rss "css-tricks.com")

Shipping code to a production server often requires paid services. With GitHub Actions, Continuous Deployment is free for everyone. Read how to set that up.

![](https://i2.wp.com/css-tricks.com/wp-content/uploads/2020/03/dzCWT0Yg.png?w=1600&ssl=1)

*来源：Steffen Bewersdorff*

#### [React 开发中的 CSS 变量](https://frontendfoc.us/link/86794/rss "joshwcomeau.com")

A solid look at how to use CSS variables (custom properties) in your next project. (_If you’re working with React, we have [a newsletter for that too](https://frontendfoc.us/link/86795/rss)!_)

*来源：Josh W Comeau*

#### [仅使用 3 个属性开发响应式 CSS 网格布局](https://frontendfoc.us/link/86796/rss "www.js-craft.io")

![](http://www.js-craft.io/wp-content/uploads/2020/04/Screen-Shot-2020-04-13-at-12.55.52.png)

*来源：Daniel Nastase*

#### [使用 CSS 在圆圈内设置文本](https://frontendfoc.us/link/86797/rss "css-tricks.com")

![](https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/03/text-circle-03.png?w=1200&ssl=1)

*来源：Kerry Smyth*

#### [提醒： Bootstrap 5 不再支持 IE](https://frontendfoc.us/link/86798/rss "github.com")

*来源：Bootstrap*

## 🔧 代码、工具、资源

#### [Flip：卡片时钟倒计时动效插件](https://frontendfoc.us/link/86799/rss "pqina.nl")

Adds an animated dynamic countdown timer to a page. No dependencies, responsive and mobile friendly, and fits any language, locale, or time zone.

![](https://res.cloudinary.com/cpress/image/upload/w_1280,e_sharpen:60/v1586943625/hgtm77tvxazwm7pg4zfp.png)

*来源：Rik Schennink*

#### [Vime：现代的视频媒体播放器](https://frontendfoc.us/link/86800/rss "vime-js.com")

Aims to be a ‘modern alternative to Video.js and Plyr’: _“The idea behind Vime is we want you to control the player, not the other way around.”_ Modular, tree-shakable, and with potential for a plugin ecosystem. [GitHub repo.](https://frontendfoc.us/link/86801/rss)

![](https://gblobscdn.gitbook.com/assets%2F-M3z-zLJGX8KsAitcZLa%2F-M4hQW7A-jU2ztua4aAg%2F-M4hQYilObPlWz5axlo7%2Fplayer-example-3.png?alt=media)

*来源：Rahim Alwer*

#### [CSS 颜色渐变生成器](https://frontendfoc.us/link/86802/rss "mybrandnewlogo.com")

Another straightforward option for generating gradients for backgrounds/other page elements. Has a decent selection of predefined gradients too.

*来源：Monokai*

#### [midori：实现动图背景的库](https://frontendfoc.us/link/86803/rss "github.com")

Built with three.js, provides support for animated transition, a configurable dynamic “camera”, and post-processing effects.

![](https://github.com/aeroheim/midori/raw/master/docs/assets/midori.1.gif)

*来源：Benjamin Pang*

#### [MonoLisa](https://frontendfoc.us/link/86804/rss)

A paid monospace font for use in coding editors. It aims to deliver a legible/pleasant reading experience over longer periods of time. Compare it to Source Code Pro, JetBrains Mono, etc, [in the playground](https://frontendfoc.us/link/86805/rss).

If you don't like paying or the license requirements seem onerous, consider [Fira Code](https://frontendfoc.us/link/86806/rss), a rather similar font released under the SIL Open Font License.

[![](https://res.cloudinary.com/cpress/image/upload/w_1280,e_sharpen:60/v1586875371/ltesquavpltgwm3ey7il.png)](https://frontendfoc.us/link/86804/rss)

## 💻 招聘

译者注：如需了解，请[查看原文](https://frontendfoc.us/issues/436)。

## 🗓 未来大事记

译者注：如需了解，请[查看原文](https://frontendfoc.us/issues/436)。

