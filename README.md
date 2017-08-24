# 获取京东商品四级分类的小爬虫，使用python3实现

## 1.首先从(https://www.jd.com/allSort.aspx)这个网站解析到所有第三级分类的链接，我已经获取好放在list里面

## 2.安装python3和依赖库(pip Install -r requirements.txt)

## 3.启动爬虫，python spider.py，结果会保存在程序运行目录，result.xlsx


# 参考结构

| 一级分类        | 二级分类          |三级分类 |四级分类 |
| ------------- |:-------------:|:-----:|:-----:|
| 家用电器        | 平板电视          |大家电 |价格 |
| 家用电器        | 平板电视          |大家电 |屏幕尺寸 |
| 家用电器        | 平板电视          |大家电 |电视类型 |
| 家用电器        | 平板电视          |大家电 |分辨率 |