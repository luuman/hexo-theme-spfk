　　** Hexo 主题：**用了yilia主题一段时间，感觉还有很多可以提高的地方，就查阅资料，对其进行粗类的修改，但是，有其实还有很多不完善的地方，欢迎大家前捧场。
没想到，这么多人喜欢黑色版本的，建议不是每个人都喜欢我的这些功能，所以准备个基础版本，插件可以看教程自行安装。

[文章链接](http://luuman.github.io/2015/12/21/GitHub+Hexo/)   

hexo-theme-spfk
================
          
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


![luuman-ipad-iphone](https://raw.githubusercontent.com/luuman/luuman.github.io/master/resoures/luuman-ipad-iphone.jpg)
![iPhone6](https://raw.githubusercontent.com/luuman/luuman.github.io/master/resoures/iPhone6-mockup.jpg)

##一、关于主题：
         

##二、使用

#### 安装

```
$ git clone https://github.com/luuman/hexo-theme-spfk.git themes/spfk
```

#### 配置

修改hexo根目录下的 `_config.yml` ： `theme: spfk`

#### 更新

```
cd themes/spfk
git pull
```

##三、配置

主题配置文件在主目录下的`_config.yml`：[_config.yml](http://luuman.github.io/2015/12/21/GitHub+Hexo/)   

```


#### Header
J:\Hexo\Hexo\themes\spfk\_config.yml
menu:
  主页: /
  所有文章: /archives
  # 随笔: /tags/随笔

    #是否开启多说评论，填写你在多说申请的项目名称 duoshuo: duoshuo-key（http://duoshuo-key.duoshuo.com/）
    #若使用disqus，请在博客config文件中填写disqus_shortname，并关闭多说评论
    duoshuo: true
    
J:\Hexo\Hexo\themes\spfk\source\css\多说.css

```
#### 头像
 头像尺寸大概200*200px




#### Bug

如有Bug欢迎大家前来反馈！
