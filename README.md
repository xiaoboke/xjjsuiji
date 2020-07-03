# kuaishouXJJ
随机播放,带视频源库,此库长期更新

## 1.搭建


php空间即可,无需数据库,视频源在ks.txt


### 2.演示

* [https://ssl-xiaoboke.cloud.okteto.net/](https://ssl-xiaoboke.cloud.okteto.net/)

### 3.视频源的获取
  
  * 方法1:下载本项目的ks.txt(更新时间较长)
  * 方法2:直接从服务器下载:[https://ssl-xiaoboke.cloud.okteto.net/ks.txt](https://ssl-xiaoboke.cloud.okteto.net/ks.txt)
  * 方法3:更直接的使用:https://ssl-xiaoboke.cloud.okteto.net/video.php
     ```
     <video id="player" src="https://ssl-xiaoboke.cloud.okteto.net/video.php" controls webkit-playsinline playsinline></video>
     ```
 
 ### 3.视频源解析+列表更新

  如果想自己解析视频源,接口在这里: [https://ssl-xiaoboke.cloud.okteto.net/geturl/api/](https://ssl-xiaoboke.cloud.okteto.net/geturl/api/)
  
  但是解析结果会被记录,并更定期新到本项目的ks.txt
  
  所以本项目的播放列表是**不断更新**的
