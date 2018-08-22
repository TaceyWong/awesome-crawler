# Awesome-crawler ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
A collection of awesome web crawler,spider and resources in different languages.
不同编程语言的优秀网页爬虫资源集合

## Contents
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
* [Scrapy](https://github.com/scrapy/scrapy) - A fast high-level screen scraping and web crawling framework.快速的高级网页抓取框架
    * [django-dynamic-scraper](https://github.com/holgerd77/django-dynamic-scraper) - Creating Scrapy scrapers via the Django admin interface.
    * 通过Django的管理接口创建Scrapy爬虫
    * [Scrapy-Redis](https://github.com/rolando/scrapy-redis) - Redis-based components for Scrapy.
    * Scrapy 的Redis插件
    * [scrapy-cluster](https://github.com/istresearch/scrapy-cluster) - Uses Redis and Kafka to create a distributed on demand scraping cluster.
    * 使用Redis和Kafka创建一个分布式按需抓取集群
    * [distribute_crawler](https://github.com/gnemoug/distribute_crawler) - Uses scrapy,redis, mongodb,graphite to create a distributed spider.
    * 使用Scrapy、redis、mongodb、graphite来创建一个分布式爬虫
* [pyspider](https://github.com/binux/pyspider) - A powerful spider system.
* 一个强大的爬虫系统
* [cola](https://github.com/chineking/cola) - A distributed crawling framework.
* 一个分布式抓取框架
* [Demiurge](https://github.com/matiasb/demiurge) - PyQuery-based scraping micro-framework.
* 给予PyQuery的微型抓取框架
* [Scrapely](https://github.com/scrapy/scrapely) - A pure-python HTML screen-scraping library.
* 纯Python实现的HTML网页抓取库
* [feedparser](http://pythonhosted.org/feedparser/) - Universal feed parser.
* 通用feed解析器
* [you-get](https://github.com/soimort/you-get) -  Dumb downloader that scrapes the web.
* 傻瓜式多媒体资源下载器（视频、音乐、图片）
* [Grab](http://grablib.org/) - Site scraping framework.
* 网站抓取框架
* [MechanicalSoup](https://github.com/hickford/MechanicalSoup) - A Python library for automating interaction with websites.
* 用于同网站进行自动化交互的Python库
* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy.
* 基于Scrapy的可视化爬虫
* [crawley](https://github.com/jmg/crawley) - Pythonic Crawling / Scraping Framework based on Non Blocking I/O operations.
* 给予非阻塞I/O操作的Python风格抓取框架
* [RoboBrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser.
* 一个简单、Python化的网页浏览库，不必使用独立的网页浏览器
* [MSpider](https://github.com/manning23/MSpider) - A simple ,easy spider using gevent and js render. 
* 一个使用gevent和js渲染的简单易用爬虫
* [brownant](https://github.com/douban/brownant) - A lightweight web data extracting framework.
* 一个轻量级网页数据提取框架
* [PSpider](https://github.com/xianhu/PSpider) - A simple spider frame in Python3.
* Python3实现的简单爬虫框架
* [Gain](https://github.com/gaojiuli/gain) - Web crawling framework based on asyncio for everyone.
* 基于asyncio实现的网页抓取框架
* [sukhoi](https://github.com/iogf/sukhoi) - Minimalist and powerful Web Crawler.
* 小而强大的网页爬虫
* [spidy](https://github.com/rivermont/spidy) - The simple, easy to use command line web crawler.
* 简单易用的命令行网页爬虫
* [newspaper](https://github.com/codelucas/newspaper) - News, full-text, and article metadata extraction in Python 3
* Python3实现的新闻、全文本、文章元数据提取工具包

## Java
* [ACHE Crawler](https://github.com/ViDA-NYU/ache) - An easy to use web crawler for domain-specific search.
* 用于特定领域搜索的简单易用网页爬虫
* [Apache Nutch](http://nutch.apache.org/) - Highly extensible, highly scalable web crawler for production environment.高度可扩展的生产环境网页爬虫
    * [anthelion](https://github.com/yahoo/anthelion) - A plugin for Apache Nutch to crawl semantic annotations within HTML pages.
    * 用于抓取HTML页面内语义标注的Nutch插件
* [Crawler4j](https://github.com/yasserg/crawler4j) - Simple and lightweight web crawler.
* 简单轻量级网页爬虫
* [JSoup](http://jsoup.org/) - Scrapes, parses, manipulates and cleans HTML.
* 抓取、解析、处理和清洗HTML的工具包
* [websphinx](http://www.cs.cmu.edu/~rcm/websphinx/) - Website-Specific Processors for HTML information extraction.
* 用于HTML信息提取的特定网站处理器
* [Open Search Server](http://www.opensearchserver.com/) - A full set of search functions. Build your own indexing strategy. Parsers extract full-text data. The crawlers can index everything.
* 一整套搜索功能。构建你自己的索引策略。解析器提取全文本数据。爬虫能索引一切
* [Gecco](https://github.com/xtuhcy/gecco) - A easy to use lightweight web crawler
* 一个易于使用的轻量级网页爬虫
* [WebCollector](https://github.com/CrawlScript/WebCollector) - Simple interfaces for crawling the Web,you can setup a multi-threaded web crawler in less than 5 minutes.
* 爬取网页的简单借口，你可以在5分钟之内构建一个多线程网页爬虫
* [Webmagic](https://github.com/code4craft/webmagic) - A scalable crawler framework.
* 一个可扩展的爬虫框架
* [Spiderman](https://git.oschina.net/l-weiwei/spiderman) - A scalable ,extensible, multi-threaded web crawler.可扩展多线程网页爬虫
    * [Spiderman2](http://git.oschina.net/l-weiwei/Spiderman2) - A distributed  web crawler framework,support js render.
    * 一个分布式网页爬虫框架，支持js渲染
* [Heritrix3](https://github.com/internetarchive/heritrix3) -  Extensible, web-scale, archival-quality web crawler project.
* 可扩展，大规模，高质量归档的网页爬虫项目。
* [SeimiCrawler](https://github.com/zhegexiaohuozi/SeimiCrawler) - An agile, distributed crawler framework.
* 一个灵活的分布式爬虫功能
* [StormCrawler](http://github.com/DigitalPebble/storm-crawler/) - An open source collection of resources for building low-latency, scalable web crawlers on Apache Storm
* 在Storm上构建低延迟、可扩展网页爬虫的资源集合
* [Spark-Crawler](https://github.com/USCDataScience/sparkler) - Evolving Apache Nutch to run on Spark.
* 在Spark上运行Nutch
* [webBee](https://github.com/pkwenda/webBee) - A DFS web spider.
* 一个DFS（深度搜索优先）爬虫


## C# 
* [ccrawler](http://www.findbestopensource.com/product/ccrawler) - Built in C# 3.5 version. it contains a simple extension of web content categorizer, which can saparate between the web page depending on their content.
* C#3.5版本。包含网页内容分类的简单扩展，可以根据网页的内容在网页之间进行访问
* [SimpleCrawler](https://github.com/lei-zhu/SimpleCrawler) - Simple spider base on mutithreading, regluar expression.
* 给予多线程、正则表达式的简单爬虫
* [DotnetSpider](https://github.com/zlzforever/DotnetSpider) - This is a cross platfrom, ligth spider develop by C#.
* C#实现的跨平台轻量级爬虫
* [Abot](https://github.com/sjdirect/abot) - C# web crawler built for speed and flexibility.
* 高速灵活的C#网页爬虫
* [Hawk](https://github.com/ferventdesert/Hawk) - Advanced Crawler and ETL tool written in C#/WPF.
* C#/WPF实现的高级爬虫和ETL工具
* [SkyScraper](https://github.com/JonCanning/SkyScraper) - An asynchronous web scraper / web crawler using async / await and Reactive Extensions.
* 使用async/await和Reactive扩展实现的异步网页爬虫

## JavaScript
* [scraperjs](https://github.com/ruipgil/scraperjs) - A complete and versatile web scraper.
* 一个完整和万能网页爬虫
* [scrape-it](https://github.com/IonicaBizau/scrape-it) - A Node.js scraper for humans.
* 人性化的Node.js爬虫
* [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler.
* 时间驱动的网页爬虫
* [node-crawler](https://github.com/bda-research/node-crawler) - Node-crawler has clean,simple api.
* Node-crawler API简单干净
* [js-crawler](https://github.com/antivanov/js-crawler) - Web crawler for Node.JS, both HTTP and HTTPS are supported.
* 为Node.js使用的Web爬虫，同时支持HTTP和HTTPS
* [webster](https://github.com/zhuyingda/webster) - A reliable web crawling framework which can scrape ajax and js rendered content in a web page.
* 可靠的可抓取ajax和js渲染内容的网页抓取框架，
* [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraper with pagination and crawler support.
* 带有分页功能的网页爬虫
* [node-osmosis](https://github.com/rchipka/node-osmosis) - HTML/XML parser and web scraper for Node.js.
* 为Node.js实现的HTML/XML解析器和网页爬虫
* [web-scraper-chrome-extension](https://github.com/martinsbalodis/web-scraper-chrome-extension) - Web data extraction tool implemented as chrome extension.
* 网页数据提取chrome扩展
* [supercrawler](https://github.com/brendonboshell/supercrawler) - Define custom handlers to parse content. Obeys robots.txt, rate limits and concurrency limits. 
* 为解析内容定义定制化的处理器。遵循robots.txt、频率限制和并发
* [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Headless Chrome crawls with jQuery support
* 支持jQuery的无头Chrome爬取

## PHP
* [Goutte](https://github.com/FriendsOfPHP/Goutte) - A screen scraping and web crawling library for PHP.PHP网页抓取库
    * [laravel-goutte](https://github.com/dweidner/laravel-goutte) - Laravel 5 Facade for Goutte.
* [dom-crawler](https://github.com/symfony/dom-crawler) - The DomCrawler component eases DOM navigation for HTML and XML documents.
* HTML、XML文档DOM访问组件
* [pspider](https://github.com/hightman/pspider) - Parallel web crawler written in PHP.
* PHP实现的并行网页爬虫
* [php-spider](https://github.com/mvdbos/php-spider) - A configurable and extensible PHP web spider.
* 一个可配置】可扩展的网页爬虫
* [spatie/crawler](https://github.com/spatie/crawler) - An easy to use, powerful crawler implemented in PHP. Can execute Javascript.
* PHP实现的易于使用而强大的爬虫实现。可以执行js代码

## C++
* [open-source-search-engine](https://github.com/gigablast/open-source-search-engine) - A distributed open source search engine and spider/crawler written in C/C++.
* 一个C/C++实现的开源分布式搜索引擎和爬虫

## C
* [httrack](https://github.com/xroche/httrack) - Copy websites to your computer.
* 克隆网站到自己的电脑

## Ruby
* [Nokogiri](https://github.com/sparklemotion/nokogiri) - A Rubygem providing HTML, XML, SAX, and Reader parsers with XPath and CSS selector support.
* 一个支持通过XPATH表达式和CSS选择器进行HTML、XML、SAX提取的Rubygem
* [upton](https://github.com/propublica/upton) - A batteries-included framework for easy web-scraping. Just add CSS(Or do more).
* 自带电池的网页爬虫框架。仅仅需要添加CSS
* [wombat](https://github.com/felipecsl/wombat) - Lightweight Ruby web crawler/scraper with an elegant DSL which extracts structured data from pages.
* 轻量级Ruby爬虫，具有从网页提取结构化数据的优雅DSL
* [RubyRetriever](https://github.com/joenorton/rubyretriever) - RubyRetriever is a Web Crawler, Scraper & File Harvester.
* 一个网页爬虫和文件收集器
* [Spidr](https://github.com/postmodern/spidr) - Spider a site ,multiple domains, certain links or infinitely.
* 爬取一个网站、多域、特定连接
* [Cobweb](https://github.com/stewartmckee/cobweb) - Web crawler with very flexible crawling options, standalone or using sidekiq.
* 具有灵活抓取选项的网页爬虫，可以单独使用，也可以配合sidekiq使用
* [mechanize](https://github.com/sparklemotion/mechanize) - Automated web interaction & crawling.
* 自动化网页交互和抓取

## R
* [rvest](https://github.com/hadley/rvest) - Simple web scraping for R.
* R实现的简单网页爬虫

## Erlang 
* [ebot](https://github.com/matteoredaelli/ebot) - A scalable, distribuited and highly configurable web cawler.
* 一个可扩展的分布式、高可配的网页爬虫

## Perl
* [web-scraper](https://github.com/miyagawa/web-scraper) - Web Scraping Toolkit using HTML and CSS Selectors or XPath expressions.
* 使用HTML、CSS选择器、XPath表达式进行网页抓取的工具包

## Go
* [pholcus](https://github.com/henrylee2cn/pholcus) -  A distributed, high concurrency and powerful web crawler.
* 一个分布式、高并发的强大网页爬虫
* [gocrawl](https://github.com/PuerkitoBio/gocrawl) - Polite, slim and concurrent web crawler.
* 优雅轻量的高兵法网页爬虫
* [fetchbot](https://github.com/PuerkitoBio/fetchbot) - A simple and flexible web crawler that follows the robots.txt policies and crawl delays.
* 一个简单而灵活的网页爬虫，遵循robots.txt规则和爬取延时
* [go_spider](https://github.com/hu17889/go_spider) - An awesome Go concurrent Crawler(spider) framework.
* 一个优秀的Go高兵法爬虫框架 
* [dht](https://github.com/shiyanhui/dht) - BitTorrent DHT Protocol && DHT Spider.
* BitTorrent协议和DHT爬虫
* [ants-go](https://github.com/wcong/ants-go) - A open source, distributed, restful crawler engine in golang.
* 一个golang实现的开源分布式、RESTfu爬虫引擎l
* [scrape](https://github.com/yhat/scrape) - A simple, higher level interface for Go web scraping.
* 简单的Golang网页爬虫高级接口
* [creeper](https://github.com/wspl/creeper) - The Next Generation Crawler Framework (Go).
* 下一代爬虫框架
* [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
* 为Go用户准备的高速而优雅的网页抓取框架

## Scala
* [crawler](https://github.com/bplawler/crawler) - Scala DSL for web crawling.
* 用与网页抓取的Scala DSL（DSL：特定领域语言，可以理解为为某些特定功能而实现的特定编程语言）
* [scrala](https://github.com/gaocegege/scrala) - Scala crawler(spider) framework, inspired by scrapy.
* Scala爬虫框架，灵感源自Scrapy（Python）
* [ferrit](https://github.com/reggoodwin/ferrit) - Ferrit is a web crawler service written in Scala using Akka, Spray and Cassandra.
* Ferrit是使用Scala&Akka&Spray&Cassandra实现的网页爬虫服务
