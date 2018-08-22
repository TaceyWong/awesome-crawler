[English](README.md)

# Awesome-crawler ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
不同编程语言的优秀网页爬虫资源集合


## 目录

- [Python](#python)
- [Java](#java)
- [C#](#c)
- [JavaScript](#javascript)
- [PHP](#php)
- [C++](#c-1)
- [C](#c-2)
- [Ruby](#ruby)
- [R](#r)
- [Erlang](#erlang)
- [Perl](#perl)
- [Go](#go)
- [Scala](#scala)

## Python 
* [Scrapy](https://github.com/scrapy/scrapy) - 快速的高级网页抓取框架
    * [django-dynamic-scraper](https://github.com/holgerd77/django-dynamic-scraper) - 通过Django的管理接口创建Scrapy爬虫
    * [Scrapy-Redis](https://github.com/rolando/scrapy-redis) - Scrapy 的Redis插件
    * [scrapy-cluster](https://github.com/istresearch/scrapy-cluster) - 使用Redis和Kafka创建一个分布式按需抓取集群
    * [distribute_crawler](https://github.com/gnemoug/distribute_crawler) - 使用Scrapy、redis、mongodb、graphite来创建一个分布式爬虫
* [pyspider](https://github.com/binux/pyspider) - 一个强大的爬虫系统
* [cola](https://github.com/chineking/cola) - 一个分布式抓取框架
* [Demiurge](https://github.com/matiasb/demiurge) - 基于PyQuery的微型抓取框架
* [Scrapely](https://github.com/scrapy/scrapely) - 纯Python实现的HTML网页抓取库
* [feedparser](http://pythonhosted.org/feedparser/) - 通用feed解析器
* [you-get](https://github.com/soimort/you-get) -  傻瓜式多媒体资源下载器（视频、音乐、图片）
* [Grab](http://grablib.org/) - 网站抓取框架
* [MechanicalSoup](https://github.com/hickford/MechanicalSoup) - 用于同网站进行自动化交互的Python库
* [portia](https://github.com/scrapinghub/portia) - 基于Scrapy的可视化爬虫
* [crawley](https://github.com/jmg/crawley) - 基于非阻塞I/O操作的Python风格抓取框架
* [RoboBrowser](https://github.com/jmcarp/robobrowser) - 一个简单、Python化的网页浏览库，不必使用独立的网页浏览器
* [MSpider](https://github.com/manning23/MSpider) - 一个使用gevent和js渲染的简单易用爬虫
* [brownant](https://github.com/douban/brownant) - 一个轻量级网页数据提取框架
* [PSpider](https://github.com/xianhu/PSpider) - Python3实现的简单爬虫框架
* [Gain](https://github.com/gaojiuli/gain) - 基于asyncio实现的网页抓取框架
* [sukhoi](https://github.com/iogf/sukhoi) - 小而强大的网页爬虫
* [spidy](https://github.com/rivermont/spidy) - 简单易用的命令行网页爬虫
* [newspaper](https://github.com/codelucas/newspaper) - Python3实现的新闻、全文本、文章元数据提取工具包

## Java
* [ACHE Crawler](https://github.com/ViDA-NYU/ache) - 用于特定领域搜索的简单易用网页爬虫
* [Apache Nutch](http://nutch.apache.org/) - 高度可扩展的生产环境网页爬虫
    * [anthelion](https://github.com/yahoo/anthelion) - 用于抓取HTML页面内语义标注的Nutch插件
* [Crawler4j](https://github.com/yasserg/crawler4j) - 简单轻量级网页爬虫
* [JSoup](http://jsoup.org/) - 抓取、解析、处理和清洗HTML的工具包
* [websphinx](http://www.cs.cmu.edu/~rcm/websphinx/) - 用于HTML信息提取的特定网站处理器
* [Open Search Server](http://www.opensearchserver.com/) - 一整套搜索功能。构建你自己的索引策略。解析器提取全文本数据。爬虫能索引一切
* [Gecco](https://github.com/xtuhcy/gecco) - 一个易于使用的轻量级网页爬虫
* [WebCollector](https://github.com/CrawlScript/WebCollector) - 爬取网页的简单借口，你可以在5分钟之内构建一个多线程网页爬虫
* [Webmagic](https://github.com/code4craft/webmagic) - 一个可扩展的爬虫框架
* [Spiderman](https://git.oschina.net/l-weiwei/spiderman) - 可扩展多线程网页爬虫
    * [Spiderman2](http://git.oschina.net/l-weiwei/Spiderman2) - 一个分布式网页爬虫框架，支持js渲染
* [Heritrix3](https://github.com/internetarchive/heritrix3) -  可扩展，大规模，高质量归档的网页爬虫项目。
* [SeimiCrawler](https://github.com/zhegexiaohuozi/SeimiCrawler) - 一个灵活的分布式爬虫功能
* [StormCrawler](http://github.com/DigitalPebble/storm-crawler/) - 在Storm上构建低延迟、可扩展网页爬虫的资源集合
* [Spark-Crawler](https://github.com/USCDataScience/sparkler) - 在Spark上运行Nutch
* [webBee](https://github.com/pkwenda/webBee) - 一个DFS（深度搜索优先）爬虫


## C# 
* [ccrawler](http://www.findbestopensource.com/product/ccrawler) - C#3.5版本。包含网页内容分类的简单扩展，可以根据网页的内容在网页之间进行访问
* [SimpleCrawler](https://github.com/lei-zhu/SimpleCrawler) - 基于多线程、正则表达式的简单爬虫
* [DotnetSpider](https://github.com/zlzforever/DotnetSpider) - C#实现的跨平台轻量级爬虫
* [Abot](https://github.com/sjdirect/abot) - 高速灵活的C#网页爬虫
* [Hawk](https://github.com/ferventdesert/Hawk) - C#/WPF实现的高级爬虫和ETL工具
* [SkyScraper](https://github.com/JonCanning/SkyScraper) - 使用async/await和Reactive扩展实现的异步网页爬虫

## JavaScript
* [scraperjs](https://github.com/ruipgil/scraperjs) - 一个完整和万能网页爬虫
* [scrape-it](https://github.com/IonicaBizau/scrape-it) - 人性化的Node.js爬虫
* [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - 时间驱动的网页爬虫
* [node-crawler](https://github.com/bda-research/node-crawler) - Node-crawler API简单干净
* [js-crawler](https://github.com/antivanov/js-crawler) - 为Node.js使用的Web爬虫，同时支持HTTP和HTTPS
* [webster](https://github.com/zhuyingda/webster) - 可靠的可抓取ajax和js渲染内容的网页抓取框架，
* [x-ray](https://github.com/lapwinglabs/x-ray) - 带有分页功能的网页爬虫
* [node-osmosis](https://github.com/rchipka/node-osmosis) - 为Node.js实现的HTML/XML解析器和网页爬虫
* [web-scraper-chrome-extension](https://github.com/martinsbalodis/web-scraper-chrome-extension) - 网页数据提取chrome扩展
* [supercrawler](https://github.com/brendonboshell/supercrawler) - 为解析内容定义定制化的处理器。遵循robots.txt、频率限制和并发
* [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - 支持jQuery的无头Chrome爬取

## PHP
* [Goutte](https://github.com/FriendsOfPHP/Goutte) - PHP网页抓取库
    * [laravel-goutte](https://github.com/dweidner/laravel-goutte) - Laravel 5 Facade for Goutte.
* [dom-crawler](https://github.com/symfony/dom-crawler) - HTML、XML文档DOM访问组件
* [pspider](https://github.com/hightman/pspider) - PHP实现的并行网页爬虫
* [php-spider](https://github.com/mvdbos/php-spider) - 一个可配置】可扩展的网页爬虫
* [spatie/crawler](https://github.com/spatie/crawler) - PHP实现的易于使用而强大的爬虫实现。可以执行js代码

## C++
* [open-source-search-engine](https://github.com/gigablast/open-source-search-engine) - 一个C/C++实现的开源分布式搜索引擎和爬虫

## C
* [httrack](https://github.com/xroche/httrack) - 克隆网站到自己的电脑

## Ruby
* [Nokogiri](https://github.com/sparklemotion/nokogiri) - 一个支持通过XPATH表达式和CSS选择器进行HTML、XML、SAX提取的Rubygem
* [upton](https://github.com/propublica/upton) - 自带电池的网页爬虫框架。仅仅需要添加CSS
* [wombat](https://github.com/felipecsl/wombat) - 轻量级Ruby爬虫，具有从网页提取结构化数据的优雅DSL
* [RubyRetriever](https://github.com/joenorton/rubyretriever) - 一个网页爬虫和文件收集器
* [Spidr](https://github.com/postmodern/spidr) - 爬取一个网站、多域、特定连接
* [Cobweb](https://github.com/stewartmckee/cobweb) - 具有灵活抓取选项的网页爬虫，可以单独使用，也可以配合sidekiq使用
* [mechanize](https://github.com/sparklemotion/mechanize) - 自动化网页交互和抓取

## R
* [rvest](https://github.com/hadley/rvest) - R实现的简单网页爬虫

## Erlang 
* [ebot](https://github.com/matteoredaelli/ebot) - 一个可扩展的分布式、高可配的网页爬虫

## Perl
* [web-scraper](https://github.com/miyagawa/web-scraper) - 使用HTML、CSS选择器、XPath表达式进行网页抓取的工具包

## Go
* [pholcus](https://github.com/henrylee2cn/pholcus) -  一个分布式、高并发的强大网页爬虫
* [gocrawl](https://github.com/PuerkitoBio/gocrawl) - 优雅轻量的高兵法网页爬虫
* [fetchbot](https://github.com/PuerkitoBio/fetchbot) - 一个简单而灵活的网页爬虫，遵循robots.txt规则和爬取延时
* [go_spider](https://github.com/hu17889/go_spider) - 一个优秀的Go高兵法爬虫框架 
* [dht](https://github.com/shiyanhui/dht) - BitTorrent协议和DHT爬虫
* [ants-go](https://github.com/wcong/ants-go) - 一个golang实现的开源分布式、RESTfu爬虫引擎l
* [scrape](https://github.com/yhat/scrape) - 简单的Golang网页爬虫高级接口
* [creeper](https://github.com/wspl/creeper) - 下一代爬虫框架
* [colly](https://github.com/asciimoo/colly) - 为Go用户准备的高速而优雅的网页抓取框架

## Scala
* [crawler](https://github.com/bplawler/crawler) - 用于网页抓取的Scala DSL（DSL：特定领域语言，可以理解为为某些特定功能而实现的特定编程语言）
* [scrala](https://github.com/gaocegege/scrala) - Scala爬虫框架，灵感源自Scrapy（Python）
* [ferrit](https://github.com/reggoodwin/ferrit) - Ferrit是使用Scala&Akka&Spray&Cassandra实现的网页爬虫服务
