# 环境介绍和部署

• Bigip VE：14.1.4.4

• AS3版本：3.33.0

• VSCode版本：1.67.2


# 1. 安装环境

1）VSCode下载并安装
https://code.visualstudio.com/

2）安装F5插件

![输入图片说明](pictures/1.png)

3)F5安装AS3和DO
![输入图片说明](pictures/101.png)

# 2.F5 ACC Chariot 转换实验

1）连接F5
![输入图片说明](pictures/2.png)

连接成功后可以看到对应信息

![输入图片说明](pictures/201.png)

2）导入UCS

![输入图片说明](pictures/3.png)

3）ACC转换为AS3

右击选择convert to AS3 with ACC 

![输入图片说明](pictures/4.png)

进入ACC Chariot查看转换输出信息

![输入图片说明](pictures/5.png)

4）用AS3格式下发应用至F5

![输入图片说明](pictures/6.png)

error报错：需修改schemaVersion

![输入图片说明](pictures/7.png)

![输入图片说明](pictures/8.png)

应用下发成功！

![输入图片说明](pictures/9.png)

# 3.DO配置实验 

下载链接 https://github.com/F5Networks/f5-declarative-onboarding/releases

推送DO配置
![输入图片说明](pictures/10.png)

200 ok 推送成功！
![输入图片说明](pictures/12.png)

查看VE上的配置
![输入图片说明](pictures/13.png)