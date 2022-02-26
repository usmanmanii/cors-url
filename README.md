
**CORS Anywhere** is a NodeJS proxy which adds CORS headers to the proxied request.

The url to proxy is literally taken from the path, validated and proxied. The protocol
part of the proxied URI is optional, and defaults to "http". If port 443 is specified,
the protocol defaults to "https".
