# 前言

随着互联网的普及和电子商务的兴起，药品行业也逐渐迈向线上销售。在此背景下，基于SSM框架的药品电商平台应运而生。本项目致力于实现一个功能齐全、易用性强的药品电商平台，为广大用户提供方便快捷的药品购买体验。

# 内容介绍

本项目主要包括以下模块：用户模块、商品模块、购物车模块、订单模块、支付模块等。用户可以在平台上注册、登录，浏览商品，将商品加入购物车，下订单并完成支付。同时，平台还提供了后台管理功能，方便管理员对商品、订单等进行管理。

# 技术介绍

## 语言：Java
## 使用框架：Spring Springmvc，MyBatis
## 前端技术：JS、Vue、CSS3
## 开发工具：IDEA/Eclipse
## 数据库：MySQL 5.7/8.0
## 数据库管理工具：phpStudy/Navicat
## JDK版本：JDK 1.8
## Maven：Apache-Maven 3.8.1-bin
## 前端环境：Node.js 12\14\16

# 核心代码

以下为项目中商品模块的部分核心代码：

```java
// 商品实体类
public class Product {
    private Integer id; // 商品ID
    private String name; // 商品名称
    private BigDecimal price; // 商品价格
    private String description; // 商品描述
    // getter和setter方法省略
}

// 商品Mapper接口
public interface ProductMapper {
    // 查询所有商品
    List<Product> getAllProducts();
    // 根据ID查询商品
    Product getProductById(Integer id);
    // 新增商品
    int insertProduct(Product product);
    // 更新商品
    int updateProduct(Product product);
    // 删除商品
    int deleteProduct(Integer id);
}

// 商品Service层
@Service
public class ProductService {
    @Autowired
    private ProductMapper productMapper;

    public List<Product> getAllProducts() {
        return productMapper.getAllProducts();
    }

    public Product getProductById(Integer id) {
        return productMapper.getProductById(id);
    }

    public int insertProduct(Product product) {
        return productMapper.insertProduct(product);
    }

    public int updateProduct(Product product) {
        return productMapper.updateProduct(product);
    }

    public int deleteProduct(Integer id) {
        return productMapper.deleteProduct(id);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/339511/6/8773/133430/68c02db1F05b850c1/7e9909309edeee79.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336126/34/8865/46421/68c02d89F7ce50afd/50fcd9a6834e7bcc.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/343794/34/1550/77347/68c02d89F8e4d145d/2a6f084fb5851a97.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/347560/13/1545/36517/68c02d8aFa536cbfd/6205a32e572e6ed9.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/329473/22/11223/23588/68c02d8aFab86ab36/1b5fca0e221ca9d8.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/337059/19/6669/27489/68c02d8aF4f1376f5/0c6771e0941936dd.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334756/32/11349/39585/68c02d8bF4c3683fb/b6a9105adbde4a74.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/336552/31/8821/18128/68c02d8bF02a125ae/9676c8b8e366c1c5.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/334590/29/11348/43874/68c02d8bF9e58a50f/cec22d4b9534ed57.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/333811/23/11258/41748/68c02d8dFd0f765f6/60e8bd3481b0525f.jpg)

