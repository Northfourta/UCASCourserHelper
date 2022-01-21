# UCASCourserHelper

----

由于[UCAS](http://sep.ucas.ac.cn/)的课程网站无法进行批量下载课件（太反人类了），本人写了一个爬虫小程序，只需手动输入用户名、密码、验证码，即可实现课件的自动下载，解放双手。

## 1. 依赖库

+ requests
+ BeautifulSoup4
+ Image
+ os

## 2. 基本思路

使用requests库请求得到网页内容，BeautifulSoup 解析网页内容。验证码原本打算采用tesseract库进行OCR识别，但无奈识别效果不佳（有空再研究研究），最终选择人工输入验证码。

![sep首页](sep%E9%A6%96%E9%A1%B5.png)

## 3. 演示效果

![效果展示](%E6%95%88%E6%9E%9C%E5%B1%95%E7%A4%BA.gif)
