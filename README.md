# docker-webmin
dockerfile for webmin

## Building the image
```
git clone https://github.com/chsliu/docker-webmin.git
cd docker-webmin
docker build -t chsliu/docker-webmin .
```

## Running the container
```
docker run -d -p 10000:10000 chsliu/docker-webmin
```

Log into webmin and manage your server
```
http://hostname.or.ip:10000
(root:pass)
```
