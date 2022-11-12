# TG-image

原项目：https://github.com/cf-pages/Telegraph-Image

因添加了`wp.com`高速节点，防止滥用，没有fork







不能手动上传，必须fork
1.github  fork此项目，打开Cloudflare，进入Pages管理页面，选择创建项目，链接到git，选择fork项目，一直下一步最后部署站点，这就可以了。

2.可以使用CF提供的xxx.pages.dev的免费二级域名直接访问，打开xxx.pages.dev就可以上传文件了，访问链接已经自动替换为国内高速访问链接，无需科学SW。


缺点：
1. xxx.pages.dev部分地区无法访问，如果有自己的域名可以在Cloudflare Pages的自定义域里面绑定,提供个免费申请顶级域名的教程  
2. 文件大小5M以内，对于图片够用的，视频可能就不够用了
3. 无法图片管理，上传了就无法删除
