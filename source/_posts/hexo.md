---
title: hexo + indigo主题搭建  
date: 2022-02-15 14:15:07  
tags:
excerpt: 纯手动hexo + indigo主题博客搭建，基于现有项目，避免命令报错文件夹非空
---

1. 下载hexo starter模板，放到自己想放的目录，以后在此模板基础上配置编写 `https://github.com/hexojs/hexo-starter`  
2. 下载主题到themes/indigo下面 `https://github.com/yscoder/hexo-theme-indigo`  
3. hexo 版本改为4.0.0。(主题不兼容高版本)  
4. 删除 `_config.landscape.yml`  
5. 删除依赖 `"hexo-theme-landscape": "^0.0.3"`(不然运行有报错)  
6. 删除全局hexo(与本地版本不一致打包为空)  
7. 主题全局搜索`href="javascript:;"`, 全部删掉