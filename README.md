MDWechat
====
# 简介
 Fork自 [Blankeer/MDWechat](https://github.com/Blankeer/MDWechat) ,支持微信7.0.15.

# 功能
实现的功能有:
1. 主界面 TabLayout Material 化,支持自定义图标
2. 主界面 4 个页面背景修改
3. 全局 ActionBar 和 状态栏 颜色修改,支持主界面和聊天页面的沉浸主题(4.0新增)
4. 自动识别微信深色模式以调整MDwechat配色方案(3.6新增)
5. 主界面添加悬浮按钮(FloatingActionButton),支持自定义按钮文本/图标/入口, 4.0支持自定义悬浮按钮点击之后的旋转角度
6. ~~主界面搜索 Material 化~~(2.0未加入)
7. 全局头像圆角
8. 全局状态栏颜色修改,支持半透明/全透明(沉浸)
9. 主界面列表去掉分割线,增加 Ripple 效果(按下水波纹),支持修改颜色
10. ~~主界面支持隐藏 发现/设置 页面~~(2.0未加入)
11. ~~支持聊天列表置顶底色修改~~(2.0未加入)
12. 聊天气泡修改,支持.9图,支持修改着色,支持修改文本颜色
13. ~~发现页面支持隐藏朋友圈/扫一扫/摇一摇/附近的人/游戏/购物/小程序~~(微信自带,2.0已去掉)
14. ~~移除会话列表下拉小程序,最低支持微信 6.6.2~~(微信7.0.0以上失效)
15. 识别微X模块入口,移动到悬浮按钮(2.0新增)
16. 主界面字体颜色修改(2.0新增)
17. 细化设置项并添加4个内置配色方案(4.0新增)

# 版本支持
- 只支持 Android 5.0 以上
- 支持的微信版本: 6.7.3 - 7.0.15
- MDWechat(官改) 4.0 对于国内版的适配性比较好，play版微信在部分机型上会出现无法适配的状况。

# 效果预览
![main00](https://gitee.com/JoshCai/MDWechat/raw/v4.0/image/main00.png)
![chat00](https://gitee.com/JoshCai/MDWechat/raw/v4.0/image/chat00.png)
![main01](https://gitee.com/JoshCai/MDWechat/raw/v4.0/image/main01.png)
![main02](https://gitee.com/JoshCai/MDWechat/raw/v4.0/image/main02.png)
![main03](https://gitee.com/JoshCai/MDWechat/raw/v4.0/image/main03.png)
![main04](https://gitee.com/JoshCai/MDWechat/raw/v4.0/image/main04.png)
![main05](https://gitee.com/JoshCai/MDWechat/raw/v4.0/image/main05.png)
![chat01](https://gitee.com/JoshCai/MDWechat/raw/v4.0/image/chat01.png)

# 使用教程
[查看使用教程](https://gitee.com/JoshCai/MDWechat/wikis/?sort_id=2158198)

# 存在的问题
1. 导致微信变卡,这是无法避免的.
2. 悬浮按钮在某些机型(魅族/中兴)上显示异常,在聊天页面会显示.
3. 4.0版本对于一些高分辨率的机型可能存在闪退的情况.
4. 微信7.0.5之后进入首页可能产生黑色遮罩, 一般来说下滑即可消除.
5. 点击最近聊天进入聊天页面后,返回主界面时有几率产生白条, 这时把白条移除屏幕外(比如下拉到小程序界面等)即可消除白条.

# 感谢
1. [Blankeer/MDWechat](https://github.com/Blankeer/MDWechat)
2. [WechatSpellbook](https://github.com/Gh0u1L5/WechatSpellbook)
3. [WechatUI](https://www.coolapk.com/apk/ce.hesh.wechatUI)
4. [群消息助手](https://github.com/zhudongya123/WechatChatroomHelper)
5. [WechatMagician](https://github.com/Gh0u1L5/WechatMagician)
6. [ForceWechatDarkMode](https://github.com/chouqibao/ForceWechatDarkMode)

(背景图片来源于网络)


