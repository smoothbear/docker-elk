# Elastic stack (ELK) on Docker

[![Elastic Stack version](https://img.shields.io/badge/Elastic%20Stack-7.11.2-00bfb3?style=flat&logo=elastic-stack)](https://www.elastic.co/blog/category/releases)
[![CI](https://github.com/smoothbear/docker-elk/actions/workflows/ci.yml/badge.svg)](https://github.com/smoothbear/docker-elk/actions/workflows/ci.yml)

Run the latest version of the [Elastic stack][elk-stack] with Docker and Docker Compose.

It gives you the ability to analyze any data set by using the searching/aggregation capabilities of Elasticsearch and
the visualization power of Kibana.

*:information_source: The Docker images backing this stack include [X-Pack][xpack] with [paid features][paid-features]
enabled by default (see [How to disable paid features](#how-to-disable-paid-features) to disable them). **The [trial
license][trial-license] is valid for 30 days**. After this license expires, you can continue using the free features
seamlessly, without losing any data.*

Based on the official Docker images from Elastic:

* [Elasticsearch](https://github.com/elastic/elasticsearch/tree/master/distribution/docker)
* [Logstash](https://github.com/elastic/logstash/tree/master/docker)
* [Kibana](https://github.com/elastic/kibana/tree/master/src/dev/build/tasks/os_packages/docker_generator)
