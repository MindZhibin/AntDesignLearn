# AntDesignLearn
AntDesign,个人学习
###命令行指令

####Git 全局设置
```shell
git config --global user.name "你的名字"
git config --global user.email "email"
```

#### 创建新版本库

```shell
git clone git@github.com:MindZhibin/AntDesignLearn.git.git
cd funxinmobi
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```

#### 已存在的文件夹

```shell
cd existing_folder
git init
git remote add origin git@github.com:MindZhibin/AntDesignLearn.git.git
git add .
git commit -m "Initial commit"
git push -u origin master

```

#### 已存在的 Git 版本库

```shell
cd existing_repo
git remote rename origin old-origin
git remote add origin git@github.com:MindZhibin/AntDesignLearn.git.git
git push -u origin --all
git push -u origin --tags
```
