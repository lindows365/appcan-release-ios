# appcan-release-ios
### 2015/7/3版本更新记录
####iOS引擎：            版本号：ios_Engine_3.1_150706_02      更新内容： 
 1. 新增isAppInstalled及回调；新增监听onWindowAppear、onWindowDisappear 2. 新增reload,reloadWidgetByAppId
 3. 修改widget未初始化就使用的问题

####iOS插件：
 1. 插件名称及版本号：uexWeiXin-3.0.15      更新内容：cbStartPay回调结构修正
    
### 2015/6/25版本更新记录

####iOS插件：
 1. 插件名称及版本号：uexQQ-3.0.6      更新内容：cbLogin回调结构修正
 2. 插件名称及版本号：uexSina-3.0.5      更新内容：注册回调方法名统一修改为uexSina.cbRegisterApp
 3. 插件名称及版本号：uexFileMgr-3.0.9
       更新内容：新增方法uexFileMgr.renameFile 重命名文件及其回调uexFileMgr.cbRenameFile
 4. 插件名称及版本号：uexLocalNotification-3.0.2      更新内容：修复iOS8.0+系统上可能不能正常发送通知的bug
     5. 插件名称及版本号：uexAreaPickerView-3.0.2      更新内容：新增
 6. 插件名称及版本号：uexCalendarView-3.0.0      更新内容：新增
     7. 插件名称及版本号：uexChatKeyboard-3.0.3      更新内容：新增
 8. 插件名称及版本号：uexInputTextFieldView-3.0.3      更新内容：新增
 9. 插件名称及版本号：uexLoadingView-3.0.3      更新内容：新增
 10. 插件名称及版本号：uexIndexBar-3.0.5
       更新内容：索引文字支持配置颜色和内容
 11. 插件名称及版本号：uexQQ-3.0.8.zip
       更新内容：不再支持分享至QQ好友的所有相关接口中的cflag可选参数
### 2015/6/19版本更新记录

####iOS引擎：            版本号：ios_Engine_3.1_150619_01      更新内容： 
 1. setMultilPopoverFlippingEnbaled与安卓统一效果
  2. addSubViewToScrollView 修复手势被网页错误拦截的问题 	          ####iOS插件：
 1. 插件名称及版本号：uexEasemob-3.0.9      更新内容： 
    * 添加getTotalUnreadMsgCount接口
    * 获取全部公开群改成分页获取


### 2015/6/12版本更新记录

####iOS引擎：
  
  版本号：ios_Engine_3.1_150612_01    更新内容：修复了在popover页面中不能正确执行openMultiPopover的bug.

                       ####iOS插件：          1. 插件名称及版本号：uexAreaPickerView --3.0.2
	 	更新内容：修复了插件会因失去焦点而被错误关闭的bug.
***

### 2015/6/5版本更新记录
####iOS插件：

1.	插件名称及版本号：uexWeiXin-3.0.14
	
	更新内容：uexWeiXin插件，支付sdk升级。
	

	

***
### 2015/5/29版本更新记录
####iOS插件：

1.	插件名称及版本号：uexEasemob-3.0.8
	
	更新内容：
	
	* 新增 发送视频消息 和 发送已读回执 的接口;	
	* 发送的消息，新增ext和length属性；
	* 修复bugs.
	
2. 插件名称及版本号：uexJPush-3.0.0

 	更新内容：新增极光推送插件
 	
3. 插件名称及版本号：uexScrollPicture-3.0.0
	
	更新内容：新增轮播图插件
	
	
	

***
### 2015/5/20版本更新记录

####iOS引擎：
  
  版本号：ios_Engine_3.1_150520_01    更新内容：

1. 新增uexWindow.setMultilPopoverFlippingEnbaled()方法；2. 添加webview嵌view方法（非API接口，供自定义插件调用）；3. 新增onPopoverLoadFinishInRootWnd(name,url)监听方法；4. 修复setBounce会导致滚动条消失的bug；                         5. 添加reachabilityWithHostname方法。

                       ####iOS插件：          1. 插件名称及版本号：uexAliPay-3.0.8
 	更新内容：支付宝插件升级  2. 插件名称及版本号：uexXmlHttpMgr-3.0.7
 	更新内容：onData回调函数参数修改 3. 插件名称及版本号：uexDownloaderMgr-3.0.3
 	更新内容：修复不支持HTTPS问题 4. 插件名称及版本号：uexUploaderMgr-3.0.6
 	更新内容：修复不支持HTTPS问题 5. 插件名称及版本号：uexAudio-3.0.10
 	更新内容：更新MP3编码lame库；提高录音功能输出的MP3文件的采样率；修复生成的录音mp3文件不能通过http方式播放的bug。 6. 插件名称及版本号：uexGaodeMap-3.0.0
 	更新内容：新增高德地图插件
