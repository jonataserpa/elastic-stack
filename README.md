## ELASTIC STACK

Commands:
    - sudo chown -R 1000:1000 ./elasticsearch_data
    - sudo chmod -R 770 ./elasticsearch_data
    - chmod go-w ./beats/metric/metricbeat.yml
    - sudo chown 1000:1000 ./beats/metric/metricbeat.yml
    - chmod go-w ./beats/heartbeat/heartbeat.yml
    - sudo chown 1000:1000 ./beats/heartbeat/heartbeat.yml
    - chmod go-w ./apm/apm-server.yml
    - sudo chown 1000:1000 ./apm/apm-server.yml
