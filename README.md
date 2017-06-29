# study : kafka-spark
spark를 이용하여 kafka의 데이터를 가공한 뒤 kafka 적재

### 환경
* Scala (2.11)
* Spark (2.1.1, http://spark.apache.org/docs/latest)
* Kafka (0.10.2, Confluent version-3.2.2, http://docs.confluent.io/current)
* Json-generator (generate sample data, https://github.com/acesinc/json-data-generator)

### 기본 과제
* spark를 이용하여 kafka의 데이터를 가공한 뒤 kafka 적재

### 도전 과제
* kafka offset 관리 툴 개발
* influxDB(time series database)에 데이터 저장 후 chronograf로 확인 (https://www.influxdata.com/time-series-platform/)
* presto 등을 이용한 Kafka data query
