---
title: Hello World
date: 2023-10-20T13:24:02.918Z
---

# hugo-decap-cms-vercel-stack



这个是安装了stack主题的博客

Use this template  开箱即可用




在Vercel上部署带有decap-cms的hugo博客。

✔完全免费

✔静态网页，无渲染时间

✔在线编辑，就像使用动态CMS一样简单，由decap-cms（原Netlify-CMS）支持

✔无需本地环境，您可以在任何设备上随时随地编辑页面

✔零编码

✔Vercel CDN使您的页面可以从世界任何地方快速加载，包括中国大陆

✔易于绑定到您的域，并启用SSL加密，由Vercel支持

其他改进
定制 404 页面
用法
克隆到你的hugo博客根目录  注意后面有个. 

git clone https://github.com/Serbia580/hugo-decap-cms-vercel.git

将hugo-decap-cms-vercel文件里面的文件复制或者剪切到博客的根目录  （ 删除里面的.git） 最后删除hugo-decap-cms-vercel文件夹

将static/admin/config.yml里面的repo和base_url修改成你的

转到 Github 开发人员应用程序并创建新的 oauth 应用。https://github.com/settings/developers

唯一重要的字段是 ，input ，其中是步骤 2 中的域，另请注意 HTTPS 是必需的。然后生成新的客户端密码。Authorization callback URLhttps://<domain>/callback<domain>

转到 Vercel 导入您的存储库并创建一个新项目。在单击按钮之前，添加环境变量OAUTH_GITHUB_CLIENT_ID和OAUTH_GITHUB_CLIENT_SECRET，并设置上一步中生成的值。Deploy

单击按钮并等待部署完成。Deploy

也许您需要在“设置”>“域”中更改Vercel提供的域。

打开 https://<domain>/admin/并登录到decap-cms后端。 （admin后面一定要/  否则会出现404错误）

测试decap-cms是否正常工作。


祝贺！您已经在Vercel上成功部署了decap-cms的Hugo博客。


下面是自己diy版，没有安装主题和原文件 

https://github.com/Serbia580/hugo-decap-cms-vercel


# 感谢

Netlify CMS的oauth网关由[ublabs/netlify-cms-oauth](https://github.com/ublabs/netlify-cms-oauth). 实现

参考
https://github.com/hangvane/hexo-netlify-cms-vercel

