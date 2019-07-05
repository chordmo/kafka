
    cd kafka_source_dir
    gradle
    ./gradlew eclipse
    
    # ./gradlew idea

### Build a jar and run it ###
    ./gradlew jar

### Installing the jars to the local Maven repository ###
    ./gradlew installAll

### Eclipse import Kafka project ###
    import -> git -> kafka.git project
    
    

Debug As -> Debug Configurations

Scala Application

Main:

project:
Core

Main class:
kafka.Kafka

Arguments:

Program arguments:
/Users/m/code/bigdata/kafka/kafka/config/server.properties

VM arguments:
-Dkafka.logs.dir=/stock/logs/kafka




