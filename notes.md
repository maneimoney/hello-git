# Git 速查表

## 日常三步
1. git add .            把改动放进暂存区
2. git commit -m "说明" 存成本地快照
3. git push             推送到 GitHub

## 观察类
- git status    看现在什么状态
- git log --oneline  看提交历史
- git diff      看具体改了哪几行

## 第一次才用的
- git clone git@github.com:用户名/仓库.git
- git remote add origin git@github.com:用户名/仓库.git
- git push -u origin main
