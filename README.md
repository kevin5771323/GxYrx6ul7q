# 餐厅点餐微信小程序（SpringBoot版）

## 前言

随着移动互联网的普及，越来越多的餐饮企业开始关注线上点餐业务。为了满足餐厅线上点餐的需求，我们开发了一套基于微信小程序的餐厅点餐系统。本项目采用SpringBoot框架，结合前端Uniapp技术，实现了一套功能完善、易用性强的餐厅点餐微信小程序。

## 内容介绍

本项目主要包括以下功能模块：用户模块、菜品模块、订单模块、管理员模块等。用户可以在微信小程序上查看餐厅菜单、点餐、下单，管理员可以在后台管理系统中对菜品、订单等进行管理。通过微信支付功能，用户可以方便地完成支付，提高餐厅运营效率。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为项目中的部分核心代码：

```java
// 菜品服务类
@Service
public class DishService {

    @Autowired
    private DishMapper dishMapper;

    // 根据菜品ID查询菜品信息
    public Dish getDishById(Integer dishId) {
        return dishMapper.selectById(dishId);
    }

    // 查询所有菜品
    public List<Dish> getAllDishes() {
        return dishMapper.selectAll();
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/342208/35/3002/132372/68c58090F0cf8813f/6357a4b42950bff8.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/326849/30/19601/14486/68c58068Fad302ce9/efb0f3d6beb51817.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/325872/11/19918/80584/68c58068F15632f98/1850cbb281922e97.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329712/24/12705/52012/68c58069Fefddd345/0e33c6f00c3f0603.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/334345/17/13056/77409/68c58069F2c2414f8/04b81f472c14c818.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348425/39/3081/47828/68c58069F5c5645a0/0b51ec918eefaf59.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/329526/14/12798/66986/68c58069Fbb8cb9da/bddf9736b13281b9.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331229/24/12823/38412/68c58069F526669cd/b163684a7eddc197.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/334113/7/12968/30352/68c5806aF74b17948/3e4c5ed1153bc99a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/336662/25/10476/66978/68c5806aF63a3f258/6f01f4e3b0cbf740.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
