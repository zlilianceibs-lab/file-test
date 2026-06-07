# Learn git

Git and Github lesson for a Monkey Bilibili links:
https://www.bilibili.com/video/BV1HM411377j?spm_id_from=333.788.videopod.sections

## 1. create a folder as the working directory

## 2. Setup git configration

```shell
git config --global user.name "xxxxx"
git config --global user.email "xxxx@xxx.com"


```

## 3. Initialize git repository of this working directory

```shell
git init

```

## 4. Common commands daily usage

```shell

1. check current directory status
git status

2. Add files from working to staged
git add .


3. commit from stage to commit area

git commit -m "create readme.md fileco"


4. check commit history

git log --oneline


5. goback history - previous version
git reset xxxxxxx

3 options for reset command
git reset --soft xxxxxx
git reset --hard xxxxxx
git reset --mixed xxxxx


6. reflog - check what you have done

git reflog

```

# How to connect with Github repository

1. login github
2. create a repository in github
3. connect with github repo and push

```shell
git remote add origin https://github.com/zlilianceibs-lab/file-test.git
git branch -M main
git push -u origin main
```
