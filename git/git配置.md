

### 创建版本库
### 时光穿梭——回退、撤销、删除
### 远程仓库
### 分支管理—— 创建合并分支、解决冲突
### 标签管理


### git别名配置
git config --global color.ui true
1. 常用别名设置
```
git config --global alias.st "st"
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.br branch
```
2. git日志别名配置
```
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
```