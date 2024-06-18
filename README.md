#

```zsh

❯ protoc -I protobuf --go_out=./api --go-grpc_out=./api ./protobuf/common/common.proto
❯ protoc -I protobuf --go_out=./api --go-grpc_out=./api ./protobuf/user/address/address.proto
❯ protoc -I protobuf --go_out=./api --go-grpc_out=./api ./protobuf/user/photo/photo.proto
❯ protoc -I protobuf --go_out=./api --go-grpc_out=./api ./protobuf/user/user.proto

```
