# Kafka console

## Indien console tools geinstalleerd zijn

```sh
kafka-console-producer --topic 'default' --broker-list localhost:9092

# <stuur berichtjes, gescheiden met newlines>

kafka-console-consumer --bootstrap-server localhost:9092 --topic 'default' --from-beginning
```

