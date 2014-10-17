## ShareJS-Server
    
A ShareJS nodejs application using the Redis backend.

Note: The default http port is 4999 instead of 80. The sharejs port is 5000.


### Manually update old sharejs package.json to lock in versions

The coffee-script and browserchannel versions need to be set as well.

```
  "dependencies": {
    "socket.io": "~0.8",
    "socket.io-client": "~0.8",
    "connect": "~1",
    "optimist": ">= 0.2.4",
    "uglify-js": "~1",
    "request": ">= 2.1.1",
    "coffee-script": "1.5.0",
    "browserchannel": "1.0.0",
    "hat": "*"
  },
```
