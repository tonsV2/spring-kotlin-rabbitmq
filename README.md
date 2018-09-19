# Description
Simple RabbitMQ "Hello world" application using Spring Boot 2.0 with Kotlin

# Launch applications
```docker-compose up```

# Execute http request (using httpie)
```http POST :8080/person/john```

# Debug and development
Start the dependencies needed
- ```docker-compose up rabbit consumer```

Run module you which to develop/debug, possible using your favorite IDE
- ```./gradlew producer:bootRun```

The above is for working with the producer.
