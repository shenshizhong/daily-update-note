# 今日主要活动

1、RecycleView中使用动画

今天碰到的是在ReclclerView 中使用点击按钮收藏的功能，但是呢，动画没有生效，误以为是RecyclerView
导致的，后来打日志跟踪，发现是自己自定义的动画有问题。

小结：缩小问题的范围，才能看到本质，避免查找方向不对问题。

2、解决RecyclerView 刷新单行闪一下问题

方案一：
((SimpleItemAnimator)recyclerView.getItemAnimator()).setSupportsChangeAnimations(false);
设置禁止动画

方案二：
recyclerView.getItemAnimator().setChangeDuration(0)；
设置动画的执行是时间为o

3、在开发的时候，由于测试不方便，然后就直接进行打包测试。即便检查了几遍，还是有问题。

小结：思考全面，如果业务原因不好测试，先打日志，跟踪代码走的流程，避免该走的流程没走，导致出问题。


