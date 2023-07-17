# Protocol buffer contracts

https://grpc.io/docs/protoc-installation/
https://grpc.io/docs/languages/go/quickstart/

## Format code
`clang-format -style=Google -i */*.proto`

## Generate code
`protoc --go_out=. --go_opt=paths=source_relative  --go-grpc_out=. --go-grpc_opt=paths=source_relative foo/foo.proto`  
`protoc --go_out=. --go_opt=paths=source_relative  --go-grpc_out=. --go-grpc_opt=paths=source_relative bar/bar.proto`
