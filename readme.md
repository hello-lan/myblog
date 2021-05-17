Hugo静态博客



#### hugo 版本

hugo v0.82.0-9D960784 linux/amd64 BuildDate=2021-03-21T17:28:04Z VendorInfo=gohugoio



#### 使用说明

**添加文章**

将markdown格式的文章放到`myblog/content/posts/`目录下，文章开头须满足一定的格式，具体参看该目录下已有的文章

**调试**

在`myblog/`目录下，执行hugo命令

```
$ hugo server
```

浏览器里打开： `http://localhost:1313`

**部署**

1. 生成静态页面

   ```
   $ hugo  --baseUrl="https://blue666.gitee.io/"
   ```

   执行顺利的话，会在，所有静态页面都会生成到`myblog/public`目录下

2. 发布页面

   将`myblog/public`目录下的所有文件push到github 或gitee上



github、gitee上部署静态页面方法参考：

[在github上部署静态网页](https://www.jianshu.com/p/b6dfc7c886a9)

[使用gitee免费部署静态网站](https://blog.csdn.net/zhangyu4863/article/details/80473412)