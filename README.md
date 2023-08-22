# zhilianxiaozhao-visual
基于 python3.9 + selenium4.2.0 + xpath + flask + echarts，爬取智联校园招聘（智联招聘），进行可视化大屏展示。【数据分析】


### 目的：

针对智联校园招聘收录的岗位名称,公司名称,薪资,城市,公司规模,企业类型,学历,岗位职责,发布时间,详情页面等信息进行爬取、清洗和可视化分析。

### 准备：

#### 1.找到想要爬取的网站（[[https://yz.chsi.com.cn/zsml/queryAction.do](https://xiaoyuan.zhaopin.com/)]

![image](https://github.com/Mingdaj/zhilianxiaozhao-visual/assets/130920375/e2e8e6cd-0454-4cd6-b1e9-169a57419aeb)


#### 2.分析网页的请求响应（json）结构，以及规划想要爬取的信息

![image](https://github.com/Mingdaj/zhilianxiaozhao-visual/assets/130920375/86138fad-d698-440c-a7fe-6210aedd6aec)


### 搭建/运行

#### 1. 环境

Python3.9+各种库

#### 2. 数据爬取

使用的是 selenium4.2.0 版本的API，可降版本或者改方法/参数

#### 3. 数据分析+可视化大屏

- 可视化大屏

运行：

- 运行app.py:

![image](https://github.com/Mingdaj/zhilianxiaozhao-visual/assets/130920375/c73e6140-b167-472f-be7b-f4ff88ae95d9)


- 以浏览器的方式打开index.html:

![image](https://github.com/Mingdaj/zhilianxiaozhao-visual/assets/130920375/104cc87d-d05d-40a6-b3d4-b279e743b387)



结果【如果网页显示发生错误，先确保app.py在运行，然后重新打开html】：

![image](https://github.com/Mingdaj/zhilianxiaozhao-visual/assets/130920375/f296920e-dbc4-44f2-b517-2345f0d97282)


- 爬虫

运行：

![image](https://github.com/Mingdaj/zhilianxiaozhao-visual/assets/130920375/f3c9572c-0d78-4211-b2ef-32b84f7ffe07)


- 数据清洗

![image](https://github.com/Mingdaj/zhilianxiaozhao-visual/assets/130920375/550f8ac6-0993-49e5-95a7-63de0d7f0971)


- 获取经纬度（这里注意selenium的版本，主要是提供可视化大屏中的地理位置信息）

![image](https://github.com/Mingdaj/zhilianxiaozhao-visual/assets/130920375/588cbdf1-5c1c-4b5c-a03f-9964563e95f3)



有偿分享，非诚勿扰！

QQ：2790810983

助理QQ：3539048933

