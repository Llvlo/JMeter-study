性能测试的步骤

1. [下载](http://jmeter.apache.org/download_jmeter.cgi)

选择Binaries的zip
![image](https://github.com/user-attachments/assets/2393236f-7b39-4310-8b7c-cad004f24444)

2. 双击**bin**目录下的**jmeter.bat**文件启动
![image](https://github.com/user-attachments/assets/5cdd972b-6ce8-45fe-87fe-84c54e8f2b26)

3. 添加线程组

   右键**test plan**然后**add**》**threads** 》**threads group**
   ![image](https://github.com/user-attachments/assets/c5ab69e0-4e51-48a7-bc3a-4aaeb67b94e0)

   对话框内的各个解释
   ![image](https://github.com/user-attachments/assets/81f9ef30-c417-4da6-9282-dcf132eb1fa6)

   * **Number of Threads (users):** 线程数量
   * **Ramp-up period (seconds):** 全部线程启动总时长
   * **Loop Count:** 循环次数

4. 添加HTTP请求
   * 右键刚刚添加的线程组**add**》**sampler**》**Http Request**
   ![image](https://github.com/user-attachments/assets/00e02d30-3a96-47b7-8eac-484a8aa8b8f5)
5. 添加察看结果树
   * ![image](https://github.com/user-attachments/assets/c89d72f6-6ae0-4a67-a67d-b4f35096e239)
   * ![image](https://github.com/user-attachments/assets/434ad928-32c6-430d-a016-1816fe2921ad)


   

