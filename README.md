# node-object-hash
A node server to wrap and expose object-hash. This includes a docker-compose.yml file for easy stand-up. Make sure to `npm install` so you have the dependencies. If your host system does not have npm and you do not want to install it, you can use `docker-compose run npm_install`.

You can verify that it is running by curling against it: `curl 127.0.0.1/?obj_to_hash=test`
