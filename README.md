# Simulator

## Executar Aplicação

Para executar a aplicação.

```go
go run main.go
```

## Executar Producer

Após entrar no container, para executar o producer.

```kafka
kafka-console-producer --bootstrap-server=localhost:9092 --topic=route.new-direction
```

## Executar Consumer

Após entrar no container, para executar o consumer

```kafka
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=route.new-position --group=terminal
```
