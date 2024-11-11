# foobox 7.37 (含 foobox 6 重制版), foobar2000 皮肤配置 (DUI)

foobox 是一个 [foobar2000](http://www.foobar2000.org/) 默认用户界面 (DUI) 的皮肤配置，具有简洁而美观实用的特点，善于管理曲目数量大的媒体库 ，对音乐各种封面提供丰富的支持。
\
\
**[项目 GitHub 主页](https://github.com/dream7180/foobox-cn)** |  **[项目Gitee 主页](https://gitee.com/dream7180/foobox-cn)**
\
\
**<a href="/2023/foobox-changelog/" target="_blank">查看更新日志</a>  |  <a href="/2023/foobox-tips/" target="_blank">帮助与使用技巧</a>  |  <a href="/about/" target="_blank">捐助作者</a>**

> **【制作和感谢】**

foobox 中文版适用于 foobar2000 汉化版 by [Asion](https://www.cnblogs.com/asionwu) 或[智享阁](https://www.esnpc.com/)，使用以下组件:  
* ttsping 的歌词组件 [ESLyric](https://github.com/ESLyric/release);  
* 基于 [Spider Monkey Panel](https://github.com/TheQwertiest/foo_spider_monkey_panel) 的 [JSplitter](https://foobar2000.ru/forum/viewtopic.php?t=6378);  
* [foo_enhanced_spectrum_analyzer](https://hydrogenaud.io/index.php/topic,116014.0.html).  

并修改使用以下优秀的代码部件:  
* 播放列表管理器，播放列表，封面浏览原作者 br3tt，汉化 always_beta;  
* 封面面板原作者 Jensen;  
* 搜索框原作者 [Asion](https://www.cnblogs.com/asionwu);  
* [简介面板](https://github.com/Wil-B/Biography)作者 Wil-B;  
* 网络电台列表收集自 [范明明](https://github.com/fanmingming)、[Kimentanm](https://github.com/Kimentanm).  

感谢 fb2k 折腾群的好友对 foobox 的编写提供众多支持， Asion, Elia, always beta, ttsping, 南陇居士(Nanlon), 添加硬件, 唐人清风, BTX, Asooo, Jensen, 庆军等。
感谢所有使用和支持 foobox 的网友。 

> **【安装包】**

* 到上面的 Github 或 Gitee 项目主页 Releases (发行版) 页面下载最新的安装包，请确保您的系统已安装了 foobar2000 汉化版。  
* 从 7.26 版开始增加 foobox 6 重制版 (仅 32 位)，其实是在 foobox 7 的基础上添加 UI Hacks 并整合了两个版本的特点，适合喜欢隐藏菜单栏状态栏 UI 的朋友。
<!--* 感谢[南陇居士](https://www.nljs.site/)制作的整合安装包: [https://www.nljs.site/foobar2000.html](https://www.nljs.site/foobar2000.html)

> **【手动安装】**

{{< admonition warning "注意" >}}
由于所依赖的组件 JSplitter 目前只有 32 位，故暂不支持 foobar2000 x64 版本。
{{< /admonition >}}

1. 下载和安装 foobar2000 汉化版：

* [智享阁Yeyo 汉化版 2.x](https://www.esnpc.com/foobar2000-20-simplified-chinese-version/)，下载 32 位的，或
* [Asion 汉化版 1.6.16 版](https://www.cnblogs.com/asionwu)，注意不要使用 Plus 版，它只集成至 foobox 7.8

2. 下载最新的 Release 包，解压后：

* 复制 themes 文件夹到已有的 foobar2000 中文汉化版目录下;
* 复制 profile 里的文件夹到 foobar2000 用户配置目录下.
* 简介面板 (作者 Wil-B) 需要 [fontawesome-webfont.ttf](https://ghproxy.com/https://github.com/beakerbrowser/beakerbrowser.com/raw/master/fonts/fontawesome-webfont.ttf) 字体，请复制到 C:\Windows\Fonts 目录下. 简介面板的完整功能需要连接外网，请自行解决.

{{< admonition warning "便携版" >}}
便携版，profile 位于 foobar2000 根目录下。目录结构如下:
{{< /admonition >}}
![alt](portable.png)

{{< admonition warning "非便携版" >}}
非便携版，即各用户使用独立配置文件，用户配置文件夹位于：\
**C:\Users\用户名\AppData\Roaming\foobar2000**  (1.x版)\
**C:\Users\用户名\AppData\Roaming\foobar2000-v2**  (2.x版)\
目录结构如下 (2.x版为例):
{{< /admonition >}}
![alt](nonportable.png#pic_left)

> **【额外的视频面板整合】**

从 foobox 7.16 版开始支持整合 foo-youtube 以及 foo-mpv 视频面板到主界面。标准的 release 包没有视频面板组件和主题文件，如需要该功能可下载视频面板整合包([github](https://github.com/dream7180/foobox-cn/releases/tag/video) | [gitee](https://gitee.com/dream7180/foobox-cn/releases/tag/video))，解压后按上面类似的方法安装。完成后可以在 “主菜单--视图--布局--快速设置”里切换各种 foobox 布局组合。
-->

> **【相关网站】**

foobar2000 官方网站：[http://www.foobar2000.org](http://www.foobar2000.org/)

Aion 汉化版博客：[asionwu - 博客园 (cnblogs.com)](https://www.cnblogs.com/asionwu)

智享阁汉化版：[esnpc.com](https://www.esnpc.com/)

> **【界面截图】**  

![foobox7](foobox7.jpg "foobox7")
![foobox7 暗色风格](foobox7dark.jpg "foobox7 暗色风格")
![布局选择](dui.png#pic_left)
