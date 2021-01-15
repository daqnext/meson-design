# CDN用户与Miner操作指南

[TOC]

## CDN用户 3步开始使用cdn加速服务

### step1. 注册账号并登陆

进入meson.network官网  <https://meson.network>

注册成为 cdn 用户

![avatar](./img/reg1.png)

注意勾选 cdn 用户

![avatar](./img/reg2.png)

### step2. 创建资源加速链接

进入后台管理页面的 `Client=>BindDomain` 页面,

![avatar](./img/bind1.png)

创建资源加速链接

![avatar](./img/bind2.png)

在红色框中填写您网站静态资源的链接,例如您想给您网站中所有的图片资源加速,如果您的图片都存储在您网站根目录`website/static/img` 目录下,您就可以在这里填写您网站的域名+目录,比如 www.yourdomain.com/static/img

点击 `Check Input Url`

如果验证无误,按钮会变成绿色,点击 `Add Record`

![avatar](./img/bind3.png)

创建成功后,会在下面下方显示您创建的加速链接

![avatar](./img/bind4.png)

### step3. 替换网页中原静态资源链接为加速链接

替换资源链接

![avatar](./img/use1.png)

将您需要加速的资源链接,替换为上一步中您生成的链接,如上图中,将红色框的内容,替换为新的链接
如果您的网页支持https,请使用 https://, 如果不支持,那就请使用 http://


## Miner挖矿指南

您只需要一台拥有公网IP的稳定服务器,就可以成为矿工,赚取您的收益

### step1. 注册账号并登陆

进入meson.network官网  <https://meson.network>

注册成为 Terminal 用户

![avatar](./img/reg1.png)

注意勾选 Terminal 用户

![avatar](./img/reg3.png)

### step2. 下载并运行Terminal客户端

进入后台管理页面的 `Terminal=>Terminals` 页面,

![avatar](./img/terminal1.png)

使用ssh或者其他方式,登录到您的服务器,并根据页面提示,选择您操作系统对应的客户端,下载 解压并运行

![avatar](./img/terminal2.png)

首次运行时,程序会提示您需要以下内容

`token`--您的用户标识,网页上有您的用户token,复制并输入

`spaceLimit`--您提供给我们硬盘空间,程序只会使用您提供的空间,最少要求80G,提供的存储空间越大,您的收益也会越高

`port`--您对外服务的端口,请不要使用80或者443端口,并且保证您的防火墙不会拦截此端口

配置完成后,terminal就会正常运行

### step3. 在网页上检查服务器运行状态

待terminal正常运行,一般数分钟后就可以在网页下方,看到您的服务器已经上线运行
![avatar](./img/terminal3.png)

如果服务器的Status为ON的状态,说明您的服务器已经正常运行,已经被纳入我们的加速网络中

### step4. 使用任意方式,将Terminal运行在后台

您可以用任何您喜欢的方式,让Terminal程序稳定运行在后台,并且建议您设置开机自启,以保证服务器重启后,Terminal也能自动运行

注意:在meson网络中,同一个IP被视为同1台机器,所以同个IP,同一台服务器上请不要运行多个Terminal程序,这样不仅不会提高您的收益,反而可能会被视为作弊行为
