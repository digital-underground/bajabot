# Start servers to interact with bajabot

  docker-compose up

# Send message to bajabot

  curl --request POST \
  --url http://localhost:5005/webhooks/rest/webhook \
  --header 'content-type: application/json' \
  --data '{
    "message": "hello"
  }'