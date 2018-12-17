# formatCommander





一键完成OC工程的格式化。

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/DingYusong/formatCommander/master/format.sh)"
```

或者：

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/DingYusong/formatCommander/master/format_http.sh)"
```



1. 进入项目目录。
2. 执行上述脚本自动添加git-hook提交检验，便于团队项目风格管理。



下载推荐的格式文件

```bash
curl -o .clang-format https://raw.githubusercontent.com/DingYusong/formatCommander/master/.clang-format
```



.gitignore 缓存清理

```
git rm -r --cached .
git add .
git commit -m 'update .gitignore'
```





参考文档：

https://github.com/wangwanjie/ClangFormaterObjC

https://github.com/square/spacecommander