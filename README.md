# gPRC for openapitools

API flow for raiseing, tracking and getting specific information regaring the issue raised and order related to that issue.

## Overview
These files were generated by the [OpenAPI Generator](https://openapi-generator.tech) project.

- API version: 1.0.0
- Package version: 
- Build package: org.openapitools.codegen.languages.ProtobufSchemaCodegen

## Usage

Below are some usage examples for Go and Ruby. For other languages, please refer to https://grpc.io/docs/quickstart/.

### Go
```
# assuming `protoc-gen-go` has been installed with `go get -u github.com/golang/protobuf/protoc-gen-go`
mkdir /var/tmp/go/
protoc --go_out=/var/tmp/go/ services/*
protoc --go_out=/var/tmp/go/ models/*
```

### Ruby
```
# assuming `grpc_tools_ruby_protoc` has been installed via `gem install grpc-tools`
RUBY_OUTPUT_DIR="/var/tmp/ruby/openapitools"
mkdir $RUBY_OUTPUT_DIR
grpc_tools_ruby_protoc --ruby_out=$RUBY_OUTPUT_DIR --grpc_out=$RUBY_OUTPUT_DIR/lib services/*
grpc_tools_ruby_protoc --ruby_out=$RUBY_OUTPUT_DIR --grpc_out=$RUBY_OUTPUT_DIR/lib models/*
```
