# ocProject

java SSM快速开发仿慕课网在线教育平台

分布式 三个项目

pc端：首页轮播图 个人中心 课程学习 评论回复 

运营平台：后台配置

wechat端：菜单 消息互动 个人中心 课程学习

微信接收普通消息api：
https://mp.weixin.qq.com/wiki?t=resource/res_main&id=mp1421140453

消息互动的本质：微信发送过来的消息为xml 解析xml放到实体类中 然后处理数据
构造图文信息 转化为xml 然后传给wechat  wechat进行处理 显示出来。

七牛云图片 整合
新浪sae
微信公众号