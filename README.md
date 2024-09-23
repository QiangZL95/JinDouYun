# JinDouYun

下载链接 

[【免费】android和ios端应用性能的测试工具资源-CSDN文库](https://download.csdn.net/download/weixin_40895135/89786960)





1. 工具说明
   本工具无侵入，低延迟，可以测试游戏，视频，普通应用的性能数据，数据精准，目前支持数据录制，可测试android和ios两个端，小程序暂时不支持。ios17及以上暂时不支持
   到tool文件目录里下载解压
   
   

   提示 ：工具包需要放在不含中文目录里使用

![d271ae5e-c85b-48d6-82aa-0a6c7f409e29](D:\Study\sdk\性能\test\JinDouYun\images\d271ae5e-c85b-48d6-82aa-0a6c7f409e29.png)



3. 原理说明
   android 采用的是systrace与adb
   ios 是 instrment

4. 数据视图展示
   android端（以王者为例）：
   
   

   ![5e92f7e8-8062-4825-8e3b-be6549716438](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/5e92f7e8-8062-4825-8e3b-be6549716438.png)
    ![loading-ag-145](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/2cba49f9-51fb-407f-a309-1a727470d00c.png)

   ![loading-ag-147](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/47e98ace-69fc-4874-b75d-9a971d80f7f6.png)

   ![loading-ag-149](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/0a88301f-b9ea-4df6-b16b-5d65f9e3cf3d.png)

   ![loading-ag-151](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/7916f935-f7a0-49af-ae1d-5db2e8ebcfbf.png)





   ios端(以一款ios游戏为例)：

![loading-ag-153](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/7b2bd50a-8ab1-4db0-9150-b3af91f646df.png)



![loading-ag-155](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/689b24a9-3152-4fe1-9365-dc915b0d9574.png)

        ![loading-ag-157](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/7b5beb10-d51b-4fd3-86bf-879040f09419.png)

![loading-ag-159](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/3b1a0d82-12fb-434c-8147-2bba13deb22b.png)

4. 功能说明
      ![39c10ed6-4597-4df4-b713-b09e46c80cb0](file:///D:/Study/sdk/%E6%80%A7%E8%83%BD/test/JinDouYun/images/39c10ed6-4597-4df4-b713-b09e46c80cb0.png)
   
   

   提示：测试目标应用时，关闭其他应用，避免提示消息的影响



6. 感谢
   [YueChen-C/py-ios-device: IOS Professional Performance Testing Tool . You can get CPU, GPU, Memory , Lifecycle and other metrics from real iOS devices . iOS 性能测试工具 (github.com)](https://github.com/YueChen-C/py-ios-device)
   [alibaba/tidevice: tidevice can be used to communicate with iPhone device (github.com)](https://github.com/alibaba/tidevice)
