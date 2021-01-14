<!--
 * @Author: your name
 * @Date: 2021-01-13 09:21:51
 * @LastEditTime: 2021-01-13 09:54:30
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /seflinkcdn_project/cdnUserTutorial/cdnUserTutorial.md
-->

# 3步开始使用cdn加速服务

## step1. 注册账号并登陆

进入meson.network官网  <https://meson.network>

注册成为 cdn 用户

![avatar](./img/reg1.png)

注意勾选 cdn 用户

![avatar](./img/reg2.png)

## step2. 创建资源加速链接

进入后台管理页面的 Client=>BindDomain 页面,

![avatar](./img/bind1.png)

创建资源加速链接

![avatar](./img/bind2.png)

在红色框中填写您网站静态资源的链接,例如您想给您网站中所有的图片资源加速,如果您的图片都存储在您网站根目录 /static/img 目录下,您就可以在这里填写您网站的域名+目录,比如 www.yourdomain.com/static/img

点击 Check Input Url

如果验证无误,按钮会变成绿色,点击 Add Record

![avatar](./img/bind3.png)

创建成功后,会在下面下方显示您创建的加速链接

![avatar](./img/bind4.png)

## step3. 替换网页中原静态资源链接为加速链接

替换资源链接

![avatar](./img/use1.png)

将您需要加速的资源链接,替换为上一步中您生成的链接,如上图中,将红色框的内容,替换为新的链接
如果您的网页支持https,请使用 https://, 如果不支持,那就请使用 http://