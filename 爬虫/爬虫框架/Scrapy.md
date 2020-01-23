# Scrapy

Scrapy是Python开发的一个快速、高层次的屏幕抓取和web抓取框架，用于抓取web站点并从页面中提取结构化的数据。Scrapy用途广泛，可以用于数据挖掘、监测和自动化测试。

Scrapy是一个为了爬取网站数据，提取结构性数据而编写的应用框架。 可以应用在包括数据挖掘，信息处理或存储历史数据等一系列的程序中。

## 安装

环境：Python 2.7

```py
pip install Scrapy
```

安装完成后 命令行输入 scrapy

```python
scrapy
# 提示以下信息则安装成功
# Scrapy 1.8.0 - no active project
```

## Scrapy 命令

### bench

scrapy bench：运行benchmark测试

### fetch

scrapy fetch <url>

使用Scrapy下载器(downloader)下载给定的URL，并将获取到的内容送到标准输出。

### startproject

scrapy startproject <project_name>

创建项目

### genspider

scrapy genspider [-t template] <name> <domain>

在当前项目中创建spider

### crawl

scrapy crawl <spider>

使用spider进行爬取

### check

scrapy check [-l] <spider>

运行contract检查