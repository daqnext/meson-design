# CDN User and Miner Guide

* [CDN User and Miner Guide](#cdn-user-and-miner-guide)
  * [3 steps to start using CDN acceleration service](#3-steps-to-start-using-cdn-acceleration-service)
    * [Step1\. Register an account and log in](#step1-register-an-account-and-log-in)
    * [Step2\. Create resource acceleration link](#step2-create-resource-acceleration-link)
    * [Step3\. Replace the original static resource link in the webpage with an accelerated link](#step3-replace-the-original-static-resource-link-in-the-webpage-with-an-accelerated-link)
  * [Miner mining guide](#miner-mining-guide)
    * [Step1\. Register an account and log in](#step1-register-an-account-and-log-in-1)
    * [Step2\. Download and run the Terminal client](#step2-download-and-run-the-terminal-client)
    * [Step3\. Check the server status](#step3-check-the-server-status)
    * [Step4\. Keep terminal running in the background](#step4-keep-terminal-running-in-the-background)

## 3 steps to start using CDN acceleration service

### Step1. Register an account and log in

Enter official website  <https://meson.network>

Register as a cdn user

![avatar](./img/reg1.png)

Check the cdn user

![avatar](./img/reg2.png)

### Step2. Create resource acceleration link

Enter the `Client => BindDomain` page,

![avatar](./img/bind1.png)

Create resource acceleration link

![avatar](./img/bind2.png)

Fill in the link of your website's static resources in the red box.

For example, if you want to accelerate all the image resources in your website, which are stored in the root directory of `website/static/img` directory, you can fill in here. e.g. www.yourdomain.com/static/img

Click `Check Input Url`

If the verification is correct, the button will turn green, click `Add Record`

![avatar](./img/bind3.png)

The acceleration link you created will be displayed below

![avatar](./img/bind4.png)

### Step3. Replace the original static resource link in the webpage with an accelerated link

Replace resource link

![avatar](./img/use1.png)

Replace the resource link you need to accelerate with the link you generated in the previous step, as shown in the figure above, replace the content in the red box with the new link.

If your webpage supports https, please use https://, if not, please use http://

------------

## Miner mining guide

You only need a server with a public IP to become a miner and earn your income

### Step1. Register an account and log in

Enter official website  <https://meson.network>

Register as a `terminal` user

![avatar](./img/reg1.png)

Check `terminal` user

![avatar](./img/reg3.png)

### Step2. Download and run the Terminal client

Enter the `Terminal=>Terminals` page,

![avatar](./img/terminal1.png)

ssh to your server, select the client corresponding to your operating system, download, unzip and run

![avatar](./img/terminal2.png)

When running for the first time, the program will prompt you:

`token` -- User identifier, you can find from  website

`spaceLimit` -- Hard disk space provided for service, at least 80G. The greater the storage space provided, the higher your profit will be

`port` -- External service port, please do not use port 80 or 443, and ensure that your firewall will not block this port

After the configuration, the terminal will run normally

### Step3. Check the server status

Usually in a few minutes, you can see that your server is online and running at the bottom of the web page
![avatar](./img/terminal3.png)

If the server's `Status` is `ON`, it means your server has been running normally and has been included in our accelerated network

### Step4. Keep terminal running in the background

Let the Terminal program run in the background, and recommend to set up a boot-up


Note: 
In the meson network, the same IP is regarded as the same machine, so please do not run multiple Terminal programs on the same IP and the same server. This will not increase your income, and may be regarded as Cheating
