# http-redirect-server
Simple Flask server for redirecting HTTP to HTTPS.

Server sends redirect responses for HTTP (port 80) to HTTPS (port 443).
To run:

```
python3 run.py
```

By default, the server runs on port 80.
The server uses Gevent for concurrent connections.
