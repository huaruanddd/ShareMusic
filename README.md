# ShareMusic

技术选型：Springboot+Mybatis+Vue


预计实现功能:

游客通过注册成为正式用户

游客功能:查看正式用户的歌单,并可以在线听歌

正式用户功能:创建删除歌单,添加删除歌单内的歌曲

用户可以上传歌曲并添加至alibaba的oss

在线播放歌曲时从oss下载播放

正式用户可以关注正式用户



项目构建计划：

实现后台用户登录注册系统:

创建一个允许用户创建和修改的歌单系统:

允许用户自由上传歌曲,并保存在网络中(alibaba oss)

实现歌曲的在线播放功能



项目实现细节:

使用Swagger-Ui编写在线文档

使用redis实现缓存功能(注册的验证码)

整合SpringSercurity+JWT实现认证和授权

整合oss实现文件上传

在线播放器-->



项目数据库:

用户表(用户个人信息)

歌单表(歌单信息)

歌曲表(歌曲信息)

用户关注表(用户关注的用户列表)



前端(Vue):

    目前还不会
    












