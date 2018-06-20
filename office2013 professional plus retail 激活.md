# skills
##### 软件的安装激活etc.
1. 下载KMS软件、Toolkit软件
2. windows+X+A 管理员打开cmd
3. KMS 将Retail转化为Vol（零售→批量）
4. 命令行输入office路径 d:  ->  回车  ->  \office\Office15  ->  回车  ->  cscript ospp.vbs/dstatus  ->  回车  ->  
(LICENSE NAME: Office 15, OfficeProPlusR_Grace edition //这里标明了你的（不一定是你现在安装的）office版本
LICENSE DESCRIPTION: Office 15,RETAIL(Grace) channel //同上
ERROR CODE: 0xC004F009 //错误代码
ERROR DESCRIPTION: The Software Licensing Service reported that the grace period expired. //未激活的错误描述
Last 5 characters of installed product key:27GXM //这里是你为该产品安装的密钥的后5位
->  cscript ospp.vbs /unpkey:27GXM 删除多余的key(27GXM换成你要删的密钥的后5位))-------------可省略
5.Toolkit 点击office （右下角第一个）  ->  选择Activation标签  ->  点击Set Installer Path  ->  点击激活
