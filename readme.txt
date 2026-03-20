=== 插件名称 ===
贡献者：ychen
捐赠链接：http://chenyundong.com/
标签：插件，ucenter，集成
至少需要：2.9
测试至：3.2.1
稳定标签：0.3.5

将WordPress与ucenter集成，这将使WordPress能够在ucenter支持的平台下运行。

== 描述 ==

此插件帮助WordPress与ucenter支持的平台协同工作。使用它，您可以轻松地将WordPress与ucenter集成。
安装完成后，WordPress将呈现如下状态：
>1. 当用户登录WordPress时：
 1. 如果用户不存在于ucenter中，则在ucenter中自动注册用户。
 2. 如果用户在ucenter中存在，且覆盖选项已启用，则用户将成功登录，且wordpress中的密码将被ucenter中的密码覆盖。否则，登录失败。
2. 在WordPress中删除用户时，ucenter中的用户也会被删除。
3. 当用户登录其他应用程序时，也会自动登录WordPress。
4. 当用户退出WordPress时，该用户也会自动退出其他应用程序。
5. 当用户退出其他应用程序时，用户也会自动退出WordPress。

顺便说一句，在启用消息、头像、积分、好友组件后，您可以在WordPress中发送消息、更改头像、兑换积分和添加好友。
对于WordPress和Discuz的粉丝来说，那将是非常酷的事情。

该插件已在3.2.1版本中进行了测试，未启用多站点功能。  
将UC客户端升级至1.6.0版本
捐赠：http://chenyundong.com/?p=368

== 安装 ==

1. 将ucenter-integration上传到`wp-content/plugins/`目录。
2. 通过WordPress中的“插件”菜单激活该插件。
3. 登录控制面板并进行适当设置。

== 常见问题 ==

= 遇到“访问被拒绝”时，我该怎么办？

进入ucenter集成插件目录，删除config.php文件，然后登录控制面板以重置ucenter集成的设置。

= 如果问题仍然存在，我该怎么办？

进入插件目录，删除ucenter-integration并重新安装此插件。

== 截图 ==

1. 设置
2. 消息组件
3. 朋友组件
4. 信用部分
5. 头像组件

== 更新日志 ==

= 0.3.5 =
将UC客户端升级至1.6.0版本
修复邮箱无表格的错误

= 0.3.4 =
> 修复更新用户时出现的错误丢弃问题
> 修正一些拼写错误
移除核心破解部分
支持中文登录名

= 0.3.3 =
修复了在发送头部之前发送字符的错误
修复activated_plugin钩子

= 0.3.2 =
修复了在发送头部之前发送字符的错误
修复权限拒绝错误

= 0.3.1 =
修复ucenter用户无法登录wordpress的bug

= 0.3 =
修复错误

= 0.2 =
修复一些错误
添加邮箱
添加自定义图标
添加好友
> 增加学分

= 0.1 =
> 第一个版本
用户可以同步登录所有已集成到ucenter的应用程序
当用户登录已集成到ucenter的其他应用时，会自动登录到WordPress
> 当用户在ucenter中不存在时，用户登录wordpress时将在ucenter中自动注册

== 升级通知 ==

= 0.1 =
首次发布。无需升级







=== Plugin Name ===
Contributors: ychen
Donate link: http://chenyundong.com/
Tags: plugin, ucenter, integration
Requires at least: 2.9
Tested up to: 3.2.1
Stable tag: 0.3.5

Integrate wordpress with ucenter, which will make wordpress work with ucenter supported platform.

== Description ==

This plugin help wordpress work with ucenter supported platform. Using it, you can easily integrate wordpress with ucenter.
After installation, wordpress will act like this:
>1. When user login wordpress:
 1. If user does not exist in ucenter, auto register user in ucenter.
 2. If user exist in ucenter, if override option is enabled, user will login successfully and password in wordpress will be overrided by that in ucenter. otherwise, login failed.
2. When delete user in wordpress, user in ucenter will be deleted.
3. When user login other apps, user will also auto login wordpress.
4. When user logout wordpress, user will also auto logout other apss.
5. When user logout other apps, user will also auto logout wordpress.

BTW, After enabling msg, avatar, credit, friends component, you can send msg, change avatar, exchange credits and add friends in wordpress.
That will be very cool for wordpress and discuz fans.

Plugin has been tested in 3.2.1 without multi site.  
Upgrade UC client to 1.6.0  
Donate: http://chenyundong.com/?p=368

== Installation ==

1. Upload ucenter-integration to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Login dashboard and make suitable setting.

== Frequently Asked Questions ==

= What should I do when enconter Access denied?

enter ucenter integration plugin dir, remove config.php and login dashboard to reset setting of ucenter integration.

= If problem still exists, what should I do?

enter plugin dir, remove ucenter-integration and reinstanll this plugin.

== Screenshots ==

1. setting
2. message component
3. friend component
4. credit component
5. avatar component

== Changelog ==

= 0.3.5 =
> upgrade uc client to 1.6.0  
> fix MailBox no table bug

= 0.3.4 =
> fix error discard when update user  
> fix some typos  
> remove core hack part  
> support chinese login name  

= 0.3.3 =
> fix sending chars before sending header bug  
> fix activated_plugin hook

= 0.3.2 =
> fix sending chars before sending header bug  
> fix permission deny bug

= 0.3.1 =
> fix ucenter user can not login wordpress bug

= 0.3 =
> fix bugs

= 0.2 =
> Fix some bugs  
> add mail box  
> add customize icon  
> add friend  
> add credit

= 0.1 =
> First version  
> User can synlogin all apps that has been integrated into ucenter  
> When user login other apps that has been integrated into ucenter, user will auto login wordpress  
> When user does not exists in ucenter, user will be auto registered in ucenter when user login wordpress

== Upgrade Notice ==

= 0.1 =
> First release. No need to upgrade
