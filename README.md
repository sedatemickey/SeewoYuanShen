# SeewoYuanShen
将希沃白板5的启动图替换为原神（x

源于B站@刻御晴空 [用两分半教你用原神的方式启动希沃白板](https://www.bilibili.com/video/BV1jV411N7uq/)

## 简介
易语言写的，360会报毒（易语言写的都报，不放心可以自己编译）

重新画了启动图

## 用法
直接运行一次会将启动图换为原神，再运行一次恢复

用了没反应的可以管理员权限运行试试，或者用带日志窗口的版本看看哪里出的错

## 原理
1. 将希沃安装路径下的 SplashScreen.png 文件替换为原神启动图并备份希沃原版启动图（EasiNote5\EasiNote5_5.2.3.1507\Main\Assets\SplashScreen.png）
2. 将 Appdata 里的 Banner.png 替换为原神启动图（%appdata%\Seewo\EasiNote5\Resources\Banner）
3. 将第2步中的 Banner.png 改为只读以防止被希沃白板替换回原版启动图
4. 写入 edited 文件以标记修改（EasiNote5\EasiNote5_5.2.3.1507\Main\Assets\edited）

## 已知问题
~~好像只有刚换完的第一次启动有效，关了希沃再开就又变回原来的了，不知道咋办~~ 已经通过把Banner改成只读解决了
