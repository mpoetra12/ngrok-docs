<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"temporary access to staging machine","principals":["ec2-user","root"],"public_key":"ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBK58lFzmWlDimDtBz78wVT4oauA8PjY0CiXTCEIsBNC6UwOJvZ0jdSaYNhDaa7dRV84DfBb/gKzqlXC7cVMZjl0= alan@work-laptop","ssh_certificate_authority_id":"sshca_2xAo42LCQ7aZYER7VBkRiQy0Mpo","valid_until":"2025-08-14T10:07:23Z"}' \
https://api.ngrok.com/ssh_user_certificates
```
