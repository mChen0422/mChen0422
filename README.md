

# 头像、姓名、自我介绍修改方法
修改配置文件：_config.yml（该配置文件为整个主页的主要配置文件：可修改以下复制的内容，其他配置项目不需要修改，保持默认就可以）
```
title: Background。 # 标题名称：对应头像下方那块
author: NAME # 姓名
url: https://mChen0422.github.io # 主页地址
avatar: "/assets/images/index/avatar.jpg" # 头像图片的路径，替换的话直接上传到这个路径下，然后改下名称就可以
top_title: > # 自我简介：</br>这个为换行符号
    Personal introduction </br>
    Personal introduction </br>
description: > # 详细的自我描述，同样可以添加换行符号
    description </br></br>
    description
```

# 项目文章等配置
主页上的其他配置均在 **/_data/home.yml** 中配置

# 点击进入查看详情的实现配置（例如点击项目，进入详情页）
在 /_posts/ 目录下创建md格式的文件
文件名称格式为：yyyy-mm-dd-filename.md
内容固定格式，layout固定写法，author作者，tags标签。然后在下面写文章内容即可。文章内容实用markdown语法
```
---
layout: post
author: author
tags: [tag1, tag2]
---
content
```

最后写完这篇文章保存后，文章的地址就为/filename，然后填写在/_data/home.yml的响应配置地方。

# 文章中插入图片的方法
标准的markdown语法格式 
小括号里的为图片路径，你插入图片的时候，先上传到相应的文件夹下，然后再写上相应的路径。路径也可以写网上的图片链接例如：`http://google.com/img/school.png`这种
`![](/assets/images/project/p02/img.png)`

ok，以上差不多了








