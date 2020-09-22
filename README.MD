### 简介
git是一个代码管理工具
同质化的软件svn
>linux linus
>git
>master 主线分支
>github 默认分支改为main

### git的基本使用
>初始化仓库、查看当前仓库的状态、暂存、提交
```bash
git init //仓库隐藏的.git文件夹
git status 、、文件状态系统
git add .
git commit -m '写日志'
#暂存和提交同时进行
git commit -am '日志信息'

```
#### 查看日志
```
git log
# 查看文件不同
git diff 版本id
git diff head^^ //和上上个版本对比

```
>head是当前版本 ^上一个版本 以此类推
#### 提交代码
>把代码推送到git服务器，push
>把代码从服务器签出，pull

```bash
# 本地仓库和服务器进行关联
//git remote add origin 地址
git remote add 服务器的名称 服务器的仓库url
# 如果第一次提交，需要关联服务器的分支
git push -u origin master
# 下载代码（签出、更新）
git pull
#查看服务器命令
git remote -v
```

#### 协同开发

#### 虚拟机
虚拟机：在某个操作系统中虚拟另一个操作系统的运行环境
服务器操作系统：centos（免费操作系统）
商业收费（redhat操作系统）
