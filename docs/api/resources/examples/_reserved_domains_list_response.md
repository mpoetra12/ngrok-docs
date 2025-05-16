<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2xAo153xNeBbnAXTIfNbQ0Xr0kA",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2xAo153xNeBbnAXTIfNbQ0Xr0kA"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.5vxm67rgf4tkfa5uv.local-ngrok-cname.com",
      "created_at": "2025-05-16T10:07:00Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xAo1DTkTOCi5eU8VQKSVHbmCMq",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xAo1DTkTOCi5eU8VQKSVHbmCMq"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-05-16T10:07:01Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.5vxm67rgf4tkfa5uv.local-ngrok-cname.com",
      "created_at": "2025-05-16T10:07:01Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xAo1BeU83N8rkPP3H54IT99fap",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xAo1BeU83N8rkPP3H54IT99fap"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
