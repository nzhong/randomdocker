```
docker build --no-cache -t openresty-lua-t1 .
docker run -p 8080:8080 --name openresty-lua-t1 openresty-lua-t1
```