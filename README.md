# RENT_CRAWL
高德API+python爬虫解决租房问题

最终效果图如下：

![](https://doc.shiyanlou.com/document-uid8834labid1978timestamp1470211337353.png/wm)

如图，划出来的大片蓝色色块就是距离工作地点一小时车程内的区域。蓝色的标记就是房源，点击后会自动给出路径规划和房源地址。红色标记（不是"终"）是工作地点,在图里被挡住了。工作地点的输入框有自动补完的功能，也是很方便的。至于房源文件我们会通过编写 Python 脚本在抓取房源信息后生成。

输入 python3 -m http.server 3000 打开服务器，浏览器访问 http://localhost:3000 查看效果
