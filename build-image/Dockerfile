FROM fhueske/flink-sql-client:1.7.2

COPY training-config.yaml /opt/sql-client/conf/config.yaml

COPY sql-udfs/target/sql-udfs-1.0-SNAPSHOT.jar /opt/sql-client/lib/

COPY taxi-drivers.txt.tgz /opt/data/kafka/taxi-drivers.txt.tgz

COPY fares.txt.tgz /opt/data/kafka/fares.txt.tgz

COPY rides.txt.tgz /opt/data/kafka/rides.txt.tgz

