###DevEnv 是一款全功能的 Docker 开发环境###



**可选配的常用服务：**

- 多PHP版本：PHP5.4、PHP5.6、PHP7.1-7.3
- Web服务：Nginx、Openresty
- 数据库：MySQL5、MySQL8、Redis、memcached、MongoDB
- 消息队列：RabbitMQ
- 辅助工具：phpMyAdmin、phpRedisAdmin、AdminMongo
- 可观测性：ElasticSearch、Logstash、Kibana、Prometheus、Grafana、Jaeger
- 其他：etcd



**使用方法：**

先复制配置文件

```sh
cp docker-compose.sample.yml docker-compose.yml
cp env.sample .env
```
按需调整配置后即可启动
```sh
docker-compose up -d
```



参考项目：[dnmp](https://github.com/yeszao/dnmp), [gonivinck](https://github.com/nivin-studio/gonivinck)
