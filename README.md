# Build
docker build -t cannin/labelme .

# Run
```
docker rm -f labelme; docker run --name labelme -p 8081:80 -v DIR:/notebooks -t cannin/labelme

docker exec -i -t labelme bash
```

# Apache needs to be started
service apache2 restart

# URL
http://127.0.0.1:8081
