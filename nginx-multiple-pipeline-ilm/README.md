## Step-by-step

1. Start Elasticsearch
1. Import ILM policy
1. Import templates
1. Start Logstash
  1. Create initial write index
1. Start Filebeat

## File location

- /etc/logstash/pipeline.yml
- /etc/logstash/conf.d/access.conf
- /etc/logstash/conf.d/beats.conf
- /etc/logstash/conf.d/error.conf
- /etc/filebeat/filebeat.yml

## Elasticsearch 

- es-template-access.json
- es-template-error.json
- ilm-policy.json
