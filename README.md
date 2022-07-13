live
======

livego_docker 作为直播的推流服务端，然后用 **flvjs** 作网页播放的适配，最后在页面右边做一个在线即时通(计划用go)

## 部署

### livego

采用 docker-compose 来自动化部署 livego_docker，该项目源码 [点此](https://github.com/gwuhaolin/livego)，

在 docker-compose 中可以自定义端口映射，其中主要是 **7001(FLV拉流)**，**1935(直播推流)**，**8090(获取直播key)** 三个端口