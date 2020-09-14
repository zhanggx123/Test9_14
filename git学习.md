1. 安装git

2. 配置用户名跟邮箱
git config --global user.name  你的名字

git config --global user.email 你的邮箱

3. 初始化
git init 

4. 添加当前目录下的文件
git add filename 单个
git add -A       所有文件

5. 保存改动
git commit -m "log"

git log 

www.github.com

6. 克隆远程库(默认remote = orgin)
git clone 

7. 添加远程库
git remote add <short_name> <url>

8. 提交到远程库
git push <remote> <branch>

9. 从远程库获取最新版本
git fetch <remote>

10. 从远程库获取最新版本并确认
gti pull 