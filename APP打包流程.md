# Jenkins打包APP操作方法
## 一、打开jenkins地址：
<a href ="http://192.168.1.20:8080"> 打包链接</a>

测试打包登录名为： liguiming  12345678

后台打包登录名为：backend   12345678

产品打包登录名为： product  12345678

## 二、登录后选择要打包APP的项目，点击构建，如下图

福利金融为fljr_android 和fljr_ios

好货商城为hhsc_android和hhsc_ios

![](https://i.imgur.com/6wt4Nbg.png)


## 三、输入版本分支和要打包的环境

![](https://i.imgur.com/UKuhHMD.png)

3.1版本分支由客户端提供，在对应钉钉群公告中，或者直接问客户端人员

3.2托管接口地址和H5地址在：<a href ="http://192.168.20.121/doku.php?id=web:tuoguan">托管地址 </a> 中查看

3.3存管接口地址和H5地址在：<a href ="http://192.168.20.121/doku.php?id=web:site"/>存管地址 </a> 中查看

3.4如果后台人员需要调试可以将接口地址指向自己本机的IP地址

## 四、构建APP
点击开始构建，构建完成后点击本次构建，然后点击控制台输出，然后拉到最下边，点击链接进行下载APP压缩包，解压缩包即可获取APP

![](https://i.imgur.com/dEswnAW.png)

![](https://i.imgur.com/c2y9zno.png)

![](https://i.imgur.com/LmgbTc1.png)

## 五、安装APP
###安卓安装APK：

1、链接电脑，将APK拖入手机内存中

2、链接电脑，使用360，应用宝等第三方应用将APK安装到手机中

3、将APK发送到钉钉，QQ中，在钉钉和QQ中接收安装

###IOS安装ipa：

1、机器需要到苹果开发人员中注册设备（必须注册设备，否则安装失败）

2、第二次即可自己使用工具安装，如itools，PP助手等