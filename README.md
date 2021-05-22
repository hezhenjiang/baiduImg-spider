# baiduImg-spider
爬取百度图片

# 介绍
本项目通过puppeteer实现自动输入关键字自动搜索百度图片最后完成图片下载

# 使用方法

git clone https://github.com/php-tzh/baiduImg-spider.git

cd baiduImg-spider

npm install

npm run start --word=关键字 --num=图片下载数量 --dir=图片下载目录 --delay=图片下载延迟（ms）

------------hezhenjiang  test20210522---------------
widows安装nodejs14  gitbash测试成功
运行指令为：
node .\baidu-img.js --word=反光衣 --num=1000 --dir=./dataset1/反光衣 --delay=200
