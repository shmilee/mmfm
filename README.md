## 简介introduction
 fork from [ubuntu论坛:酷我电台，豆瓣fm(更新)](http://forum.ubuntu.org.cn/viewtopic.php?f=74&t=351034)

 网络音乐电台 An Internet-Radio toolkit(P.R.China)
 
 支持的电台：豆瓣电台，多米音乐，酷狗电台，酷我电台，网络电台，青檬音乐，人人电台，虾米电台

## 依赖depends

**Archlinux**  
 'pywebkitgtk' 'python2-notify' 'gst-plugins-base-libs'

##变更changelog

 ---2012.11.10  
 在论坛2011-12-16更新的版本基础上：  
  1.把默认python改成python2,适应archlinux。  
  2.调整目录结构，便于打包。  
  3.启动器按alt拖动后的位置记录文件，改放到$HOME/.mmfmrc。  
    解决因为权限问题而没法右键退出起动器。默认第一次打开位置为:800 600.  

## TODO
 
 1.网络电台(不出声)，青檬音乐(网址有误),这两检查一下。  
 2.相似的电台脚本整合成一个，传入网址等;起动器8个电台改写到配置文件。
