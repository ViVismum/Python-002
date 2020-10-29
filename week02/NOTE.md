学习笔记
20201011 
了解到s = requests.Session()可以重复使用同一个session ，实现做到，发出的所有请求之间保持 相同cookie
学习了反爬虫的一些基本知识
不熟悉JavaScript，可以用webdriver辅助与浏览器交互点击
学习了代理ip的配置，改写中间件，作为自定义配置代理IP，毕竟windows上没有export xxx 代理的设置，更好兼容其他平台
了解了分布式爬虫的一些基本概念，可使用redis集群，作为各scrapy机器群的共享存储相互通信，最后可以把redis 落入到 mysql关系型数据库
