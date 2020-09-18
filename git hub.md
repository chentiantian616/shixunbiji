# git hub





## 创建远程仓库步骤

### 创建远程仓库方法

- 1：账号密码
  - 创建仓库名称（不使用中文名称）
- 2：创建本地仓库
  - 方法：通过克隆到本地
  - 命令：git clone 把地址克隆到本地
- 查看：ls
- 把项目文件添加到本地文件
- 在命令窗口下进入  ：进入：cd 文件夹
- 查看状态：git status
- 提交本地仓库：git add .:把所有的文件提交到列队
- GIT commit -m'第一次提交'
- 同步远程仓库:git push

遇到账户权限问题：重设本地账号

- git config --global user.name'xxx'
- git config --global user.email'xxx@qq.com'