# 写一些零零散散的问题

* 在git push 的时候遇到的问题

```
在git push 的时候遇到的问题
git push
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/twototwoto/WWDesignPattern.git/'

解决办法：
git config user.name twototwoto
wangwang:WYWDesignPattern wangyongwangyongwang$ git push
Username for 'https://github.com': twototwoto
Password for 'https://twototwoto@github.com': 

确实是成功地提交了 不过还有个问题是github显示哪些天提交的色块没有变化
擦侧可能是因为在 git commit -m "" 的时候的用户名不对所致 确实在github上边看Commits的时候也发现了这个问题 接下来试着提交下

```
* 问题On branch master Your branch is up-to-date with 'origin/master'. Changes not staged for commit:

```
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
解决办法：git add 添加到暂存区


```

## 学习网址

[git commit 报 "Changes not staged for commit:"是怎么回事?](https://segmentfault.com/q/1010000004428943/a-1020000004451719)

