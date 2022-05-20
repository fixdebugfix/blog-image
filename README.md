# blog-image
save image for both typora and blog etc

按照这个配置的typora + picgo + github：https://zhuanlan.zhihu.com/p/489236769

> 注意：原本github的自定义域名应该是：https://raw.githubusercontent.com/[username]/[仓库名]

- 1.PicGo配置

要使用原来的github自定义域名，不要使用jsdelivr作为cdn加速，jsdelivr网上说不支持图床了，即使用下面的配置

![image](https://user-images.githubusercontent.com/105898532/169507338-332344f4-297a-4bfe-a9a0-18aa75e81bbf.png)

- 2.Typora配置

偏好设置里使用如下配置，这样onedrive里会有一份图片，github里会同步有一份图片

![image](https://user-images.githubusercontent.com/105898532/169624272-200b3c97-cb99-4522-8645-86ca94466dee.png)

> 注意:里面的相对路径不是必选的，建议选上，这样的好处就是本地写文档不会因为github访问慢导致图片加载失败

![image](https://user-images.githubusercontent.com/105898532/169625033-472e8c00-dddf-456a-9b01-3e16dfe8ad64.png)


- 3.Typora操作（如果写博客）

typora写的md文件，上传到博客上最头疼的就是图片不显示了，上面Typora设置的图片是相对路径，需要改成url

我习惯的操作：

- 1.coype一个new.md（专门用来上传博客用）

- 2.将new.md的所有图片上传

![image](https://user-images.githubusercontent.com/105898532/169624154-61f09616-a0c7-4a34-ab2e-e81b0ef684f6.png)

- 3.将new.md导入想要得博客中，图片直接显示，再也不用一个个上传了

![image](https://user-images.githubusercontent.com/105898532/169625063-018fe8af-1b36-4c96-bc64-7c23d96b1014.png)



