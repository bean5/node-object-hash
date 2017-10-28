# node-object-hash
A node server to wrap and expose [object-hash](https://github.com/puleos/object-hash). This includes a docker-compose.yml file for easy stand-up.

# Set up: Gather depencencies
If you do have npm installed: `npm install`.
If you don't have npm installed: `docker-compose run npm_install`

# Standing up
`docker-compose up -d node_object_hash`

# Testing
You can verify that it is running by curling against it: `curl 127.0.0.1/?obj_to_hash=test`
