---
title: Hello World
date: 2022-01-12T13:24:02.918Z
---

# huoo-decap-cms-vercel



克隆到你的hugo博客根目录
git clone https://github.com/Serbia580/huoo-decap-cms-vercel.git








hexo-netlify-cms-vercel
在Vercel上部署带有Netlify-CMS的Hexo博客。

✔完全免费

✔静态网页，无渲染时间

✔在线编辑，就像使用动态CMS一样简单，由Netlify-CMS支持

✔无需本地环境，您可以在任何设备上随时随地编辑页面

✔零编码

✔Netlify-CMS和Netlify支持预览

✔Vercel CDN使您的页面可以从世界任何地方快速加载，包括中国大陆

✔易于绑定到您的域，并启用SSL加密，由Vercel支持

其他改进
定制 404 页面
用法
单击以分叉此存储库。它可以是私有的。Use this template

修改。将 和 的值更改为您的值。/source/admin/config.ymlbackend.repobackend.base_url

转到 Github 开发人员应用程序并创建新的 oauth 应用。https://github.com/settings/developers

唯一重要的字段是 ，input ，其中是步骤 2 中的域，另请注意 HTTPS 是必需的。然后生成新的客户端密码。Authorization callback URLhttps://<domain>/callback<domain>

转到 Vercel 导入您的存储库并创建一个新项目。在单击按钮之前，添加环境变量OAUTH_GITHUB_CLIENT_ID和OAUTH_GITHUB_CLIENT_SECRET，并设置上一步中生成的值。Deploy

单击按钮并等待部署完成。Deploy

也许您需要在“设置”>“域”中更改Vercel提供的域。

打开 https://<domain>/admin/并登录到Netlify-CMS后端。

测试Netlify-CMS是否正常工作。

如果您需要Netlify-CMS提供的预览功能，即在点击按钮后在文章撰写页面上为您提供预览链接，则还需要将您的博客存储库链接到Netlify。这类似于链接到Vercel，但您不需要添加环境变量，因为您不在Netlify提供的域上使用Netlify-CMS。save

祝贺！您已经在Vercel上成功部署了Netlify-CMS的Hexo博客。


# 感谢

Netlify CMS的oauth网关由[ublabs/netlify-cms-oauth](https://github.com/ublabs/netlify-cms-oauth). 实现

参考
https://github.com/hangvane/hexo-netlify-cms-vercel


2022年12月1号更新
网页翻译成中文
加入了几个比较热门的hexo主题
butterfly，fluid，matery，next

可以在 _config.yml 文件切换主题

插件安装或者升级，可以在package.json文件里面修改 举例

butterfly主题需要安装的插件

"hexo-renderer-pug": "^3.0.0",

"hexo-renderer-stylus": "^2.1.0",

文章加密的插件
"hexo-blog-encrypt": "^3.1.6",

本地搜索插件
"hexo-generator-search": "^2.4.3",

固定链接插件
"hexo-abbrlink": "2.2.1",

如果需要升级，可以在搜索插件名称，看下最新的版本是哪个，直接就可以修改了。

