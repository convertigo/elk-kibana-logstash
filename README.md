# elk-kibana-logstash
This repository holds sample configurations to integrate Convertigo with Elastic Search / Kibana / Logstash for log analysis and reports.

[image.png](https://postimg.cc/cghH59VW)

## How to install
This is using docker-compose so you need a docker environment with docker-compose to use this stack.

Docker runs on Linux or on Windows 10 WSL2 environments. Please refer to both environment documentation to setup your docker-compose.

## Sample configuration files

|Name                |  Usage
| ----               |------------------------------------------
| docker-compose.yml | The docker-compose definition stack for ELK including ELK, Kibana & Logstash
| docker-compose-c8o.yml | The docker compose definition for a complete Convertigo stack including Convertigo, CouchDB, MySQL for billing & filebeat to crunch and send logs to logstash.
| filbeat.yml | The filebeat configuration file
| logstash.conf | The logstash configuration file holding the GROK filters to parse Convertigo logs. 
| ConvertigoCanvas.json |A Convertigo Canvas sample to display various informations in Kabana Canvas.

