# Airflow-ELK
Docker Compose For Apache Airflow With ELK Stack For Logging

## airflow.cfg Changes

### Logging Section
- `remote_logging` changed from `False` to `True`

### WebServer Section
- `log_fetch_delay_sec` changed from `2` to `10`

### ElasticSearch  Section
- `host` set to `http://elasticsearch:9200`
- `write_stdout` set to `False`
- `json_format` changed from `False` to `True`
