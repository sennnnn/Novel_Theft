# 轻文解析器

爬取轻小说，并打包成 EUPB，插图只嵌入开头。

## 用法

python main.py --task [main/picture]

>--task main 为将 txt 以及图片 url 解析并存放至 txt 中。  
>--task picture 为下载图片 url 并存放到对应文件夹。  

## 后记

用上了多线程，学习了正则表达式，能够做自己喜欢做的事情真是太好了。  
第一次写爬虫经验不足，多线程也是用的很粗糙，还没有考虑用协程，而且这还是最简单的不需要一些  
其他的 web 手段就能成功的爬虫，看来还是需要精进。之后比较想尝试通过多层代理来高速并安全地  
下载。