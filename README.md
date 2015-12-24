![luuman-ipad-iphone](https://raw.githubusercontent.com/luuman/luuman.github.io/master/img/luuman-ipad-iphone.jpg)
![iPhone6](https://raw.githubusercontent.com/luuman/luuman.github.io/master/img/iPhone6-mockup.jpg)
hexo-theme-spfk
================

Yilia 是为 [hexo](https://github.com/tommy351/hexo) 2.4+制作的主题。
崇尚简约优雅，以及极致的性能。 你可以点击 [我的博客](http://litten.github.io/) 查看效果。           
 
如遇到问题或有需求，可以：
* 提issue给我
* 在这篇文章下留言[Hexo主题Yilia](http://litten.github.io/2014/08/31/hexo-theme-yilia/)
* 移动端问题留言[Yilia在移动端适配的一些事](http://litten.github.io/2015/02/23/yilia-on-mobile/)

我都会看到并处理。

如果你想体验手机浏览效果，可以扫一下二维码：

![litten-qrcode](https://cloud.githubusercontent.com/assets/2024949/6349328/51a067fe-bc64-11e4-881c-f68050c50c28.png)

—————————————————————

主题结构：

    .
    ├── languages         #多语言
    |   ├── default.yml  #默认语言
    |   └── zh-CN.yml    #中文语言
    ├── layout           #布局，根目录下的*.ejs文件是对主页，分页，存档等的控制
    |   ├── _partial     #局部的布局，此目录下的*.ejs是对头尾等局部的控制
    |   └── _widget      #小挂件的布局，页面下方小挂件的控制
    ├── source           #源码
    |   ├── css          #css源码 
    |   |   ├── _base    #*.styl基础css
    |   |   ├── _partial    #*.styl局部css
    |   |   ├── fonts       #字体
    |   |   ├── images      #图片
    |   |   └── style.styl #*.styl引入需要的css源码
    |   ├── fancybox      #fancybox效果源码
    |   └── js            #javascript源代码
    ├── _config.yml       #主题配置文件
    └── README.md         #用GitHub的都知道

关于主题：

1. 我喜欢简约。所以近期文章，搜索框都拿掉了    
2. 接地气一点。所以用上了jiathis分享，友言评论，以及baidu的cdn       
3. 追求移动端的体验
3. 让大家把注意力放到内容上。这是本主题设计初衷      
4. 主题不支持IE6，7，8。以后也不会        

##一、近期更新

    2015.6.14 - 模块化加载
    2015.2.21 - 移动侧重构&布局bug修改
    2014.11.7 - 增加“友情链接”“关于我”               
    2014.10.22 - 优化fancybox展示               
    2014.10.16 - 增加表格样式                 
    2014.9.19 - 云标签挂件                 

##二、使用

#### 安装

``` bash
$ git clone https://github.com/litten/hexo-theme-yilia.git themes/yilia
```

#### 配置

修改hexo根目录下的 `_config.yml` ： `theme: yilia`

#### 更新

``` bash
cd themes/yilia
git pull
```

##三、外观


##四、配置

主题配置文件在主目录下的`_config.yml`：[_config.yml](http://luuman.github.io/2015/12/21/GitHub+Hexo/)   

```
# Header
menu:
  主页: /
  所有文章: /archives
  # 随笔: /tags/随笔

    #是否开启多说评论，填写你在多说申请的项目名称 duoshuo: duoshuo-key（http://duoshuo-key.duoshuo.com/）
    #若使用disqus，请在博客config文件中填写disqus_shortname，并关闭多说评论
    duoshuo: true

```
# 头像
 头像尺寸大概200*200px

##五、其他

[同步你的instagram图片](https://github.com/litten/hexo-theme-yilia/wiki/%E5%90%8C%E6%AD%A5%E4%BD%A0%E7%9A%84instagram%E5%9B%BE%E7%89%87)



bug抓取：

* 移动端友情链接靠的太近
    * 修改他们之间的间距(mobile-slider.styl)
* 侧边栏展示的内容有限
    * 添加侧边栏滚动轴
 * 你好
    * 第
* 你好
    * 第
* 你好
    * 第
