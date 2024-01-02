# Server(Rust)
## API
* GraphQL
* REST API(axum)
* gRPC(tonic)

## Middleware
* Kafka(MQ)
* Nginx(proxy)


# Database
* PostgreSQL
  * HA(replica)
  * SSL
* MongoDB
  * HA(replica)
  * SSL 
* Redis
  * HA(replica)
  * SSL 

# DevOps
* **Infrastructure**
* **Log Management**
  * Elastic search, Fluentd, Kibana 
* **Monitoring**
  * **Application Performance Monitoring(APM)**: CPU usage, Mem usage, response times, error rates, requests, uptime, the number of instances, transaction tracing  
    * Prometheus, Grafana
  * **Universal Service Monitoring**: Automatically discover all 1st and 3rd party services and their dependencies Monitor real-time performance metrics of every service in one place
  * **Database Monitoring**: Surface slow performing queries
  * **Network Monitoring**: Monitor devices and traffic flows for complete network visibility
* **Observability Pipelines**
  * Collect, transform, and route observability data to any destination at petabyte scale
* **Incident Management**
* **Continuous Testing** & **CI Visibility**
  * Monitor the health and performance of your CI pipelines and tests





# Candidates
## Web Framework
1. actix-web
2. axum

## API
1. REST API (+ Polling, Long Polling, WebSocket, Server-Sent Events)
2. GraphQL
3. gRPC

## DB
1. **PostgreSQL**, MySQL (SQL)
2. MongoDB (noSQL)
3. Redis (In-memory KV store)

## Middleware
1. GraphQL APIs on DB : Hasura
2. Message Broker : **Kafka**, Pulsar, RabbitMQ (Message broker)
3. Service Mesh : istio, linkerd

## DevOps
1. Packer
2. Terraform (Provisioning cloud infrastructure)
3. Ansible (Automation - configuration management tool for deploying application)
4. Kubernetes
5. Docker
6. Prometheus + Grafana (Monitoring)
7. Elasticsearch + Fluentd + Kibana (Logging)
8. Apache Airflow (workflow management for data engineering pipelines)
