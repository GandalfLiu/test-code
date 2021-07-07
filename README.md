# git大全

```
git clone https://github.com/test/test-proj test-proj
git add test.txt
git commit -m "[add]新增功能"
git rm -f 删除
git remote add origin https://github.com/test/test-proj
git remote rm origin
git fetch origin dev
git branch  # 显示所有的branch
git branch newBranchName  # 新建branch
git checkout master        # 切换到master分支
git status -s           # 简短的显示当前
git diff                # 查看当前工作区和缓存区的不同
git diff --stat         # 查看工作区和缓存区的总览
git diff --cached   # 查看已缓存的改动
git diff HEAD        #  查看已经缓存区和HEAD仓库的区别

```

[git命令大全](https://juejin.cn/post/6844903598522908686)
```
git clone https://github.com/test/test-proj test-proj
git add test.txt
git commit -m "[add]新增功能"
git rm -f 删除
git remote add origin https://github.com/test/test-proj
git remote rm origin
git fetch origin dev
git branch  # 显示所有的branch
git branch newBranchName  # 新建branch
git checkout master        # 切换到master分支
git status -s           # 简短的显示当前
git diff                # 查看当前工作区和缓存区的不同
git diff --stat         # 查看工作区和缓存区的总览
git diff --cached   # 查看已缓存的改动
git diff HEAD        #  查看已经缓存区和HEAD仓库的区别
git restore file    # 将当前工作区域的file文件恢复至缓存区的状态
```

# crontab命令
[crontab在线生成网站](https://atool.vip/crontab/)
```
{minite} {hour} {day-of-month} {month} {day-of-week} {full-path-to-shell-script}

minite: 0-59
hour: 0-23
day-of-month: 0-31
month: 1-12
day-of-week: 0-7

# 例如
1. 每隔1min执行一次
*/1 * * * *

2.每个月的10号到15号每隔2天之间, 的12点至15点每隔2h, 
30/20 12-15/2 10-15/2 * *



3. 表示每隔45min执行
*/45 * * * *

```
