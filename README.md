# bilibili-simple-home

b站仿搜索引擎样式首页风格

## 安装

> 请先在浏览器安装 `Stylus` 插件，再进行以下安装

1. 安装 [Stylus for Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Firefox（不推介使用）](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

2. [点击此处安装或更新样式](https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/index.user.css)

3. [xStyle插件的在此处安装](https://ext.firefoxcn.net/xstyle/install/open.html?name=bilibili搜索引擎首页样式&code=https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/index.user.css)

4. [UserStyles.world 安装](https://userstyles.world/style/3022/bilibili)

## 快速配置

* [自定义背景](#自定义背景)

* [使用说明](#使用说明)

* [Firefox 不显示毛玻璃问题（不推介使用 Firefox）](https://github.com/hakadao/bilibili-simple-home/issues/11)

## 效果

![首页](https://userstyles.world/api/style/preview/3022.webp)

## 使用说明

点击齿轮图标及可进行样式设置

![设置](https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/preview/setting-preview.png)

### 自定义背景

1. 用 [sm.ms](https://sm.ms/) 图床上传图片

2. 复制上传后得到的图片链接

3. 按以下设置进行配置，同时需要将上面的图片链接复制到 `url()` 括号里

![自定义背景设置](https://i.loli.net/2020/09/22/OeU6xdqKCujzIL4.png)

``` css
/* 自定义背景格式 */
url(https://i.loli.net/2020/05/25/HxnieocyPIjWvQB.jpg)
```

---

## 开发

不建议去看css，写的太垃圾 = =

### 你可以

* 直接使用stylus插件点击`铅笔图标`进行编辑
![设置](https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/preview/setting-preview.png)

* 使用 `xStyle` 插件导入根目录下的 `index.user.css` 文件编辑
