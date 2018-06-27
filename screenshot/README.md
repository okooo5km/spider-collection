# screenshot

用于获取指定网址页面的长截图。

## 依赖

- selenium库
- PhantomJS

`pip3 install selenium` 可以安装 `selenium`库。

访问[http://phantomjs.org/download.html ](http://phantomjs.org/download.html)下载对应版本`PhantomJS`，解压后把`bin`目录下的`phantomjs`放至`$PATH`路径下，比如：`/usr/local/bin`

## 使用

修改文件中参数：

- `URL`：指定网址
- `PIC_PATH`：图片的存放位置
- `PIC_NAME`：图片要保存的名称

```sh
python3 screenshot.py
```
即可运行。

## 有关

[爬虫实践之网页长截图](https://www.smslit.top/2018/06/27/spider-practice-page-screenshot/)
