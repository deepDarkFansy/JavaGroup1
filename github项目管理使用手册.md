### 0  SSH免密登录设置（略过）

参考这篇博客：<https://blog.csdn.net/u013778905/article/details/83501204>

### 1  克隆一个项目副本到本地

git clone git@github.com:YourGithubID/firstProject  ## deepDarkFansy/firstProject 为你所创建的项目

### 2  创建文件并上传到github上

cd firstProject    ##  进入克隆的项目中
echo "This is a file to upload to the github" >> readme.md   ##  新建文本文件
git add readme.md  ##  将其上传到本地仓库中
git commit -m "first unload"  ##  加上备注
git push origin master  ##  开始上传

### 3 查看git的部分配置信息命令

git branch    ##　查看分支

git remote -v　　##　查看各种上传(push)下载(fetch)流

git status 　## 　查看目前git 状态

git remote add upstream git@github.com:YourForkedGithubID/firstProject　##　添加上传下载流

git fetch upstream　　## 　从upsteam 下载项目

git merge upstream/master  　##  合并下载的项目与本地的项目

### 4 推荐参考网站

<https://github.com/deepDarkFansy/Leetcode-solution-for-us>

可以在该网站上查询上传本地项目到主项目的以及项目负责人审批提交的全过程