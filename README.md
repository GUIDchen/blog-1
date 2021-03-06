# 个人博客cms系统V1.0

------


## 项目主要内容

### 前台
- [x] 博客主页文章列表展示
- [x] 博客分类标签展示
- [x] 博客文章详情页
- [x] 博客文章评论系统（多楼层评论）

-----

### 后台
- [x] 博客文章内容管理
- [x] 博客分类标签管理
- [x] 博客评论管理

-----

### 项目主要架构
- 前端主要页面：基于layui框架搭建的
- 后台架构：springmvc+spring+mybatis+mysql+freemarker+maven等技术架构进行开发

-----

## 项目部署
- 复制该项目到本地中
- 将项目导入到IDEA开发工具(必须有maven环境)
- 修改数据库配置文件 jdbc.properties 配置成自己的数据库参数
- 修改/src/main/java/com/xuzijia/common/Config.java 将uploadUrlRoot属性修改为自己的上传路径
- 配置tomcat配置文件server.xml 增加虚拟路径，供访问本地图片(看不懂的自行google了解~)

```
<!-- 增加虚拟路径，供访问本地图片-->
<Context path="/resource" docBase="/www/resource/system_resource" reloadable="false" ></Context>
```
-----

## 项目部分效果图预览

> *1. 博客系统主页效果图*

![博客系统主页效果图](https://raw.githubusercontent.com/xuzijia/blog/master/effect/1.png)

> *2. 博客文章详情效果图*

![博客文章详情效果图](https://raw.githubusercontent.com/xuzijia/blog/master/effect/2.png)

> *3. 文章评论楼层效果图*

![文章评论楼层效果图](https://raw.githubusercontent.com/xuzijia/blog/master/effect/4.png)

> *4. 后台管理系统文章管理*

![后台管理系统文章管理](https://raw.githubusercontent.com/xuzijia/blog/master/effect/16.png)
![后台管理系统文章管理](https://raw.githubusercontent.com/xuzijia/blog/master/effect/17.png)

> *5. 后台管理系统分类标签管理*

![后台管理系统分类标签管理](https://raw.githubusercontent.com/xuzijia/blog/master/effect/18.png)

> *6. 后台管理系统评论管理*

![后台管理系统评论管理](https://raw.githubusercontent.com/xuzijia/blog/master/effect/19.png)
![后台管理系统评论管理](https://raw.githubusercontent.com/xuzijia/blog/master/effect/20.png)

> *7. 后台管理系统登陆页面*
![后台管理系统登陆页面](https://raw.githubusercontent.com/xuzijia/blog/master/effect/21.png)

> *8. 后台管理系统菜单管理（**功能暂未开发~**）*

![后台管理系统菜单管理](https://raw.githubusercontent.com/xuzijia/blog/master/effect/11.png)

> *9. 后台管理系统网盘管理（**功能暂未开发~**）*

![后台管理系统网盘管理](https://raw.githubusercontent.com/xuzijia/blog/master/effect/13.png)
![后台管理系统网盘管理](https://raw.githubusercontent.com/xuzijia/blog/master/effect/14.png)

------


> **再一次感谢您花费时间阅读这份文档，star一下吧 嘿嘿~~~**

作者： **xuzijia**    
最后一次修改时间：*2018 年 05月 07日*    

