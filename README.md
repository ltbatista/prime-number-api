
# prime-number-api

A prime number decomposition API that uses Server Streaming gRPC framework.

  

#

### To execute

First initialize the Server

```

go run prime/prime_server/server.go

```

After, execute the client passing two arguments as below

```

go run prime/prime_client/client.go 720

```

The code above will return the following responses:
>Hello, i'm a client
Starting Prime Request RPC...
2021/12/25 21:02:47 Response from Prime Decomposition: 2
2021/12/25 21:02:48 Response from Prime Decomposition: 2
2021/12/25 21:02:49 Response from Prime Decomposition: 2
2021/12/25 21:02:50 Response from Prime Decomposition: 2
2021/12/25 21:02:51 Response from Prime Decomposition: 3
2021/12/25 21:02:52 Response from Prime Decomposition: 3
2021/12/25 21:02:53 Response from Prime Decomposition: 5
2021/12/25 21:02:54 End.
#

### Requirements

[![Stable release](https://img.shields.io/badge/libprotoc-3.17.3-green.svg)](https://github.com/protocolbuffers/protobuf/releases/tag/v3.17.3)

[![Stable release](https://img.shields.io/badge/golang-v1.17.5-blue.svg)](https://go.dev/doc/go1.17)