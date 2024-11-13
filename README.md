# gRPC-tonic

gRPC server/client with tonic lib

## Hello World

```
grpcurl -plaintext -import-path ./proto -proto helloworld.proto -d '{"name": "Tonic"}' '[::1]:50051' helloworld.Greeter/SayHello
```
