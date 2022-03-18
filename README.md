# grpc_training

https://qiita.com/tomo0/items/310d8ffe82749719e029

```
protoc --go_out=. --go_opt=paths=source_relative \
    --go-grpc_out=. --go-grpc_opt=paths=source_relative \
    proto/calc.proto
```
