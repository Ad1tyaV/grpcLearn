Learning gRPC - https://www.tutorialspoint.com/grpc/grpc_helloworld_app_with_python.htm


Command to generate files:
```
python -m grpc_tools.protoc -I ..\common_proto_files\ --python_out=../python --grpc_python_out=. greeting.proto
```