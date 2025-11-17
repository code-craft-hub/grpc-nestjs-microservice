protoc --plugin=./node_modules/.bin/protoc-gen-ts_proto --ts_proto_out=./ --ts_proto_opt=nestJs=true ./proto/auth.proto


"proto:generate": "protoc --plugin=protoc-gen-ts_proto=\"node ./node_modules/.bin/protoc-gen-ts_proto\" --ts_proto_out=./src/proto --ts_proto_opt=nestJs=true ./proto/*.proto"
