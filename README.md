# 项目介绍：明光筑梦儿童端子系统

## 技术栈
该项目是一个完整的前后端分离项目，采用了以下技术栈：
- 前端：Vue.js 框架、element-ui 组件库
- 后端：Spring Boot、MyBatis Plus
- 数据库：MySQL，实现了主从复制和读写分离
- 数据库连接池：Druid
- 对象存储服务：Minio

## 主要功能

1. **需求分析和数据库设计**
   - 参与需求分析和数据库设计，负责儿童端表和与志愿者端协同的表的设计与沟通。
   - 将数据库部署在阿里云服务器上，实现了主从复制和读写分离，确保数据库的一致性和相同的数据状态。
   - 集成和配置了 Druid 数据源的监控功能，方便监控和管理数据库连接池的状态和运行情况。

2. **任务管理**
   - 儿童能够查看任务列表、任务详情和任务完成情况，支持搜索或筛选任务，提交任务，并支持讲解视频的播放和进度调整。
   - 集成 Minio 对象存储服务，实现文件的上传、存储和下载功能，具备良好的可扩展性和性能。

3. **积分与兑换**
   - 儿童能够查看加分明细，可兑换物品，使用积分兑换物品，并查看兑换物品记录和订单进程等。
   - 儿童也可以与志愿者进行互动聊天。

4. **应用程序监控**
   - 使用日志框架 Log4j 和 Slf4j 进行应用程序监控，记录系统运行日志以便排查问题。
