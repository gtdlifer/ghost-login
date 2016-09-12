#Ghost-login

#使用帮助详见
[liinux](http://www.cnblogs.com/liinux)
## 模拟登录一些常见的网站


主要基于以下的 Java的第三 library 
1. [httpclient](http://hc.apache.org/downloads.cgi) HTTP请求以及响应
2. [Selenium](http://docs.seleniumhq.org/download/) 模拟自动登录
3. [tesseract-ocr](https://github.com/tesseract-ocr) 验证码识别
4. [bouncy castle](http://www.bouncycastle.org/) 加密解密

## Done
1. [百度](https://www.baidu.com)(已经实现)
2. [新浪微博](https://passport.weibo.cn/signin/login?entry=mweibo&res=wel&wm=3349&r=http%3A%2F%2Fm.weibo.cn%2F%3Fjumpfrom
%3Dwapv4%26tip%3D1) (验证码识别困难，建议不要使用)
3. [腾讯微博](http://w.t.qq.com/touch) (还有点问题)
4. [知乎](https://www.zhihu.com/#signin)(已经实现)


##Todolist
0. **重构代码，增加可扩展性**
1. 增加新浪微博网页版的登录 (已解决)
2. 增加 QQ 空间 和 QQ 邮箱的登录
3. 重新组织文件结构和代码风格，make it esay to read;
4. 增加可扩展性，方便添加新的功能, 现在开发新功能的例子还很不优雅。

## tips of pull request 

欢迎大家一起来 pull request 

0. pull request 尽量做到JDK1.8版本的兼容。
1. 增加新的网站登录
2. 改进错误, JDK1.8版本的兼容
3. 基于模拟登录增加新的功能。

## something to add

0. 这个项目开始于 2016.9.11，有些网站改了规则，可能模拟登录不能使用了，授人以鱼不如授人以渔，后面会维护几个典型的模拟登录，并且会给出每个模拟登录的教程，初步考虑是视频，这样对于刚刚接触爬虫，对于抓包分析技术一脸懵逼的初学者来说比较友好，后面可能会更新图文的教程。教程目前制作中;
1. 项目写了一段时间后，发现代码的风格和程序的易用性，可扩展性，代码的可读性，都存在一定的问题，所以接下来最重要的是重构代码，让大家可以更容易的做出一些自己的小功能。
2. 如果你觉得某个网站的登录很有代表性，欢迎在 issue 中提出，
如果网站的登录很有意思，我会在后面的更新中加入
3. 网站的登录机制有可能经常的变动，所以当现在的模拟的登录的规则不能使用的时候，请在 issue 中提出
如果时间允许的话，我会更新。

## 交流讨论

1. QQ群：开源Java爬虫QQ群:322937592