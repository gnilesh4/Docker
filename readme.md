# Docker

## ArangoDB

docker-compose -p arangodb -f arangodb.yml up --build -d

**Url:** http://localhost:8529

**Login:** root

**Password:** P4ssW0rd!

## CouchDB

docker-compose -p couchdb -f couchdb.yml up --build -d

**Url:** http://localhost:5984/_utils

**Login:** admin

**Password:** P4ssW0rd!

## CrateDB

docker-compose -p cratedb -f cratedb.yml up --build -d

**Url:** http://localhost:4200

## Elasticsearch

docker-compose -p elk -f elk.yml up --build -d

**Url Elasticsearch:** http://localhost:9200

**Url Kibana:** http://localhost:5601

## Grafana

docker-compose -p grafana -f grafana.yml up --build -d

**Url:** http://localhost:3000

**Login:** admin

**Password:** admin

## InfluxDB

docker-compose -p influxdb -f influxdb.yml up --build -d

**Url InfluxDB:** http://localhost:8086

**Url Chronograf:** http://localhost:8888

**Login:** admin

**Password:** P4ssW0rd!

## Jenkins

docker-compose -p jenkins -f jenkins.yml up --build -d

**Url:** http://localhost:8081

**Password:** docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword

## MongoDB

docker-compose -p mongo -f mongo.yml up --build -d

**Url:** http://localhost:8081

**Login:** admin

**Password:** P4ssW0rd!

## SQL Server

docker-compose -p mssql -f mssql.yml up --build -d

**Url:** http://localhost:1433

**Login:** sa

**Password:** P4ssW0rd!

## Neo4j

docker-compose -p neo4j -f neo4j.yml up --build -d

**Url:** http://localhost:7474

**Login:** neo4j

**Password:** neo4j

## PostgreSQL

docker-compose -p postgres -f postgres.yml up --build -d

**Url:** http://localhost:16543

**Login:** admin@admin.com

**Password:** P4ssW0rd!

## RabbitMQ

docker-compose -p rabbitmq -f rabbitmq.yml up --build -d

**Url:** http://localhost:15672

**Login:** admin

**Password:** P4ssW0rd!

## Redis

docker-compose -p redis -f redis.yml up --build -d

**Url:** http://localhost:6379

**Password:** P4ssW0rd!

## RethinkDB

docker-compose -p rethinkdb -f rethinkdb.yml up --build -d

**Url:** http://localhost:8080
