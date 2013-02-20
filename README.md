aSM: Android Client for newsmth
==============================

aSM -- android上的水木清华客户端


下载地址
==============================
Build Date: 2013-02-19.

<a href="https://github.com/zfdang/asm-android-client-for-newsmth/raw/master/dist/aSM.apk">aSM.apk</a>

更新历史
==============================

2013-02-20:
------------------------------
1. 修正收藏夹版面加载的问题，原来的实现没能利用本地的缓存;
2. 修正了对帖子列表的处理，上次在标题后添加回复数量后，除了同主题模式，其他模式都会crash

2013-02-19:
------------------------------
1. 修正了分类目录的刷新，弃用了资源里缺省分类目录，第一次会自动从web加载;
2. 修改了UrlImageViewHelper库, 对图片自动缩放, 使得图片可以占用屏幕的全部宽度;
3. 增加了帖子回复数量，在标题后面的括号中显示;
4. 登录时，区分网络连接错误和认证错误;

2013-02-17:
------------------------------
1. 更新了UrlImageViewHelper库。原来附件里图片，缺省的显示大小是200X400，在高分辨率的屏幕下看起来效果不好；升级了之后，如果图片较大，可以充分利用屏幕了
2. 增加了退出是否需要确认的设置；缺省需要确认退出；
3. 在底部的工具栏中增加了夜间模式，这样可以快速切换白天、夜间模式了
4. 缺省展开了水木十大
5. 收藏夹里，首先显示“我的收藏夹”的内容并缺省展开，然后再显示最近访问的版块

Original project home
==============================

http://code.google.com/p/asm-android-client-for-newsmth/