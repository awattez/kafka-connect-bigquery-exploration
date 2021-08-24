FROM confluentinc/cp-kafka-connect-base:6.1.1

ARG BIGQUERY_VERSION=2.1.0
ARG DATAGEN_VERSION=0.4.0


RUN confluent-hub install --no-prompt wepay/kafka-connect-bigquery:$BIGQUERY_VERSION
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-datagen:$DATAGEN_VERSION
