## 移动端 web 开发技巧

#### META相关

##### 1. 添加到主屏后的标题（IOS）

    <meta name="apple-mobile-web-app-title" content="标题">

####  2. 启用 WebApp 全屏模式（IOS）
当网站添加到主屏幕后再点击进行启动时，可隐藏地址栏（从浏览器跳转或输入链接进入并没有此效果）
    <meta name="apple-mobile-web-app-capable" content="yes" /> 
    <meta name="apple-touch-fullscreen" content="yes" /> 