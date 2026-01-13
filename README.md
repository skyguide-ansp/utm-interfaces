## UTM Interfaces

this project contains interfaces for entities willing to interact with Skyguide UTM system.



## Item generation

From root folder:
protoc --proto_path=./api --go_out=./src/utm --go_opt=paths=source_relative --go-grpc_out=./src/utm --go-grpc_opt=paths=source_relative api/*.proto