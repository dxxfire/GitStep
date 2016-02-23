# 创建Repositories
## 通过GitHub创建
    在GitHub上创建Repositories之后，git clone的方式下载到本地
## 本地创建后上传
- 在本地项目下git init，Git会建立一个名为.git的隐藏文件夹作为本地代码库。
- 然后加载项目文件到本地代码库中:
  - git add . ".'符号的意思是"所有文件、文件夹和子文件夹"
  - git add *_file, *_other_file 把特定文件添加到代码库中
- 提交已加载（staged）的文件 git commit -m "注释"
- 检查当前已加载（staged）和未加载（unstaged）文件的状态、提交等情况：git status
- 推送到远程代码库 git remote add origin https://your_username@bitbucket.org/your_username/name_of_remote_repository.git

## 分支
> 准备创建分支
