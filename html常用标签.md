# html常用标签

## 标题标签

 

```html
   <h1>1</h1>
    <h2>2</h2>
    <h3>3</h3>
    <h4>4</h4>
    <h5>5</h5>
    <h6>6</h6>
```

## 段落标签

```html
<p>111</p>
```



## 换行标签

```html
</br>
```



## 文本格式化标签

在网页中，有时需要为文字设置粗体、斜体和下划线等效果，这时就需要html中文本格式化标签，

突出重要性

| 语义   | 标签                      | 说明       |
| ------ | ------------------------- | ---------- |
| 加粗   | <strong></strong> <b></b> | 推荐strong |
| 倾斜   | <em></em> <i></i>         | 推荐em     |
| 删除线 | <del></del><s></s>        | 推荐del    |
| 下划线 | <ins></ins> <u></u>       | 推荐ins    |

```html
 我是<strong>加粗</strong>的文字
```

## 盒子标签

div  /div   span /span 标签

```html
<div>
    这是头部
</div>
<span>
    今日价格
</span>
```

div是一个大盒子  用来布局  每个div独占一行   一行只能放一个

span  是一个小盒子  用来布局  一行可以放多个

```html
    <div>一个div标签</div>111
    <div>一个div标签</div>222
    <span>工藤新一</span>
    <span>毛利兰</span>
    <span>铃木园子</span>
```

## 图像标签

```html
<img>  图像标签
<img src="图像URL"/>
```

src是<img>属性的必须属性  制定图像文件路径和文件名

```html
   <img src="柯南.jpg"/>
```

```html
    <h4>图像标签的使用</h4>
    <img src="柯南.jpg"/>
    <h4> alt 替换文本 图像显示不出来的时候用文字替换：</h4>
    <img src="柯南.jpg" alt="柯南柯南"/>
    <h4>title  提示文本 鼠标放在 图像上 提示的文字</h4>
    <img src="柯南.jpg" alt="名侦探柯南" title="工藤新一思密达"/ >
    <h4>width 给图像设定宽度 </h4>
    <img src="柯南.jpg" alt="名侦探柯南" title="工藤新一思密达" width="500"/ >
    <h4>width 给图像设定高度 </h4>
    <img src="柯南.jpg" alt="名侦探柯南" title="工藤新一思密达"  height="100"/ >
    <h4>给图像设置边框</h4>
    <img src="柯南.jpg" alt="名侦探柯南" title="工藤新一思密达" width="500" border ="15"/ >
```

图片标签可以拥有多个属性  必须写在标签名的后面

属性之间不分前后顺序 标签名与属性 属性与属性之间都是空格分开

属性采用键值对的方式 key="value" 的方式  属性=属性值""



## 超链接标签

语法格式

```html
<a href="跳转目标" target="目标窗口的弹出方式">文本图像</a>
```





1. 外部链接

```html
    <h4>1.外部链接</h4>
    <a href="http://www.qq.com" target="_self">腾讯</a>
    <a href="http://www.qq.com" target="_blank">腾讯</a>
    target 打开窗口的方式 默认值是_self 当前窗口 打开页面  _blank 新窗口打开
    </body>
```

2.内部链接 

```html
   <h4>1.外部链接</h4>
    <a href="http://www.qq.com" target="_self">腾讯</a>
    <a href="http://www.qq.com" target="_blank">腾讯</a>
    target 打开窗口的方式 默认值是_self 当前窗口 打开页面  _blank 新窗口打开

    <h4>2.内部链接:网页内部页面之间的链接</h4>
    <a href="gongsijianjie.html">公司简介</a>

```

3.空链接

```
    <h4>3.空链接</h4>
    <a href="#">首页</a>
```

4.下载链接

```html
    <h4>4.下载链接:地址链接的是.exe或者zip等压缩包形式 </h4>
    <a href="新兰.zip">下载文件</a>
```

5.网页元素的链接

```html
  <h4>5.网页链接</h4>
    <a href="http://baidu.com"><img src="柯南.jpg"></a>
```

6.锚点链接:快速定位到网页中某个位置

```html
    <h4>6.锚点链接</h4>
    <a href="#zuopin">主要作品</a>
    <h3 id="zuopin">主要作品 hahahhahahahahahahahahah</h3>
```

