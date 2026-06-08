# GOTO

<div align="center">
  <img src="GOTO_LOGO.png" width="120"/>
</div>

Keywords:   
  Quick startup, lightweight design, local operation,   
  statistical functions, high degree of customizability,   
  multiple operating modes available, seamless user experience.

  
关键词：  
  快速启动 轻量 本地 统计功能 高度自定义   
  多种操作模式可选 无感操作  


## What is GOTO 是什么？

A quick launch software for Android. 
一个安卓端的快速启动软件


  
## Why choose GOTO? 为什么选择GOTO?

The core search and launch features of the software run entirely locally on your device.  
For core search: given the compact input panel of mobile IME keyboards which often causes mis-taps and poor usability,   
we have added out-of-order search, fuzzy search and quick bind search to boost operating efficiency on mobile devices.  
Premium membership unlocks usage statistics and cross-device sync via activation code:  
Statistics cover registration date, total usage days, aggregate character input count, overall app launch count,   
breakdown launch counts of individual apps with gradient statistical charts, plus a TOP5 ranking of most-opened applications.  
Membership is a one-time lifetime purchase license, valid for one single device per activation code.  
We have no restrictions on legitimate membership obtained via alternative channels, as such support counts as recognition of our product.  
Feedback, positive or constructive criticism, is always welcome.   

软件本体的基本搜索和启动功能支持**纯本地**运行。  
基本搜索功能方面，考虑到手机输入法输入窗口较小，容易误触从而导致体验下降 
我们额外支持乱序搜索，模糊搜索，快捷绑定搜索，悬浮球等功能以提高移动设备的操作效率（详情请见"## Introduction to Examples of Core Functionality 核心功能例子介绍"）  
同时，会员附带使用**统计功能**  
（统计项包含：注册日期，使用天数，软件启动次数，输入字符数，总启动次数以及各软件启动次数的梯度统计图，当然也有TOP5的软件启动次数）    
以及通过激活码实现的**多端同步**功能  
会员为**终身买断制**，单次仅限一台设备使用————你最常触碰的那台，也支持无限设备间切换   
我们理解并尊重每一位用户的获取方式，无论通过何种途径使用，都是对我们的认可，
同时，您的反馈也是对我们最大的支持。 


**统计功能数据结构示例：
```json
{ 
  "Activate_ID": "", 
  "Registration_Date": "", 
  "User_Day": 0, 
  "APPStart_Times": 0, 
  "Character_Num": 0, 
  "Total_Use_Time": 0, 
  "App_Launches": [] 
}
```



  
## Introduction to Examples of Core Functionality 核心功能例子介绍

### English-speaking ecosystem users, look here!!!
1. Fuzzy Search: If you want to look up Spotify, typing wrong spellings like "Spotok" will trigger the matching algorithm to prioritize showing the Spotify app (this applies when no other
   app named Spotok is installed on your device). Additional note: If an app named Spotok does exist on your phone, it will also be listed in search results, as multiple matches can be
   displayed simultaneously.
   Supplementary Rule 1: Typing errors caused by cramped keyboards or small screen sizes—such as mistyping "Spotify" as "Spk7fiyb" due to extra, missing or misclicked letters—can still be
   recognized by the system, which intelligently filters out Spotify as your intended target. Feel free to test this feature inside the app; this fuzzy search function is available
   completely free of charge.
2. Fuzzy Search:Supports app lookup via Chinese Pinyin or loose spelling.
   To take Amazon as an example, keywords such as amazon, ama, amazo can all locate the target application.
3. Additional Search Feature: Take Amazon for example. If you start typing "Ama" but then change your mind and want to open another app such as Uber, Spotify or WhatsApp, there’s no need to
   backspace, delete existing input or return to the blank search bar. Just keep typing the name of your newly desired application, and the system will prioritize your latest search
   intention automatically.
4. Custom Quick-tag Search:You may bind a custom shorthand tag like amz to Amazon, with two optional running modes.
   Standard Mode: Typing amz pins Amazon at the top of your search results.
   Quick Launch Mode: Inputting amz directly opens Amazon instantly with no extra confirmation tap.
   Note: Improper configuration of Quick Launch Mode may degrade user experience, please adjust settings carefully.
5. Additional available features include intelligent automatic indexing, floating shortcut ball, in-app quick-launch menu (sort automatically by launch frequency, manual drag rearrangement, or hybrid sorting), gesture
   triggered app launching (swipe up/down/left/right plus customized complex gestures), categorized app folders, and more features to explore.
6. To be continued…………


  
### 中文生态用户看这里！！！  
1. 乱序搜索：如果您需要搜索京东，即使您输入东京，系统也能为您通过匹配度算法 高优先级显示"京东"软件（前提是如果你的手机没有名字带有东京的应用的话）；补充：如果有，软件也能索引到，毕竟搜索结果不止一个。
2. 补充1:即使您因为键盘太挤，屏幕偏小等原因导致点错，点多，点漏字母，如jd输入为jhkfded，系统也能综合判断为您选择出京东。具体请进入软件体验，该功能也在免费功能范围内。
3. 追加搜索功能：又双叒叕是京东，如果您输入京东，突然想去其他软件，比如淘宝？美团？饿了么？不需要退格，不需要删除，也不需要返回；只需要继续在后面加入您想要跳转的应用，软件将会以您最新的意图为准。
4. 模糊搜索：通过中文拼音搜索应用（当前仅支持软件名字，比如搜索京东，jingdong/jd/jingdoo类似均可）
5. 快捷绑定搜索：同样地，您可以通过绑定jd索引京东软件，并且可以选择标准/快速模式；标准模式下，输入“jd",京东将会置顶显示；而如果是快速模式，您输入jd，将会不经过额外的确认点击按钮 软件直接跳转到jd软件，  
（请注意，快速模式下，如果设置不当可能导致体验下滑，请三思而后行）
6. 还有如智能索引，悬浮球功能，软件内通过手势打开应用（上滑，下拉，左右滑动以及各种复杂手势）等功能等待探索
7. 未完待续…………


 
  

## Other tips 其他提示：
The software is still under development   
and may contain some bugs. Thank you for your understanding!  
The software will be available on a lifetime purchase basis.   
Currently, it is in Beta testing, and all member features are free to use.   
(Activation codes and synchronization functions are included.)  
If you find this software helpful, please click a **star**.  
  
软件尚处于完善阶段，可能出现部分BUG，提前感谢您的谅解！
软件后续采用终身买断制，当前处于Beta测试阶段，所有会员功能均可免费使用。（激活码和同步功能暂时不可使用）
如果您认为该软件对您有帮助，请点一个**星星**
