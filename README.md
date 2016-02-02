
# DynamicLoading
Android Dynamic loading(Android动态加载技术汇总)

1. [各大热补丁方案分析和比较](http://blog.zhaiyifan.cn/2015/11/20/HotPatchCompare/)：最近开源界涌现了很多热补丁项目，但从方案上来说，主要包括 Dexposed、AndFix和ClassLoader三种。前两个都是阿里巴巴内部的不同团队开发的（淘宝和支付宝），后者则来自腾讯的QQ空间团队。虽然都是热更新技术，但这三种方案的原理徊然不同，本文详细分析这三种热补丁方案的实现原理及各自的优缺点。

2. [Android动态加载黑科技 动态创建Activity模式](http://segmentfault.com/a/1190000004077469?utm_source=Weibo)：

3. [美团Android DEX自动拆包及动态加载简介](http://tech.meituan.com/mt-android-auto-split-dex.html?utm_source=www.race604.com)：

4. [Android平台免Root无侵入AOP框架Dexposed使用详解](http://www.jianshu.com/p/14edcb444c51)：

5. [基于cydia Hook在线热修复补丁方案](http://blog.csdn.net/xwl198937/article/details/49801975)：

7. [Android动态修复实践](http://www.sunmoonblog.com/blog/2015/12/02/load-dex/)：本文主要介绍了如何使用Nuwa生成补丁包以及如何使用dalvik_patch的DexInjector加载补丁包，从而实现Android动态修复。

8. [Android 动态加载dex](http://blog.dreamtobe.cn/2015/12/07/android_dynamic_dex/)

6. [AndFix](https://github.com/alibaba/AndFix): 支付宝团队开发的产品。` 局限性： 不支持YunOS;无法添加新类和新的字段；需要使用加固前的apk制作补丁，但是补丁文件很容易被反编译，也就是修改过的类源码容易泄露；使用加固平台可能会使热补丁功能失效（看到有人在360加固提了这个问题，自己还未验证）。`
关于AndFix介绍的一些文章：[AndFix使用说明](http://www.jianshu.com/p/479b8c7ec3e3)
