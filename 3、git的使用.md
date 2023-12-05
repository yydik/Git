### 1. 什么是版本库?

版本库（Repository），又称为仓库（Repo），是Git用来存储项目的地方。可以将版本库理解为一个目录，目录中的所有文件都可以被Git管理。每个文件的增删改查都可以被Git跟踪，因此可以随时返回到之前的任何版本。

### 2. Git创建仓库

Git提供两种创建仓库的方式：

#### 2.1 使用 `git init`

要创建一个新的仓库，首先在本地文件系统中创建一个新目录，然后运行以下命令：

```bash
$ mkdir my_project
$ cd my_project
$ git init
```
#### 2.2 使用 `git clone`
```bash
git clone https://github.com/example/repo.git
```