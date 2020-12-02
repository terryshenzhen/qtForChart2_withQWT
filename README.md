# qtForChart2_withQWT
this is a project to show how to use QWT libs in QT project to show a beautiful chart


关山月

作者：李白

明月出天山，苍茫云海间。 
长风几万里，吹度玉门关。 
汉下白登道，胡窥青海湾。 
由来征战地，不见有人还。 
戍客望边色，思归多苦颜。 
高楼当此夜，叹息未应闲。


Env:
 win10+ minGW32 + QT5.9.9
OK


运行时，应将qwt库文件qwtd.dll放在：
qwtChart003\build-qwtChart003-Desktop_Qt_5_9_9_MinGW_32bit-Debug\debug
否则会因为找不到库文件报错


BarChart---天龙八部图
barchart2--钢筋规格图
特别注意：
以上两个类在切换时，必须关闭一个，除了在pro中删除文件，在头文件中去掉包含之外，
必须在源码目录中移走。否则qt还是会找到其中，且报错。这点很奇怪。


