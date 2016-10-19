# DockerParseyAPI

Dockerfile for 
https://github.com/dsindex/syntaxnet/blob/master/README_api.md



docker-compose up

Will build a version of parsey mcparseface with patches to expose protobuffers   
service will fire up on 0.0.0.0:9000


#OSX - Client
```
brew install node 
npm install grpc
```

```
cd clients   
cd node_client   
npm install   
```

Run it with the client (note: the server address 0.0.0.0:9000 is hard-coded into the client.  Edit as necessary.
```
cd parsey_client
node index.js
```


TODO - add sample ios swift project
https://github.com/apple/swift-protobuf
