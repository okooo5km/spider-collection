# ttpic

爬取头条图集图片的命令行工具，使用库：

- requests
- urllib
- os
- hashlib
- multiprocessing
- functools

## 使用

```sh
$ ./ttpic 关键字 请求个数
```

- 关键字: 图片搜索关键词
- 请求个数: 一次请求会获取20个图集的图片

## 举例

```sh
# 获取100个图集中狗狗的图片
$ ./ttpic 狗狗 5
```
