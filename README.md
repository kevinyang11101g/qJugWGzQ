# 前言

欢迎来到我们的基于SSM（Spring、SpringMVC、MyBatis）的幼教管理系统项目。本项目致力于为幼儿园提供一个便捷、高效的管理平台，实现幼儿园在日常工作中对各项事务的信息化管理。以下是本项目的详细介绍。

## 内容介绍

本项目主要包括以下模块：幼儿信息管理、教职工管理、课程安排、考勤管理、收费管理等。通过这些模块，幼儿园可以轻松实现对各项事务的统一管理，提高工作效率。此外，本项目还采用前后端分离的开发模式，前端使用Vue框架，后端使用Java语言及SSM框架，确保系统的稳定性、可扩展性和易维护性。

## 技术介绍

- **语言**：Java
- **使用框架**：Spring、SpringMVC、MyBatis
- **前端技术**：JS、Vue、CSS3
- **开发工具**：IDEA/Eclipse
- **数据库**：MySQL 5.7/8.0
- **数据库管理工具**：phpstudy/Navicat
- **JDK版本**：jdk1.8
- **Maven**：apache-maven 3.8.1-bin
- **前端环境**：Node.Js 12\14\16

## 核心代码

以下是本项目中的一段核心代码，展示了如何使用MyBatis实现幼儿信息查询：

```java
// Mapper接口
public interface ChildMapper {
    List<Child> selectChildList(@Param("name") String name);
}

// Mapper.xml
<select id="selectChildList" resultType="Child">
    SELECT * FROM child WHERE name LIKE CONCAT('%', #{name}, '%')
</select>
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

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/340556/21/8961/115979/68c06c46Fba9b2d7f/34218436bf477483.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/342158/4/1215/29886/68c06c1eFe2fff220/ca1b38255558272a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/345734/18/1613/53321/68c06c1eF7e5a6ca0/f0db31f39ecdc6b2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/339517/11/8848/25953/68c06c1fFe05a1fcd/0407edd044603268.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/323554/7/18437/83934/68c06c1fF85a84ab5/5952c5e2a5e4c67f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/329798/5/11358/29104/68c06c20F6100af9b/21b084b2f3bae188.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/334984/9/11360/26046/68c06c20F12e8836c/911855858bba0ed8.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/334533/3/11389/66570/68c06c20F7eab6db6/ca1b937c38216f35.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326229/1/18147/32587/68c06c21F25830246/2e976838478ae06d.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/323446/20/18476/27481/68c06c21F37dcbaa2/6343b2e159618092.jpg)

