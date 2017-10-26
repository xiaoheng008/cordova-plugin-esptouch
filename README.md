# cordova-plugin-esptouch
smartconfig配网 来源：https://github.com/GTDistance/cordova-plugin-esptouch.git

esptouch cordova插件，支持esp8266
 
ios端编译出错，找不到.h文件，
解决方案：
在Build Phases -> Compile Sources 中手动添加ios工程中，Plugins/esptouch/ 文件夹下的所有文件，添加之后会在Xcode工程根目录下显示。
然后再次编译
