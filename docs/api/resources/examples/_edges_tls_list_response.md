<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-16T10:07:28Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2xAo4dlHsE3YkkRkDkTCWMAFRTJ",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xAo4dlHsE3YkkRkDkTCWMAFRTJ"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2xAo3E2Dc8GpDEUix6wLDY9C85R",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2xAo3E2Dc8GpDEUix6wLDY9C85R"
        },
        "enabled": true
      },
      "created_at": "2025-05-16T10:07:17Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2xAo3Di4iQ0eVy32Ilgzre9ctg5",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xAo3Di4iQ0eVy32Ilgzre9ctg5"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
