##版本控制
版本控制是记录文件随时间的改变，方便以后能重新定位到之前的记录中
> 添加文件到git仓库

* git add <file>向库里添加文件，git add . 是向库里添加当前目录下所有文件
* git commit命令，-m后面提交的是说明

> 掌握仓库的状态

* git status 让我们掌握仓库当前的状态
* git diff 帮助我们查看具体的改变

> 版本回退

* git log 查看从远到近的提交日志
* git reset --hard HEAD^ 回退到上一个版本， head^ 回到上一个版本，head^^ 回到上上个版本，以此类推，也可以用 head~100表示
* git reset --hard [id]回到 commit id 的那个版本
* git reflog 记录每一次命令 可以查看到commit id值