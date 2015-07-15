title: Hello Hexo 
tag: hexo
---
Welcome to [Hexo](http://hexo.io/)! This is your very first post. Check [documentation](http://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](http://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## 快速入门

### Hexo 安装

``` bash
$ npm install hexo-cli -g
$ hexo init blog
$ cd blog
$ npm install
$ hexo server
```

### Hexo Git 配置

``` bash
第一步：
        安装 npm install hexo-deployer-git --save
第二步：
       vi _config.yml
-------------------------------------------------
# Deployment
## Docs: http://hexo.io/docs/deployment.html
deploy:
  type: git
  repo: https://github.com/xxxxxx/xxxxxxxxx.git
 
```

### 创建新的文件

``` bash
$ hexo new "My New Post"
```

More info: [Writing](http://hexo.io/docs/writing.html)

### 启动服务

``` bash
$ hexo server
```

More info: [Server](http://hexo.io/docs/server.html)

### 将MD 生成静态资源,放在 public 文件夹内

``` bash
$ hexo generate
```

More info: [Generating](http://hexo.io/docs/generating.html)

### 部署发布网站

``` bash
$ hexo deploy
```

More info: [Deployment](http://hexo.io/docs/deployment.html)
