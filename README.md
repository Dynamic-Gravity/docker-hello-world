```
# run command example
docker run \
  -e "NODE_ENV=production" \
  -p 49160:8080
  -u "node" \
  -m "300M" --memory-swap "1G" \
  -w "/home/node/app" \
  --name "my-nodejs-app" \
  node [script]
```