---
title: 初步学习部署博客
published: 2024-08-05
description: '将基于 Astro 开发的博客部署到 Netlify'
image: ''
tags: [Markdown, Althea, Study]
category: 'Study'
draft: false 
---
## 部署步骤

### 1. 创建 GitHub 仓库

首先，我们需要创建一个 GitHub 仓库，并将博客源码上传到仓库中。

![创建 GitHub 仓库](../Images/deploy_01.png)

### 2. 通过 GitHub 登录 netlify 账号

接着，我们直接通过 GitHub 登录 [netlify](https://www.netlify.com/) 账号。

![登录 netlify 账号](../Images/deploy_02.png)

### 3. 导入 GitHub 仓库

按照步骤，先导入自己的 GitHub 仓库，然后选择需要部署的仓库，

![导入 GitHub 仓库 01](../Images/deploy_03.png)

![导入 GitHub 仓库 02](../Images/deploy_04.png)

![选择需要部署的仓库](../Images/deploy_05.png)

### 4. 配置部署环境

然后，我们需要配置部署环境。

![配置站点和部署](../Images/deploy_06.png)

### 5. 部署成功

最后，我们点击最下方的部署按钮，等待一小段时间，即可部署成功。

![部署成功](../Images/deploy_07.png)

### 6. 访问博客

部署成功后，我们可以直接通过刚刚设置的属于自己的 [Netlify](https://blog-althea.netlify.app/) 域名访问博客啦！

![通过域名访问博客](../Images/deploy_08.png)

## 参考资料

> Astro 官方部署文档：[https://docs.astro.build/zh-cn/guides/deploy/](https://docs.astro.build/zh-cn/guides/deploy/)