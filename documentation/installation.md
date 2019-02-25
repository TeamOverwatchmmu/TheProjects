# Installation

## Install Elk Stack
Download Elasicsearch, Logstash, Kibana and 2 filebeat installs

Current filepaths setup to read logs form the bootdrive.

## Install log files
files to install

### Filebeat Apache access configs
files in [/configs/filebeat/apache/access](https://github.com/TeamOverwatchmmu/TheProjects/tree/master/configs/filebeat/apache/access)
```
filebeat/
├── filebeat.yml
└── fields.yml
```

## Filebeat Apache error configs
files in [/configs/filebeat/apache/error](https://github.com/TeamOverwatchmmu/TheProjects/tree/master/configs/filebeat/apache/error)
```
filebeat/
├── filebeat.yml
└── fields.yml
```

## Logstash
```
logstash/
└── configs/
    ├── apache-error-pipeline.conf
    ├── apache-pipeline.conf
    └── pipelines.yml
```
