# git 第远程操作指令

1. 克隆远程仓库 `git clone <repository-url>`
   + 例如 `git clone https://github.com/user/repo.git`
2. 查看远程仓库 `git remote -v`
3. 添加远程仓库 `git remote <name> <url>`
4. 删除远程仓库 `git remote rm <name>`
5. 重命名远程仓库 `git remote rename <old-name> <new-name>`
6. 获取更新并且合并 `git pull <remote> <branch>`
7. 推送 `git push -u <name> <branch>`
8. 查看远程仓库分支 `git branch -r`
9. 创建一个本地分支来跟踪远程分支 `git checkout -b <local-branch> <remote>/<remote-branch>`
    + 例如 `git checkout -b feature origin/feature`
10. 删除远程分支 `git push <remote> --delete <branch>`
   
