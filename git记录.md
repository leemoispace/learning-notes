# GIT学习使用记录

把印象笔记的“git 学习记录”重新整理一遍到md格式。

## 1. 建立git



本地电脑与github账户连接：todo

在网上建立repository，然后用HTTPS clone到本地

```
git clone https://github.com/xxxxx/learning-notes.git
```

就建立了联系。

## 2.使用git

终端cd到代码根目录初始化：

```
git init
```

# Gitbook使用

* Gitbook绑定：在gitbook开新书可以与github的repository 绑定。

* 同步到本地：/Dropbox/learning-notes

  * ```
    git fetch
    git checkout
    git pull
    ```

本地编辑后推送：

```
git commit
git push
```

当前问题：gitbook editor自动生成的文件名是拼音中文，还是自己建文件夹再加链接来组织比较好。

# 参考资料

<https://www.codeschool.com/paths/git>