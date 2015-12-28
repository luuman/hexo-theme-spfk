hexo-theme-spfk
================
          
![luuman-ipad-iphone](https://raw.githubusercontent.com/luuman/luuman.github.io/master/resoures/luuman-ipad-iphone.jpg)
![iPhone6](https://raw.githubusercontent.com/luuman/luuman.github.io/master/resoures/iPhone6-mockup.jpg)
 


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

##一、关于主题：
         

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

##三、配置

主题配置文件在主目录下的`_config.yml`：[_config.yml](http://luuman.github.io/2015/12/21/GitHub+Hexo/)   

```
#### Header
menu:
  主页: /
  所有文章: /archives
  # 随笔: /tags/随笔

    #是否开启多说评论，填写你在多说申请的项目名称 duoshuo: duoshuo-key（http://duoshuo-key.duoshuo.com/）
    #若使用disqus，请在博客config文件中填写disqus_shortname，并关闭多说评论
    duoshuo: true

```
#### 头像
 头像尺寸大概200*200px


#### bug抓取：

* 移动端友情链接靠的太近
    * 修改他们之间的间距(mobile-slider.styl)
* 侧边栏展示的内容有限
    * 添加侧边栏滚动轴
