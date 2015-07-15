title: 如何 加入大厨网hexo 文章贡献
date: 2015-07-15 18:13:47
tags: hexo
---

## 记住：每次拉取最新的代码, 写文章的时候新建一个分支

### 如何 加入大厨网hexo 文章贡献

``` bash
第一步,拉取博客主分支:
      https://github.com/lisiyizu/dachu-fe.git
``` 

``` bash
第二步,进入到 /dachu-fe/www 目录,执行一下命令: 
      npm install
``` 

``` bash
第三步,安装hexo-deployer-git :
      npm install hexo-deployer-git --save
``` 

``` bash
第四步,启动
      hexo server
``` 

``` bash
第五步,写博客文章,敲一下命令:
      hexo new post my-first-post
``` 

``` bash
第六步: 提交发布到线上部署环境,执行这个命令会生产一个public静态资源的打包文件夹:
      hexo deploy
```       
