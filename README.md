# Velopark Open API documentation
API documentation for Velopark bicycle parkings using Open API v3.0.2. It is served using a bundle of [`http-server`](https://github.com/http-party/http-server).

## Install it

Clone this repository and run `npm install` on the cloned folder.

## Run it

Run it using the following command inside the cloned folder:

```bash
node bin/http-server -p PORT ./docs/
```

The `PORT` parameter is the TCP port where the HTTP server will listen for requests. The default is 8080. Once run, you can access it on:

```http
http://localhost:PORT/
```
