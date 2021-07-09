# hzy-zhihu-client-master
设计目标:<br>
---
前后端协作设计并实现一个类似知乎的问答系统，本部分是Android端项目代码，使用android studio进行开发，目前项目已基本完成。<br>

项目内容:<br>
---
User Story 1<br>
  * 用户注册<br>
  * 用户登录<br>
  * 发布问题<br>
  * 查看问题列表<br>
  * 修改问题<br>
  * 删除问题<br>
  
User Story 2<br>
  * 查看问题列表<br>
  * 回答问题<br>
  * 修改回答<br>
  * 删除回答<br>
  
User Story 3<br>
  * 热门问题列表<br>
  * 对回答点赞和踩<br>
  * 个人中心查看自己发布的问题<br>
  * 个人中心查看自己的回答<br>
  * 个人中心查看自己点赞的回答<br>
  
项目要点:<br>
---
1、本项目整体采用MVC架构<br>
2、利用RecyclerView展示问题列表。<br>
3、利用OkHttp + Retrofit + Rxjava2afnetworking进行网络请求<br>
4、数据接口定义及解析使用Android JSON 数据解析<br>
5、利用gradle进行依赖管理<br>
6、JWT作为验证token并在客户端进行缓存<br>



运行方法:<br>
---
打包下载文档，Android Studio上运行。
