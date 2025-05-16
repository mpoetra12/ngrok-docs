<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-16T10:07:22Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2xAo3DEOHIMlrhro5OfX9z9FQxC",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xAo3DEOHIMlrhro5OfX9z9FQxC"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xAo3nlaAE3EcDABrerm4J3ySuS",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-16T10:07:22Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2xAo3nlaAE3EcDABrerm4J3ySuS",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-16T10:07:20Z",
      "hostport": "4113f2c5de6f.ngrok.paid:443",
      "id": "ep_2xAo3aJaQdPu6uTxg8zNuAcn1tF",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2xAo19iRmJJEaTYeYsvjbECtN5W",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://4113f2c5de6f.ngrok.paid",
      "tunnel": {
        "id": "tn_2xAo3aJaQdPu6uTxg8zNuAcn1tF",
        "uri": "https://api.ngrok.com/tunnels/tn_2xAo3aJaQdPu6uTxg8zNuAcn1tF"
      },
      "tunnel_session": {
        "id": "ts_2xAo3csD7Mg1oYThsMi0rYlvgmA",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2xAo3csD7Mg1oYThsMi0rYlvgmA"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-16T10:07:20Z",
      "upstream_url": "http://localhost:80",
      "url": "https://4113f2c5de6f.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-16T10:07:17Z",
      "domain": {
        "id": "rd_2xAo3DEOHIMlrhro5OfX9z9FQxC",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xAo3DEOHIMlrhro5OfX9z9FQxC"
      },
      "edge": {
        "id": "edgtls_2xAo3Di4iQ0eVy32Ilgzre9ctg5",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2xAo3Di4iQ0eVy32Ilgzre9ctg5"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xAo3FzEp2dGTsJ1kK8yyYkDW4S",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-16T10:07:17Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
