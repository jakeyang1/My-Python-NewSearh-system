
这个工程主要分为两个部分


一部分负责抓取指定的新闻的网页信息，并存取到数据库中

另一部分是建立相应的搜索引擎的东西，用来进行前端显示


**使用技术：**

采用了Scrapy框架，

使用html搭建简单的页面

通过ajax请求想后台服务器请求指定的查询信息

使用webpy搭建简答的后台服务，

使用Fiddler在抓取新闻内容的过程中，检查网页加载过程中的网络请求和响应。