# 豆瓣租房信息管理系统

## require

`PHP>=7.0`
 
`mysql`

`composer`

## 安装

```bash
cd /path/to/your/application
composer install
cp .env.example .env
php artisan key:generate
```

配置`.env`文件


导入`sql/init.sql`文件到MYSQL数据库

`nginx|apache`，将网站路径(root路径)配置到项目路径下的`public`文件夹即可。

具体配置文件写法可以参考[Laravel配置](https://docs.golaravel.com/docs/5.6/installation/)

## 体验
地址：http://douban.jwlchina.cn/douban


帐号：`test`

密码：`test`


## 截图

![图1](http://www.jwlchina.cn/uploads/Douban/DoubanAdmin1.png)
![图2](http://www.jwlchina.cn/uploads/Douban/DoubanAdmin2.png)


## 租房信息爬虫（配合使用）
[DoubanGroupSpider](https://github.com/kong36088/DoubanGroupSpider)
