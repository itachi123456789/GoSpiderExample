# Golang 土拨鼠项目爬虫示例

## 使用
1. 克隆`https://github.com/hunterhug/GoSpider`仓库到GOPATH路径下，地址：[https://github.com/hunterhug/GoSpider](https://github.com/hunterhug/GoSpider)
2. 示例仅供学习，爬虫有风险，如果太暴力，会给别人带来损失，在此申明不承担相应责任，查看Example

## Example
1.[jiandan煎蛋项目爬文章](jiandan/README.md)，多浏览器持久化cookie分布式爬虫爬取数据，使用到redis，mysql，将网页数据保存在磁盘中，详情页解析后存入数据库。中级示例！

结果，总共抓取了56,961 篇文章

![](doc/jiandan/redis.png)
![](doc/jiandan/file.png)
![](doc/jiandan/mysql.png)

详细 说明见[http://www.lenggirl.com/spider/jiandan.html](http://www.lenggirl.com/spider/jiandan.html)

2.[jiandan煎蛋项目爬妹子](jiandanmeizi/README.md)，啥Redis都不用，准备好网速就行！

![jiandanmeizi/meizi.png](jiandanmeizi/meizi.png)

已经封装了exe（自己 go build 吧），小心开车。

总共爬取了....张图片，程序会自动去重

## 环境配置
请查看[https://github.com/hunterhug/AmazonBigSpider/blob/master/china.md](https://github.com/hunterhug/AmazonBigSpider/blob/master/china.md)