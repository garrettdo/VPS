## Shortcuts -  Mac





### 通用:
hua , setting.

**光标**
*行首*    ⌃ A
*行尾*    ⌃ E
*删除光标后所以内容*  ⌃ K

Delete  ⌃ H
退格     ⌃ D


---
> **Cap & Ctrl 键位互换!** \>系统→键盘→设置!!!!



**终端:**
删除前面全部 *⌃ U*
清屏        *⌃ L*  
中断操作     *⌃ C* 
暂停脚本     *⌃ S*
继续脚本     *⌃ Q* 


**浏览器**
Hua M  最小化 全局

Hua + - 网页缩放

Hua d  加入书签 
Hua shift d   阅读列表

网页文字搜索   hua f

Hua shift b  显示/隐藏 书签栏 
Hua shift l  显示/隐藏阅读列表

Hua 1234  打开书签栏上的第一第二------ 个书签 

Hua  opt f    全选网址  ,












# 1 由于 hhkb 没有方向键!  so ......    要么就配合fn 用/要么就用快捷键.

	终端下:
	
	    ctrl n/p      下/上 # 记忆: next/previous  
	    ctrl b/f      左/右 # 记忆: back/forword   
	
	    ctrl j = 回车   # j 是控制方向的 差不多就是回车的意思
	
	    ctrl h = 删除光标前一个字符
	    ctrl d = 删除光标后一个字符
	    ctrl k = 删除光标后本行所有字
	
	    ctrl a = 光标到行头    #ahead
	    ctrl e = 光标到行尾    #end
	
	    所有unix 终端通用 emacs 也适用!!   Mac 终端亲测可用
	
	Macvim 下:
	
	    esc 模式下 hjkl 控制方向.

↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓

Mac 键盘 改键.  也就是按键映射/Remap  系统级别的.

	改键需要两个软件  seil 和 karabiner(这个是重点) 
	
	karabiner 
	
	    官网下载链接           https://pqrs.org/osx/karabiner/
	    官网改键教程  英语.      https://pqrs.org/osx/karabiner/xml.html
	
	    他能帮忙做绝大多数键盘映射：
	
	        1. 将任何一个按键映射成其他的按键，比如将cmd和opt键对换一下.
	        2. 贴心小功能，比如不重映射笔记本自带键盘.
	        3. 很多内置的键盘映射组合，比如vi mode、Emacs mode等等…
	        4. 调整不同按键的Key repeat 
	
	    vi 全局模式 :   change key 下面  展开vi mode  打勾.
	
	    ★★★★    S + HJKL  就能鼠标上下左右移到,  macvim下通用!
	
	    程序之间的切换  用  command + tab 选程序.
	
	
	
	




全局改键:

	双击esc →  切换输入法   
	
	    1: 系统设置下输入法快捷键    改为^ + 空格
	    2: 然后 karabiner  下 control*2 双击 改为control + space. 
	
	
	
	左ctrl  →    变esc键  
	
	    seil 下面   
	        change ctrl_l  打勾     keycode 改成 53
	        change escape  打勾   keycode 改成 59
	
	
	
	左 alt 不变
	
	    后缀 a-z  快捷启动安装软件
	
	右 alt →  ctrl + alt 
	
	    后缀 a-z  快捷启动自带软件
	
	
	
	右shift  →  向后删除键
	
	
	
	系统偏好设置→快捷键→键盘   
	
	    将F1 F 2 等键用作标准功能键盘. 这个 打上 ✔️
	        这样的话 最上面那行的 特殊功能 就要按下 fn 之后 再按下功能键 才能生效.
	
	    F1      Macvim
	    F2      Iterm
	    F3      记事本   
	    F4      谷歌浏览器
	    F5      Omnifocus
	    F6      Safari
	
	    F7/F8/F9  上一首 停止 下一首    Fn a s d  加减音量  静音
	
	    F10  截图到寄存器.    ⌘+F10 截图到桌面.
	
	    F11  音量 精确减
	    F12  音量 精确加
	
	
	
	     shift + 8  *
	     fn + h    *
	
	Fn [ / ; '    上下左右方向键盘
	
	
	
	better snap tool    控制窗口  和win7 一样.  
	
	    ctrl 回车  最大化    方向键 上下左右均分.
	
	    ctrl + 单指 移动  重新调整窗口大小!

↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑



系统快捷键:         F1 , F2 用做功能键.
然后用KM 设置 功能键的作用  


	• F1          切换输入法            
	• F2
	• F3           Finder 显示桌面
	• F4           Finder    /   浏览器网页后退                      全局 
	• F5           关闭浏览器标签页/ finder 标签
	• F6           新建浏览器标签页/ finder 标签
	• F7           浏览器  /Finder  标签页左移
	• F8           程序全屏                                                         全局
	• F9           标签页右移动
	• F10         区域截图        ⌘ F10 屏幕截图
	• comm + opt + V     剪贴
	
	
	• ⌘     shift  D       桌面
	• ⌘     shift  H       home 目录
	• ⌘     shift  A       应用程序目录
	• ⌘     shift   I        Icloud

⌘ O    打开文件夹
⌘ M   窗口最小化




Alf:
 km  打开km设置


Km 设置 

自带软件快捷键   用 opt 
安装软件                用shift





## 快捷键 - 2
ctrl 和 esc 键 互换:
ctrl 换 esc   karabiner 里设置
esc 换 ctrl   下载seil     进行设置. 
 
偏好设置: 快捷键  键盘 :  
将焦点移到dock   → ctrl 1
 
Finder 快捷键         ^2      KM 下设置.
 
• 
• Command+[ -- 后退
]()•  Command+] -- 前进
• 
• Command+X -- 剪切
• Command+D -- 复制选中项 
 
• Command+O -- 打开选中项目
• 
• Shift+Command+G -- 进入文件夹
• 
• Command+M -- 最小化窗口
• 
• Shift+Command+A -- 打开应用程序文件夹
• 
• Command+I -- 获得信息
• 
• Command+K -- 连接服务器
• 
• Option+Command+M -- 最小化所有窗口
• 
• Command+N -- 打开新的Finder
• Shift+Command+N -- 新建文件夹
• Option+Command+N -- 新建智能文件夹
• 
• 
• Shift+Command+T -- 添加到最爱列表
• 
• Option+Command+Y -- Slideshow（Mac OS X 10.5 及更新的版本）
• Command+Z -- 撤销/重做
• 
• 
• Command+, （Command 和逗号键）-- 打开Finder的设置
• 
• Command+` （Command，加上TAB键上的“`键”。如果你的键盘是标准美式键盘就有这个键。）浏览各个打开的Finder窗口。
• 
• Option+Shift+Command+Esc （按住三秒） -- Mac OS X v10.5、 v10.6 或更新 的版本中，强制退出最前面的程序。
• 
• Command+向上方向键 -- 打开隐藏文件夹
• Control+Command+向上方向键 -- 在新窗口中打开隐藏文件夹
• Command+向下方向键 -- 打开选中的项目
• 
• Command+Tab -- 切换到下一个程序
• Shift+Command+Tab -- 切换到前一个程序
• 
• 
• 空格键（或Command+Y）-- （Mac OS X 10.5 及更新的版本）快速查看
• 拖动时按 Command 键 -- 将拖动的项目移动到其他磁卷或位置处（拖动的时候按此键，会发现指针的形状变了）
 
• 拖动时按 Option 键-- 复制拖动的项目（指针形状变了）
• 拖动时按 Option+Command 键-- 给拖动的项目添加别名（指针形状变了）
 
 
 
 
 
 
开机快捷键:
• Option -- 在启动管理器中显示所有可启动磁卷
• Shift --进行安全启动（安全模式）
• N -- 用网络服务器启动
• Command+V -- 详细启动模式
 

自带快捷键:
 
• ⌘  + tab    程序切换   键盘流必备. 
    一直按住 ⌘  
       按下 s+h/l    实现左右移动   
       按下 h          隐藏程序 相对于 最小化  = ⌘ + H 
       按下Q          直接退出 
 


硬件：   HHKB pro2 白色 无刻. happy hacking keyboard ! 适合程序员/长时间文字录入的人
 
按键映射/Remap软件：       karabiner(这个是重点)   &  seil 
 

 
 karabiner                 官网下载链接            官网改键教程（英语）
 
  作用： 
 
   \1. 将任何一个按键映射成其他的按键，比如将cmd和opt键对换一下.
   \2. 贴心小功能，比如不重映射笔记本自带键盘.
   \3. 很多内置的键盘映射组合，比如vi mode、Emacs mode等等…
   \4. 调整不同按键的Key repeat 
 
  
    change key 下：
 
   vi mode 打勾.  S + HJKL 就能鼠标上下左右移到, macvim下通用
 
 
 
 
 seil                           官方下载链接 
 
  Karabiner……Caps lock搞不定，这时候再装一个 seil 的软件，问题引刃而解。 
 
 他能帮助你: 
 将Caps lock换成任何其他键（几乎是唯一功能） 只能单键修改.
 
   然后seil →setting 下面 change the caps key 打勾.
  打勾后 默认caps 修改成 delete 键 可以改成自己要改的键 (输入相应键的代码就好.)
  按键详细代码 setting 下面有列表的.
 
 

快捷键软件：keyboard maestro   
 macros  :   宏命令/宏的意思     宏:批量处理的称谓,一般指 将小命令或者小动作化为一系列指令.
 string : 字符串         触发面板 trigger        行为面板 Action 
 
KM 系统偏好设置:
  
系统自动登录    打开
同步系统配置    打开 选择文件夹 (云文件夹最好)
Detect and conceal possible passwords    查明和隐藏 可见的密码 ??
 
存最近使用的app记录到硬盘 ?
存剪切板历史记录到硬盘 ?
 
Send diagnostics  发送诊断.
  
基本功能: 1
                             用快捷键启动应该程序
 
 1界面 左 group  选global macro group
 2 中间界面    macros  点地下的加号
 3 右边界面取个名字   然后点 new trigger 出来一堆选框框  选第一个hot key trigger  输入一个快捷键
 4new action 点击 选字一个程序
 5然后下面的勾打上  再enable  就好了
 
 
 
 
 
 
 
 
 
 
 
 
 
 
关闭键盘:
sudo kextunload /System/Library/Extensions/AppleUSBTopCase.kext/Contents/PlugIns/AppleUSBTCKeyboard.kext/
打开键盘:
sudo kextload /System/Library/Extensions/AppleUSBTopCase.kext/Contents/PlugIns/AppleUSBTCKeyboard.kext/
 
 

 
HHKB 简介：
缺点:     键盘有点厚!          USB口: 电压低 手机不能充电. u盘啥都困难.   
优点:     轻巧.                     寿命长 (静电电容:键帽和电路板达到一定距离 电路就会通了! 没有任何的机械接触)
特点：  
1: 没有方向键.   
2: 功能鍵要使用 Fn配合     
3: ctrl 键 替代了一般的 cap键位置. 
4: delete 和 enter 太近了 要小心用 -.-
 
 
 
使用技巧:   
 
 
 终端下:
 
  ctrl n/p 下/上 # 记忆: next/previous  
  ctrl b/f 左/右 # 记忆: back/forword   
 
  ctrl j = 回车 # j 是控制方向的 差不多就是回车的意思
 
  ctrl h = 删除光标前一个字符
  ctrl d = 删除光标后一个字符
  ctrl k = 删除光标后本行所有字
 
  ctrl a = 光标到行头 #ahead
  ctrl e = 光标到行尾 #end
 
  所有unix 终端通用 emacs 也适用!! Mac 终端亲测可
↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓
 
全局改键:
 
 双击esc → 切换输入法   
  
  1: 系统设置下输入法快捷键 改为^ + 空格
  2: 然后 karabiner 下 control\*2 双击 改为control + space. 
 
 
 
 左ctrl → 变esc键  
 
  seil 下面   
   change ctrl\_l 打勾 keycode 改成 53
   change escape 打勾 keycode 改成 59
 
 
   
 左 alt 不变
 
  后缀 a-z 快捷启动安装软件
 
 右 alt → ctrl + alt 
 
  后缀 a-z 快捷启动自带软件
 
  
 系统偏好设置→快捷键→键盘   
 
  将F1 F 2 等键用作标准功能键盘. 这个 打上 ✔️
   这样的话 最上面那行的 特殊功能 就要按下 fn 之后 再按下功能键 才能生效.
 
  F1 Macvim
  F2 Iterm
  F3 记事本 
  F4 谷歌浏览器
  F5 Omnifocus
  F6 Safari
 
  F7/F8/F9 上一首 停止 下一首 Fn a s d 加减音量 静音
 
  F10 截图到寄存器. ⌘+F10 截图到桌面.
 
  F11 音量 精确减
  F12 音量 精确加
 
 
 
   shift + 8 *    fn + h *  
 
 better snap tool 控制窗口 和win7 一样.  
 
  ctrl 回车 最大化 方向键 上下左右均分.
 
  ctrl + 单指 移动 重新调整窗口大小!
 
↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑
 
 
 
系统快捷键: F1 , F2 用做功能键.
然后用KM 设置 功能键的作用  
 
 
 • F1 切换输入法            
 • F2
 • F3 Finder 显示桌面
 • F4 Finder / 浏览器网页后退 全局 
 • F5 关闭浏览器标签页/ finder 标签
 • F6 新建浏览器标签页/ finder 标签
 • F7 浏览器 /Finder 标签页左移
 • F8 程序全屏 全局
 • F9 标签页右移动
 • F10 区域截图 ⌘ F10 屏幕截图
 • comm + opt + V 剪贴
 
 
 • ⌘ shift D 桌面
 • ⌘ shift H home 目录
 • ⌘ shift A 应用程序目录
 • ⌘ shift I iCloud
 
⌘ O 打开文件夹
⌘ M 窗口最小化
 
 
 
 
Alf:
 km 打开km设置
 
 
 
 
Km 设置 
 
自带软件快捷键 用 opt 
安装软件 用shift
 
 
 
 
 
 
 
 
 
 
 
Safari  插件 

vimari      Safari 下的类似 vimium 插件     下载地址
 
 
 
 
 
偏好设置

输入法 :  alt + 空格      手掌按 alt. 
 
 
 
 
 
 Karabiner 教程 
Change key  下面：
 
1: 开启 vi mode      实现全局用 s ＋ h j k l  移动 
 
2：开启得到
 
 
 
 
 





## Shortcuts

⌘ + / -:       放大缩小 看网页或者文本 都有效
 

新建窗口………………………………⌘  + n
 
关闭当前窗口………………………………….⌘ + w
 
最小化当前窗口………………………………..⌘  + m
 
关闭所有窗口………………………………….⌘ ⌥ + w
 
全屏截图……………桌面(.png)…………⌘ + Shift + 3 
 
屏幕部分画面………桌面(.png)…………⌘  + Shift + 4 （自己截取）
 
截取窗口…………桌面(.png）………⌘  + Shift + 4 然后按一下空格
 
 
   ctrl 花 shift 4          区域截图直接存到黏贴板上  
 
空格 花 shift 4          窗口截图 
 
掌握多手势和快捷键（少量即可，多多益善）
 
• Command+Tab                   任意情况下切换应用程序 - 向前循环
• Shift+Command+Tab          切换应用程序 - 向后循环
• Command+Delete               把选中的资源移到废纸篓

• Command+C/V/X                复制/粘贴/剪切
• Command+N                       新建应用程序窗口
• Command+Q                       退出当前应用程序，
• Command+L                       当前程序是浏览器时，可以直接定位到地址栏
• Command+“+/-”                  放大或缩小字体 
• Command+Space              切换输入法
 
























