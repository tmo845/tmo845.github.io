#Mac下安装jdk
##1 在官网下载jdk
https://links.jianshu.com/go?to=https%3A%2F%2Fwww.oracle.com%2Fjava%2Ftechnologies%2Fdownloads%2F

##2 点击安装包进行安装
  ![image](https://user-images.githubusercontent.com/61699540/208234779-d588f77e-8202-4001-8c79-7772531955a1.png)
   
##3 配置系统环境变量

###3.1 找到JDK的主目录`/Library/Java/JavaVirtualMachines/jdk1.8.0_351.jdk`

![image](https://user-images.githubusercontent.com/61699540/208234791-3d81dfa6-3b14-4a85-8bd9-32f030360bba.png)

###3.2	进入用户的home目录：`cd ~/`

###3.3	输入 `java –version`

![image](https://user-images.githubusercontent.com/61699540/208234803-1403c67d-5406-463a-a21d-00ca7698efd8.png)
 
###3.4	查看jdk安装路径：`/usr/libexec/java_home -V`

![image](https://user-images.githubusercontent.com/61699540/208234812-1b2294e6-9752-4ef9-975d-27dbaf60d9e1.png)

###3.5 使用“touch .bash_profile” 创建一个.bash_profile的隐藏配置文件，然后再次编辑使用这个命令open -e .bash_profile"使用这个命令会弹出一个编辑框输入一下内容
![image](https://user-images.githubusercontent.com/61699540/208234827-15c3088e-02ff-4bcd-ba67-dcd28c285413.png)
![image](https://user-images.githubusercontent.com/61699540/208234839-af509069-6de2-45d6-8dc0-a149ffb550a9.png)

###3.6	使用"source .bash_profile"命令,使配置生效

![image](https://user-images.githubusercontent.com/61699540/208234859-08aee515-4c44-4c0d-9e19-b9fc36a54a36.png)

###3.7	`echo $JAVA_HOME` 命令显示刚才配置的路径，看有就是成功

![image](https://user-images.githubusercontent.com/61699540/208234339-0a152fd7-230a-48e5-a7b6-a72bfcec67f6.png)
