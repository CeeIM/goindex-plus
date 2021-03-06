![GoIndex](https://raw.githubusercontent.com/ceecx/goindex-plus/master/themes/logo.png)  

GoIndex Plus
====  

基于 [原版](https://github.com/donwa/goindex) 和 [yanzai/goindex](https://github.com/yanzai/goindex) 修改而来，为自己所需做了调整。

复制 `index.js` 代码到 Cloudflare Workers 并修改自己的信息进行部署。

## 预览

Demo: https://dl.cee.workers.dev/


## 更新日志

### 1.0.1 (2020-07-08)

- 修改所有静态文件为 jsDelivr CDN 加快国内访问速度。
- 修改默认主题颜色为白色。
  

---



> **安装部署可以参考原版，以下摘自原版 GoIndex 的部署说明：**



## Demo  
material: [https://index.gd.workers.dev/](https://index.gd.workers.dev/)  
classic: [https://indexc.gd.workers.dev/](https://indexc.gd.workers.dev/)  

## Deployment  
1.Install `rclone` software locally  
2.Follow [https://rclone.org/drive/]( https://rclone.org/drive/) bind a drive  
3.Execute the command`rclone config file` to find the file `rclone.conf` path  
4.Open `rclone.conf`,find the configuration `root_folder_id` and `refresh_token`  
5.Download index.js in https://github.com/donwa/goindex and fill in root and refresh_token  
6.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)

## Quick Deployment  
1.Open https://installen.gd.workers.dev/  
2.Auth and get the code  
3.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)  



## About  
Cloudflare Workers allow you to write JavaScript which runs on all of Cloudflare's 150+ global data centers.  
