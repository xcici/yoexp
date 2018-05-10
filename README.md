本项目关注网络性能监视，告警及日志分析。

使用 influxdata telegraf 和 collectd 作为数据采集引擎，完成数据采集
实现一个web UI对上述软件进行图形化配置

采集结果作为对网络设备和主机的性能及状态监视依据，然后在web ui上作可视化呈现，包含用D3实现的拓扑

web后台采用golang开发，前端使用jquery+boostrap及adminLTE风格
性能数据保存在influxdb中，配置数据库使用SQLite3，可移植到嵌入式系统。
