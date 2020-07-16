FROM strimzi/kafka:0.16.1-kafka-2.4.0
USER root:root
RUN mkdir -p /opt/kafka/plugins/debezium
COPY ./plugins/debezium-connector-mysql/ /opt/kafka/plugins/debezium/
USER 1001