# elk_services
systemd services for Elasticsearch, Logstash, Kibana

Place these files in /usr/lib/systemd/system/

Works on CentOs


### Tips:
`systemctl daemon-reload`  Restart systemctl daemon   
`systemctl start elasticsearch logstash kibana` Start services  
`systemctl enable elasticsearch logstash kibana`  Make services start after machine reload   

`systemctl status elasticsearch logstash kibana`  Check if everything is correct  
`journalctl -u elasticsearch/logstash/kibana`
