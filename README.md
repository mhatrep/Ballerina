# Ballerina
Ballerina Programming for Integration


## Generate Ballerina source code using the following command:
$ ./ballerina grpc --input <proto-file-path> [--output <path>] [--mode client | service]
  
## Generate the client/service stub and service template.
$ ballerina grpc --input helloworld_service.proto --mode service --output service

## Generate the client/service stub and client template.
$ ballerina grpc --input helloworld_service.proto --mode client --output client

## Generate only the client/service stub.
$ ballerina grpc --input helloworld_service.proto --output stubs
