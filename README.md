# This is a trivial example of a Kafka consumer written in Golang

Based on Confluent's Go client library:

	https://github.com/confluentinc/confluent-kafka-go

# It starts off as a basic project with the Confluent client library:

	go mod init nextgened.com/kafka/consumer-example
	go get github.com/confluentinc/confluent-kafka-go/kafka

All of the significant code is in consumer.go, mostly derived from the example in the library:

# To execute, just "go run" the consumer.go:

	go run consumer.go
