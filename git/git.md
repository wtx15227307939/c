##git配置
-- git config --global user.name xxx
-- git config --global user.email xxx
-- git config --list 检测
##命令
-- cd改变目录(change direction)
##清屏
-- clear
##创建文件
--mkdir
##初始化git
-- git init
##初始化文件
-- 
##查看状态
--git status
##将文件上传
--git add -A
--git add file单个文件
##提交
--git commit -m 可以在提交时写一些东西
--i 忘记写东西可以补一下 插入模式
i 表示编辑
退出esc + :wq
## 提交信息
--git log --oneline
## 比较代码差异
```
git diff 
```
##比较工作区和版本库的区别
```
git diff master
```
##比较暂存区和版本库的区别
```
git diff --cached
```