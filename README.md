```
protoc.exe -I="." --java_out=gen --plugin=protoc-gen-grpc-java=protoc-gen-grpc-java.exe --grpc-java_out=gen --proto_path="." calculator.proto
```

```
protoc.exe -I="." --java_out=gen --plugin=protoc-gen-grpc-java=protoc-gen-grpc-java.exe --grpc-java_out=gen --proto_path="." streaming.proto
```

```
protoc.exe -I="." --java_out=gen --plugin=protoc-gen-grpc-java=protoc-gen-grpc-java.exe --grpc-java_out=gen --proto_path="." person.proto
```
