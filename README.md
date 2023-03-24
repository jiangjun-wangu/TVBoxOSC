# TVBoxOSC
tvbox 源码
•fork 项目地址
https://github.com/Wsine/android_builder   
•使用这个复刻过来，用这个打包就是debug版（即9-10M版）
•接着复刻这个地址
•fork 项目地址
https://github.com/CatVodTVOfficial/CatVodTVOSC
•这个官仓复刻过来直接打包就是release版（即6M版）
第三步
•修改android_builder项目下的project-to-build文件里的地址为：
https://github.com/你的账号/CatVodTVOSC
（你账号填写你注册的账号不是吧这个文字复制进去）
•或者你自己的复刻过来官版的地址fork项目
https://github.com/CatVodTVOfficial/CatVodTVOSC    
•至此，（你的账号）账号下有上述两项目，https://github.com/你的账号/android_builder
https://github.com/你的账号/CatVodTVOSC
第四步
•进入点击标注位置文件
•修改成你自己的仓库地址
https://github.com/你的账号/CatVodTVOSC
•或者是
https://github.com/CatVodTVOfficial/CatVodTVOSC
•默认是tvbox官仓地址，可忽略不改
第五步
•以下操作只针对此两项目
•修改android_builder项目下的project-to-build文件里的地址为
https://github.com/ABC/CatVodTVOSC
修改CatVodTVOSC项目下
app/src/main/java/com/github/tvbox/osc/api/ApiConfig.java
此文件的82行，把
(HawkConfig.API_URL, "这里改为接口地址失效内置接口");
•详细操作可参阅
https://github.com/Wsine/android_builder
的readme，此处特别感谢Wsine！！！
•当然更感谢CatVodTVOSC项目组所有人！！！坐等2分钟，下载安装即可最先使用TVbox
