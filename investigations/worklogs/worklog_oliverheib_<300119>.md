# running pipeline

```
/logstash -f <log/file/path>--config.reload.automatic
```
This runs logstash and auto reloads the config file at the giver path.

```
./filebeat -e -c filebeat.yml -d "publish"
```
This runs file beat with -d loading the dashboard for kibana, -e desabaling syslog output and -c specifying the confiuration file (filebeat.yml).
