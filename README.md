# 燃鹅向前冲逆向测试记录

### 此仓库仅为逆向学习过程中的一个测试，禁止任何人用于商业用途，请严格遵守开源协议

###如果有帮助，请给我一个star！⭐

### 文件结构

postcode.py为实现请求发送的python文件

deceode.js为实现加密解密的js源码

note.js为学习过程中的笔记记录

### 使用说明

经过查看源代码，可以轻松找到加密方式及提供的接口，在文件中已做详细注释，请勿利用该测试记录干扰游戏进程

在windows下运行需要改python目录下lib目录里的subprocess.py文件的编码,init的encoding改为utf-8

### 心得

qq小程序源代码保存与Data/data/com.tencent.mobileqq/files/minigame，以文件夹存储，无需解密

qq小程序源代码为混淆过的js文件，但混淆程度较低，容易破解，搜索接口即可找到发送数据的函数，过程中用到的函数只需要搜索.functionname(即可找到其定义位置，逆向难度较低

