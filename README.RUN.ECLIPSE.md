
    cd kafka_source_dir
    gradle
    ./gradlew eclipse
    ./gradlew idea

### Build a jar and run it ###
    ./gradlew jar

### Installing the jars to the local Maven repository ###
    ./gradlew installAll

### Eclipse import Kafka project ###
    import -> Gradle -> Existing Gradle Project
