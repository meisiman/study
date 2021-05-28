## grpc golang准备工作

1、安装protoc

```
https://github.com/protocolbuffers/protobuf/releases/tag/v3.17.0
```

2、安装protoc-gen-go

```
go get -u github.com/golang/protobuf/protoc-gen-go
```

3、安装grpc

```
go get google.golang.org/grpc
```

4、生成*.pb.go文件

```
protoc.exe --go_out=plugins=grpc:. add.proto
```
