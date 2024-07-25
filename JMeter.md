性能测试的步骤

1. [下载](http://jmeter.apache.org/download_jmeter.cgi)

选择Binaries的zip

2. 双击**bin**目录下的**jmeter.bat**文件启动

3. 添加线程组

   右键**test plan**然后**add**》**threads** 》**threads group**

   对话框内的各个解释

   * **Number of Threads (users):** 线程数量
   * **Ramp-up period (seconds):** 全部线程启动总时长
   * **Loop Count:** 循环次数

4. 添加HTTP请求

   右键刚刚添加的线程组**add**》**sampler**》**Http Request**

   然后：

   ![http请求编写](C:\Users\Administrator\Desktop\JMeter的使用\http请求编写.jpg)

5. 添加察看结果树

   

