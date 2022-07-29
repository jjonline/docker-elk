# docker-elk

基于`docker compose`的docker下三节点`ELK`集群套件，仅用于开发环境。

## 目录结构

````
.
├── README.md
├── config
│     ├── elasticsearch.yml c   ES配置
│     ├── kibana.yml           kibana配置
│     ├── logstash.yml         logstash配置
│     └── pipeline             logstash的流水线配置目录
│         └── logstash.conf
├── docker-compose.yaml
└── logstash
    └── pipeline
````
