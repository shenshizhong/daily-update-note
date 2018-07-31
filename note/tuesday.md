# 今日主要活动

1、git 更新分支名称并上传
```

  1、重新命名：
> git branch -m oldName newName

  2、删除远程分支：
> it push origin :oldName

  3、上传：
> git push origin newName


如果碰到以下错误提示：
Your branch is based on 'origin/mymodule', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)
  
  4、使用以下命令，重新关联：
> git branch --set-upstream-to origin/newName

```

2、Animator 关系
```
Animator 抽象类  
   1、AnimatorSet 子类
   2、ValueAnimator 子类
       1、ObjectAnimator 子类
       2、TimeAnimator   子类

```
