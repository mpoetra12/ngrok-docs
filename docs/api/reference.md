curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 1" \
-d '{"bindings":["public"],"description",:"{\"environment\": \"staging\"}","{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":}}]}]}","type":"cloud","url":"https://endpoint-example.com:"}' \
https://api.ngrok.com/
