﻿[English]
1.The main part of this project is the source code of GT Console.

2.This project relies on 3 jars:
(1)android-support-v13.jar
(2)mid-sdk-2.xx.jar, download: mta.qq.com
(3)mta-sdk-2.x.x.jar, download: mta.qq.com
Before building the project, please make sure those 3 jars are in the libs folder under the root directory.

To use GT for network traffic capture, please download tcpdump(download: http://www.androidtcpdump.com/android-tcpdump/downloads) to the /res/raw/ folder under the root directory. 

3.The detailed description of each module can be found in the package-info.java, which is located in every package under the src directory.

4.The sdk folder under the root directory includes the source code of GT SDK and the shell project for debug use. To export the GT SDK as a jar, please select both the src folder and the com.tencent.wstt.gt folder in gen folder, click the right key, select export as a jar.

5.The demo folder under the root directory is a sample app project packaged with GT SDK. It can be imported into Eclipse.


[Chinese]
1.本Andorid工程主体源码是GT Console的源码。

2.本工程依赖于三个jar:
    (1)android-support-v13.jar
    (2)mid-sdk-2.xx.jar，请到mta.qq.com网站下载
    (3)mta-sdk-2.x.x.jar，请到mta.qq.com网站下载
请编译前将上述jar包放到工程根路径下的libs目录中。

如使用抓包功能，需将tcpdump下载至工程根目录下的/res/raw/目录中。tcpdump请到http://www.androidtcpdump.com/android-tcpdump/downloads 下载最新版即可

3.具体模块描述请参考src目录中各package中的package-info.java文件。

4.根目录下的sdk目录，是GT SDK的源码及其调试的壳工程。需要将GT SDK导出jar包时，请选中src目录，及在eclipse中即时生成的gen目录中的package:com.tencent.wstt.gt及其子package导出jar即可。

5.根目录下的demo目录，是合入了GT SDK的一个被测app样例工程，可以直接用eclipse导入。