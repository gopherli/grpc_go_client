# grpc_go_client
grpc_go_client

# 客户端使用说明
- 第一步：下载grpc包 go get google.golang.org/grpc
- 第二步：引入客户端包 
```
(1) go.mod 引入项目
require grpc_go v0.0.0

replace grpc_go => D:\CodingSpace\go_workspace\src\grpc_go
(2) 使用包的话需要在包后面加对应包名
pb "grpc_go/helloerdan"
```