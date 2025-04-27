## 部署到cloudflare pages

流程如下：
- Fork本项目(导入也可)
- cloudflare中新建一个pages
- 连接GitHub
- 选择刚刚fork的项目
- 构建命令填 <u>npm run build</u>
- 构建输出填 <u>public</u>
- 根目录留空
- 其他留空，点击部署
- 部署完成后等待一小会，访问cf分配的域名尝试是否正常预览，可以预览后再绑定自己的自定义域名

## 设置博客

- `_config.yml`文件：设置博客的基本信息，如网站名称、作者等
- `_config.anzhiyu.yml`文件：主题配置文件，参照[安知鱼主题官方文档](https://docs.anheyu.com/global/base.html)进行配置

## 如何发布博文
 
- 你可以直接在`source\_posts`：博客文章文件夹，在仓库里写`md`文档，提交即可发布到博客
- 但是我个人更推荐使用[Qexo](https://github.com/Qexo/Qexo)这个项目来给你的博客添加一个后台功能，同时也更加方便写作与编辑
