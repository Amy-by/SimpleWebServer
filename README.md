# SimpleWebServer

## 项目概述
本项目展示了如何使用 Nginx 在本地机器上搭建一个基础的 Web 服务器。内容包括 Nginx 的安装与配置，以及托管一个静态 HTML 页面。

## 功能
- 本地 Nginx 服务器搭建
- 静态 HTML 页面托管

## 安装步骤
1. 在本地机器上安装 Nginx。
2. 配置服务器以托管 HTML 文件。
3. 在浏览器中访问 `http://localhost` 查看托管的页面。

## 使用方法
完成 Nginx 配置后，可以在本地运行服务器，并通过浏览器访问静态 HTML 页面。

## 项目目录结构
   在本地创建项目文件夹，建议的目录结构如下：
   ```
   SimpleWebServer/
   ├── public/
   │   └── index.html  (静态HTML页面)
   ├── nginx.conf     (Nginx服务器配置文件)
   ├── apache.conf    (如果选择使用Apache服务器)
   ├── README.md      (项目说明文档)
   └── LICENSE        (开源许可证，如MIT)
   ```
## 许可证
MIT 许可证
