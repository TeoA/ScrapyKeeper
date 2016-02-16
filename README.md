#欢迎使用 SpiderKeeper
**SpiderKeeper** 是一款基于[scrapyd](https://github.com/scrapy/scrapyd)服务的scrapy爬虫管理程序，实现了对scrapy爬虫的可视化管理，包括爬虫的启动与取消，定时抓取任务的设置和周期执行,并可对在运行爬虫的日志，运行状态进行查看。

##截图
spider管理
![spider管理](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/screenshot_1.png)
添加定时任务
![添加定时任务](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/screenshot_2.png)
抓取状态
![抓取状态](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/screenshot_3.png)
查看/取消定时任务
![查看/取消定时任务](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/screenshot_4.png)
服务器状态监控
![spider管理](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/screenshot_5.png)

##运行

    修改 dist/scripts/scripts.*.js , 设置 scrapyd 服务地址
    运行index.html,或将dist下文件部署至web服务器

or

    修改 dist/scripts/scripts.*.js , 设置 scrapyd 服务地址
    修改 SKWebService.py SKMonitor.py, 配置 scrapyd 服务地址
    启动 start.sh 


##构建

    1.安装 [node和npm](http://nodejs.org/)
    2.安装 bower `npm install -g bower`
    3.安装 grunt `npm install -g grunt`
    4.$ `bower install`
    5.$ `npm install`
    6.Run `grunt` for building and `grunt serve` for preview.
