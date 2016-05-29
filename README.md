##哈哈使用$ git push -u origin gh-pages -f
强制将低版本转换成高版本
当提交的时候遇到以下情况的时候:
```
$  git push --set-upstream origin gh-pages
To git@github.com:lyj505/try2try.git
 ! [rejected]        gh-pages -> gh-pages (non-fast-forward)
error: failed to push some refs to 'git@github.com:lyj505/try2try.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```

##git push -u origin（远程）master(某一个分支) -f

## 这样就ok了
