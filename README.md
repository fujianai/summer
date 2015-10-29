## 项目地址
[https://github.com/zhouwenbin/summer](https://github.com/zhouwenbin/summer)

## 简介
因为业务需求，需要让运营自己能做一些简单的活动页，所以在github搜索了下，找到一个可以用的，然后做了二次开发。

## 使用方法
在需要使用的页面样式表内添加四行代码，用来块级元素居中，可以根据网站的实际情况修改宽度。
```css
.page-center{
    width: 1180px;
    margin:0 auto;
}
```
打开index.html，画完图形后，导出代码，贴到需要的页面。

## 优化内容

* 界面汉化。
* 支持大图，大图会自动替换成背景，防止出现滚动条和布局错乱。可根据网站的宽度修改`page-center`的宽度。
* 支持一个页面多个热点。
* 拖动上传的图片使用base64地址，可以根据自己服务器的情况修改为线上地址。
