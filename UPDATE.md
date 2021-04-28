### 本项目fork自 [yeszao/dnmp](https://github.com/yeszao/dnmp)  

**以下是同步更新上游的更改操作**
> master只做同步上游操作,最终合并到main分支

1. 切换到master分支
```shell
git checkout master
```

2. 添加上游仓库地址

```shell
git remote add upstream https://github.com/yeszao/dnmp.git
```

3. 获取上游更新
```shell
git fetch upstream
```

4. 合并上游的更新到本项目master分支
```shell
git merge upstream/master --allow-unrelated-histories
```

5. 提交变更
```shell
git push
```

6. 合并到main分支
```shell
git checkout main  
git merge master  
git push  
```
