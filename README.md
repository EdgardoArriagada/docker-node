```
# build
docker build -t feedback-node .

# run
docker run -p80:80 --name feedback-app --rm -v feedback:/app/feedback -v "$(pwd):/app" -v /app/node_modules feedback-node
```
