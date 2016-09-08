# URL List For MS-KEY Tool and Garbage Collector

* [MS-KEY Tool](http://bbs.pcbeta.com/viewthread-1514621-1-1.html)
* [Garbage Collector](http://forum.ru-board.com/topic.cgi?forum=2&topic=5328)

# KEY Database

* [Blocked_Keys_VAMT.txt](https://github.com/CNMan/balala/blob/master/Blocked_Keys_VAMT.txt): valid keys, have been blocked(confirmed database by VAMT).

* [Blocked_Keys_PIDKEY.txt](https://github.com/CNMan/balala/blob/master/Blocked_Keys_PIDKEY.txt): valid keys, have been blocked(unconfirmed database from [PIDKey Lite](https://www.solidfiles.com/folder/bd7165a0d4/) ).

* [Fake_Keys.txt](https://github.com/CNMan/balala/blob/master/Fake_Keys.txt): valid keys, have same keyid.

* [Unsupported_Keys.txt](https://github.com/CNMan/balala/blob/master/Unsupported_Keys.txt): valid NT 5.x keys, unsupported by VAMT, you can check them with [The Ultimate PID Checker](http://janek2012.eu/download/pidgen.v1.2.0.606.rar) and/or [PIDKey Lite](https://www.solidfiles.com/folder/bd7165a0d4/).

* [Undefined_Keys.txt](https://github.com/CNMan/balala/blob/master/Undefined_Keys.txt): valid keys, unsupported by VAMT, you need recheck them after add new pkconfig to VAMT.

* [Invalid_Keys.txt](https://github.com/CNMan/balala/blob/master/Invalid_Keys.txt): invalid keys, unsupported by VAMT.

* 如果你使用MS-KEY Tool收集序列号，复制Blocked_Keys.txt、Fake_Keys.txt、Unsupported_Keys.txt、Undefined_Keys.txt、Invalid_Keys.txt中的KEY到/keys/OldKeys.txt，MS-KEY Tool会自动过滤这些序列号。

# [Pull requests](https://github.com/CNMan/balala/pulls)

* 提交前请排序、去重

# [VAMT 支持的产品pkconfig信息](https://github.com/CNMan/balala/blob/master/pkconfig.csv)

注：部分产品需要自行添加相应的`pkconfig.xrm-ms`以提供支持。
* [Get Windows ADK for Windows 10, version 2004](http://download.microsoft.com/download/8/6/C/86C218F3-4349-4AA5-BEBA-D05E48BBC286/adk/adksetup.exe)
* [Get Windows ADK for Windows 10, version 1903](http://download.microsoft.com/download/B/E/6/BE63E3A5-5D1C-43E7-9875-DFA2B301EC70/adk/adksetup.exe)
* [Get Windows ADK for Windows 10, version 1809](http://download.microsoft.com/download/0/1/C/01CC78AA-B53B-4884-B7EA-74F2878AA79F/adk/adksetup.exe)
* [Get Windows ADK for Windows 10, version 1803](http://download.microsoft.com/download/6/8/9/689E62E5-C50F-407B-9C3C-B7F00F8C93C0/adk/adksetup.exe)
* [Get Windows ADK for Windows 10, version 1709](http://download.microsoft.com/download/3/1/E/31EC1AAF-3501-4BB4-B61C-8BD8A07B4E8A/adk/adksetup.exe)
* [Get Windows ADK for Windows 10, version 1703](http://download.microsoft.com/download/5/D/9/5D915042-FCAA-4859-A1C3-29E198690493/adk/adksetup.exe)
* [Get Windows ADK for Windows 10, version 1607](http://download.microsoft.com/download/9/A/E/9AE69DD5-BA93-44E0-864E-180F5E700AB4/adk/adksetup.exe)
* [Get Windows ADK for Windows 10, version 1511](http://download.microsoft.com/download/3/8/B/38BBCA6A-ADC9-4245-BCD8-DAA136F63C8B/adk/adksetup.exe)
* [Get Windows ADK for Windows 10, version 1507](http://download.microsoft.com/download/8/1/9/8197FEB9-FABE-48FD-A537-7D8709586715/adk/adksetup.exe)
* [Get Windows ADK for Windows 8.1 Update](http://download.microsoft.com/download/6/A/E/6AEA92B0-A412-4622-983E-5B305D2EBE56/adk/adksetup.exe)
* [Download and install the Windows ADK](https://docs.microsoft.com/en-us/windows-hardware/get-started/adk-install)
* [Install the Windows ADK offline](https://docs.microsoft.com/en-us/windows-hardware/get-started/adk-offline-install)
```
adksetup.exe /features OptionId.VolumeActivationManagementTool
```

# 致谢

* [hnfeng@bbs.pcbeta.com](http://bbs.pcbeta.com/viewthread-1514621-1-1.html)

* [Ratiborus@forum.ru-board.com](http://forum.ru-board.com/topic.cgi?forum=2&topic=5559)

* [janek2012@forums.mydigitallife.info](http://forums.mydigitallife.info/threads/20816)

* [ASV93@forums.mydigitallife.info](http://forums.mydigitallife.info/threads/48346)
