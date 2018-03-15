
## 使用 hexo 搭建的个人博客 
域名 http://zuoguoqing.com 已解析至该项目。

### 主题
next 
 
### Github hexo项目添加README
默认情况下，在source目录添加README.md后，hexo g后，会将README.md生成README.html，影响显示，可以在"\_config.yml" 里面设置不渲染README.md就可以了。
``` js
skip render:
- README.md
```

