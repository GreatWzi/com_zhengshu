## 简介
这是一个用于个人开发的库。

## 目录介绍
- **com_zhengshu**
  - do  *处理脚本*
    - cameraConfigs *相机配置*
    - doout *导出脚本*
  - docs *文档*
    - doin.md *导入说明文档*
    - request.py *网络请求脚本*
  - src
    - mysdk_com *sdk源码*
  - navigation.md *各类学习文档*
  - requrement.txt *依赖包*
  - setup.py *安装脚本*

## 安装
使用 pip 安装：
pip install git+https://github.com/GreatWzi/mysdk-com.git

更新：
pip install --upgrade git+https://github.com/GreatWzi/mysdk-com.git

使用 SSH 方式进行克隆
pip install --upgrade git+ssh://git@github.com/GreatWzi/mysdk-com.git

## git使用
添加当前文件夹中的所有更改到 Git
git add .

将更改提交到本地 Git 仓库。
git commit -m "提交信息"

连接到 GitHub 仓库
git remote add origin https://github.com/yourusername/mysdk-com.git

把本地的 main 分支推送到 GitHub 的 origin 远程仓库。
git push -u origin main

生成 SSH 密钥
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

将远程仓库地址更改为 SSH 格式：
git remote set-url origin git@github.com:GreatWzi/mysdk-com.git

git config --global https.proxy http://192.168.34.247:30002
git config list --global

# Markdown
- 可视化模式
    - ctrl + k v