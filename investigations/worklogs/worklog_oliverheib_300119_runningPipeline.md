# running pipeline

```
./logstash -f <log/file/path>--config.reload.automatic
```
This runs logstash and auto reloads the config file at the giver path. Running this without the -f agument will run logstash with the congigurations set in pipelines.yml where you can set multiple pipeline configs to run at once.

```
./filebeat -e -c filebeat.yml -d "publish"
```
This runs file beat with -d loading the dashboard for kibana, -e desabaling syslog output and -c specifying the confiuration file (filebeat.yml).
