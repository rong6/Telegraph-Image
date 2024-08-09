<h1 align="center">Telegraph-Image</h1>
<p align="center">一个基于Vercel或Nginx搭建的Telegraph图床。</p>
<hr>

## 这是什么？
[Telegraph](https://telegra.ph)是一个内容发布工具，其中可以上传图片，因此可以拿来“白嫖”用作图床，本项目就是为此而生，有Vercel、Nginx两种搭建方式，你也可以尝试前辈基于CloudFlare Pages的[cf-pages/Telegraph-Image](https://github.com/cf-pages/Telegraph-Image)项目。

## 部署
### Vercel
Vercel的优点是几乎0成本部署，缺点是每个月只有100G流量。   
- 方式一：Fork本仓库，然后在Vercel新建项目，选择Fork后的仓库即可。   
- 方式二：直接点击该按钮部署：[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/rong6/Telegraph-Image&project-name=Telegraph-Image&repository-name=Telegraph-Image)   
> 由于Vercel分配的域名已被墙，部署后记得绑定自己的域名。   

### Nginx
Nginx的有点是灵活、可控性高，缺点是必须需要一台服务器。   
请确保服务器以安装Nginx，然后将[nginx.conf](https://github.com/rong6/Telegraph-Image/blob/main/nginx.conf)的配置粘贴至配置文件即可。