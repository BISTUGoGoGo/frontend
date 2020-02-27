# 商业网站模板

这是一个商业产品模板

## 基本结构

### 首页 index.js [bpus_20_obaju/index.html]

1、顶部链接栏：可以链接到登录页、注册页、联系页(公用)

2、顶部分类栏：可以跳转到主页、男装、女装、搜索框、购物车界面（公用）

3、轮播图效果：展示商品主要的banner

4、主要产品：产品可以旋转放大的CSS效果

5、界面博客：显示新闻动态

6、页脚企业信息（公用）

### 注册界面 [register.html]

公用部分不重复

这里是一个注册/用户登录界面：界面是若干表单（用户名、密码、邮箱、注册等）

### 用户账户界面 [customer-orders.html]

登录成功后跳转到这个界面

左侧是分类栏：可以查看我的信息；我的订单、登出账户等


### 联系界面 [contact.html]

可以跳转到三个次级界面

/text.html 介绍公司的描述信息

/contact.html 介绍公司的联系方式和联系地址

/faq.html 介绍公司的问答情况


### 购物车界面 [basket.html]

显示以及有的购物界面内容，这里需要和后端数据库交互

### 商品分类界面 [category.html]

具体商品的分类和实现


### 商品详情界面 [detail.html]

点击商品分类界面，可以跳转到商品详情界面中


## 主要技术

主要使用下面的样式

~~~html
<!-- Bootstrap CSS-->
<link rel="stylesheet" href="vendor/bootstrap/css/bootstrap.min.css">

<!-- Font Awesome CSS-->
<link rel="stylesheet" href="vendor/font-awesome/css/font-awesome.min.css">

<!-- Google fonts - Roboto -->
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:100,300,400,700">

<!-- owl carousel-->
<link rel="stylesheet" href="vendor/owl.carousel/assets/owl.carousel.css">
<link rel="stylesheet" href="vendor/owl.carousel/assets/owl.theme.default.css">

<!-- theme stylesheet-->
<link rel="stylesheet" href="css/style.default.css" id="theme-stylesheet">

<!-- Custom stylesheet - for your changes-->
<link rel="stylesheet" href="css/custom.css">
~~~

主要使用下面的脚本

~~~html
<script src="vendor/jquery/jquery.min.js"></script>
<script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
<script src="vendor/jquery.cookie/jquery.cookie.js"> </script>
<script src="vendor/owl.carousel/owl.carousel.min.js"></script>
<script src="vendor/owl.carousel2.thumbs/owl.carousel2.thumbs.js"></script>
<script src="js/front.js"></script>
~~~

