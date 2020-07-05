FROM confluentinc/cp-kafka-connect:5.5.1
ENV CONNECT_PLUGIN_PATH="/usr/share/java,/usr/share/confluent-hub-components"
RUN confluent-hub install confluentinc/kafka-connect-mqtt:1.2.4 --no-prompt