# kafka-spring-boot
Demo Spring boot project to connect with kafka  (producer and consumer ) on docker.

# Command to create topic
docker-compose exec kafka kafka-topics --create --bootstrap-server \localhost:9092 --replication-factor 1 --partitions 1 --topic trino

# comamnd to check running docker
docker ps

# command to check list of topics
docker-compose exec kafka kafka-topics --bootstrap-server kafka:29092 --list
