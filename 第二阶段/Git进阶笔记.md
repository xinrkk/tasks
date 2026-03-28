# Git进阶笔记
> ——康思晟
***
## 💾 一、常用查看命令

- git log --graph --oneline --decorate --all

- git blame 文件名

- git diff

- git diff --cached
***
## 🧹 二·、忽略文件
> *.log
> *.tmp
> node_modules/
> __pycache__/
> .DS_Store
***

## 🧭 三、帮助命令
- 查看 Git 帮助
git help  

- 查看某命令帮助
git help commit
git help push
git help branch
***
## 🚀 四、Git 常见工作流程（典型流程）
1. 初始化仓库
git init

2. 添加远程仓库
git remote add origin https://github.com/用户名/仓库名.git

3. 添加文件
git add .

4. 提交修改
git commit -m "首次提交"

5. 推送到远程仓库
git push -u origin main

6. 拉取最新更新
git pull origin main