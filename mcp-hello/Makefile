BINARY_NAME=mcp-go-hello

build:
	GOARCH=arm64 GOOS=darwin go build -o ../bin/mcp-hello/${BINARY_NAME} main.go
	GOARCH=amd64 GOOS=linux go build -o ../bin/mcp-hello/${BINARY_NAME}-linux-amd64 main.go
	GOARCH=amd64 GOOS=linux go build -o ../bin/mcp-hello/${BINARY_NAME}-linux-arm64 main.go

clean:
	go clean
	rm ../bin/mcp-hello/${BINARY_NAME}
	rm ../bin/mcp-hello/${BINARY_NAME}-linux-amd64
	rm ../bin/mcp-hello/${BINARY_NAME}-linux-arm64
