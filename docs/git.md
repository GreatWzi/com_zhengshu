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