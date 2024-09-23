采用Hexo搭建个人博客，主题采用Butterfly

修改主题信息去themes/butterfly/_config.yml下修改

## 全局
``` bash
1. npm install hexo-cli -g
2. hexo init [name]  // 创建项目
3. npm install hexo-deployer-git --save  // 部署插件
```

## 运行
``` bash
1. npm install  // 安装依赖
2. hexo server  // 启动
```
## 部署 
``` bash
1. hexo clean  // 清除缓存
2. hexo g  // 生成静态文件
3. hexo d  // 部署

hexo clean && hexo d // 一键部署
```
### 常用命令
https://hexo.io/zh-cn/docs/commands