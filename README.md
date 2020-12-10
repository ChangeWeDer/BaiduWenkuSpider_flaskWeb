# BaiduWenkuSpider_flaskWeb
以web server形式实现对百度文库文档以pdf形式原格式下载
如果觉得可以的话，可以点个**🌟**哦 
（当前爬取方式已经不支持，仅提供flask开发参考）

## 前言
首先，这是根据
[https://github.com/M010K/BaiduWenkuSpider](https://github.com/M010K/BaiduWenkuSpider)
的项目进行一点修改得到的基于flask框架的python web项目，
可以对百度文库的文档转换为pdf格式进行下载

**[博客地址](https://www.upstudy.top/index.php/archives/21/)**

## 如何使用？
#### 一、下载项目zip包，或者直接用git获取

**$ git clone https://github.com/ChangeWeDer/BaiduWenkuSpider_flaskWeb**


#### 二、安装依赖
项目使用的依赖有
1. requests
2. chardet
3. bs4
4. Pillow
5. pdfkit
6. flask
7. imgkit
8. img2pdf

cd到项目文件夹中使用命令，直接一键安装
**pip install -r requirements.txt**

#### 三、安装wkhtmltopdf工具
[官网下载地址](https://wkhtmltopdf.org/downloads.html)

下载后按当前系统
配置环境变量即可

**window：**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200421234401464.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80Mzg3ODMzMg==,size_16,color_FFFFFF,t_70)

**Centos：**

[https://blog.csdn.net/LookingTomorrow/article/details/93513457](https://blog.csdn.net/LookingTomorrow/article/details/93513457)

#### 四、直接运行GetAll.py文件，访问http://127.0.0.1:5000/post 即可（运行在服务器端则访问IP：5000/post）

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200421234635967.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80Mzg3ODMzMg==,size_16,color_FFFFFF,t_70)

ps：ppt格式的文档不支持预览
#### 五、Github源码下载地址
[https://github.com/ChangeWeDer/BaiduWenkuSpider_flaskWeb](https://github.com/ChangeWeDer/BaiduWenkuSpider_flaskWeb)
