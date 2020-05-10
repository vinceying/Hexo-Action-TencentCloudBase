# Hexo-Action-TencentCloudBase

通过 Github Actions，使用 Hexo-Action-TencentCloudBase 可以将 Hexo 的源文件部署并推送到 Tencent CloudBase 的静态托管中。

## 🚀 使用

由于 Github Pages 在国内的访问速度，可以使用 [Tencent CloudBase](https://cloud.tencent.com/product/tcb?from=12334) 来托管相关静态网页。Hexo-Action-TencentCloudBase 可以通过 Github Actions 将 Hexo 的源文件推送到Tencent CloudBase 的静态托管中。

在仓库中添加 `Repo/.github/workflows/tencent.yml` ，相关文件即可。更多关于 Github Actions ，[请点击这里查看](https://help.github.com/en/actions)。

## 🔐 腾讯云相关输入内容

在项目的 'secret' 添加 'ENV_ID' 'SECRET_ID' 'SECRET_KEY' 相关字段。

SECRET_ID # Required 云开发的访问密钥 secretId
SECRET_KEY # Required 云开发的访问密钥 secretKey
ENV_ID # Required 云开发的环境 id envId

## ✔ 使用内容及灵感来源

[实例](https://i.vince.pub)  
[cloudbase-action](https://github.com/TencentCloudBase/cloudbase-action)  
[action-hexo](https://github.com/heowc/action-hexo/issues/3)