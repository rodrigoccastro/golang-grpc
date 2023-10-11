1. generate proto
protoc --go_out=. --go-grpc_out=. helloworld/helloworld.proto

2. infolder root
go mod init google.golang.org/grpc/examples
go mod tidy

3. execute in first terminal
go run greeter_server/main.go

4. execute in second terminal
go run greeter_client/main.go

