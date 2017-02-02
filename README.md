# Elasticsearch, Logstash, Kibana (ELK) Docker image

### Freebird specific
* Elasticsearch ONLY
* This app has cpu and memory requirements which are set in `docker-compose.yml`
* This app requires an update to the host system's `vm.max_map_count`. If it's not already set, `convox rack params set 'InstanceBootCommand="sysctl -w vm.max_map_count=262144"'``

---

### Documentation

See the [ELK Docker image documentation web page](http://elk-docker.readthedocs.io/) for complete instructions on how to use this image.

### Docker Hub

This image is hosted on Docker Hub at [https://hub.docker.com/r/sebp/elk/](https://hub.docker.com/r/sebp/elk/).

### About

Written by [Sébastien Pujadas](https://pujadas.net), released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).
