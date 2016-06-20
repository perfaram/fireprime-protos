# fireprime-protos
FirePrime license protobuf definition files

## How to compile ?
`protoc FILE.proto --LANGUAGE_out=../` with : 
* `FILE.proto` being the protobuf definition you want to compile, and 
* `LANGUAGE` the language you're targeting (for Objective-C, use `objc_out`)
