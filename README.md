# Reptile-Baidu-images
本仓库代码可用于爬取百度图片

## 使用说明

如果要使用上述程序的话，需要修改两个地方：

+ `self.directory`: 这是本地存储地址，修改为自己电脑的地址，另外，**{}**不要删
+ `spider.json_count` = 10: 这是下载的图像组数，一组有30张图像，10组就是三百张，根据需求下载

运行代码[Reptile_Baidu_images.py](https://github.com/Jy-stdio/Reptile-Baidu-images/blob/main/Reptile_Baidu_images.py)
在输入框中输入想要查询下载的图像，即可进行批量下载。

![d97k56](https://ossjiyaoliu.oss-cn-beijing.aliyuncs.com/uPic/d97k56.png)

## 原理介绍
1. 获取请求url
2. 解析出图像对应的url
3. 根据图像url下载图像

更多参考详见：

1. https://blog.csdn.net/cun_king/article/details/120921849?spm=1001.2014.3001.5501
2. https://blog.csdn.net/cun_king/article/details/120936013
