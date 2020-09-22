# bilibili-simple-home

b站仿搜索引擎样式首页风格，支持几种不同显示效果

## 安装

> 请先在浏览器安装`Stylus`插件，再进行以下安装

1. 安装 [Stylus for Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/) 或者 [Cascadea for Safari](https://cascadea.app/)

2. [点击此处安装或更新样式](https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/index.user.css)

3. [xStyle插件的在此处安装](https://ext.firefoxcn.net/xstyle/install/open.html?name=bilibili搜索引擎首页样式&code=https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/index.user.css)

## 快速配置

* [自定义背景](#自定义背景)

* [使用说明](#使用说明)

## 效果

预设效果
![预设效果](https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/preview/preview-1.png "预设效果")

【样式1】半屏显示壁纸
![【样式1】半屏显示壁纸](https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/preview/preview-2.png "【样式1】半屏显示壁纸")

【样式2】半屏显示壁纸
![【样式2】半屏显示壁纸](https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/preview/preview-3.png "【样式2】半屏显示壁纸")

## 使用说明

点击齿轮图标及可进行样式设置

![设置](https://cdn.jsdelivr.net/gh/hakadao/bilibili-simple-home@master/preview/setting-preview.png)

### 自定义背景

1. 用 [sm.ms](https://sm.ms/) 图床上传图片

2. 复制上传后得到的图片链接

3. 按住以下设置进行配置，同时需要将上面的图片链接复制到 `url()` 括号里

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

* 使用`xStyle`插件导入根目录下的`index.user.css`文件

直接使用stylus插件编辑

> 目录名字 ``XXXXX_XXXX`` 对应的是stylish的 ``/*[[XXX_XXX]]*/`` 插入符，是用来后期填充替代插入符号来实现自定义样式的。**但这些与样式没太大关系，这里单独放出来只是方便查看**
