# https://pikajojo.github.io/Knowledge_Graph_UGent_Lab2/data.ttl


# Command
curl -I https://pikajojo.github.io/Knowledge_Graph_UGent_Lab2/data.ttl


# Output of Command
HTTP/2 200 
server: GitHub.com
content-type: text/turtle; charset=utf-8
last-modified: Wed, 04 Mar 2026 18:12:39 GMT
access-control-allow-origin: *
strict-transport-security: max-age=31556952
etag: "69a87617-2db"
expires: Thu, 05 Mar 2026 08:04:17 GMT
cache-control: max-age=600
x-proxy-cache: MISS
x-github-request-id: 5016:27B4C6:CAE9B6:CDA4EE:69A936A8
accept-ranges: bytes
age: 0
date: Thu, 05 Mar 2026 07:54:17 GMT
via: 1.1 varnish
x-served-by: cache-bru1480038-BRU
x-cache: MISS
x-cache-hits: 0
x-timer: S1772697257.355912,VS0,VE131
vary: Accept-Encoding
x-fastly-request-id: f4a54748bced04cb8a7524a36590d17569298ede
content-length: 731

# Comments
The server returns **Content-Type: text/turtle**, meaning the resource is served as Turtle RDF.

The **header Vary: Accept-Encoding** indicates that the response may vary depending on compression methods (e.g., gzip).

However, GitHub Pages does not implement full content negotiation based on the Accept header, since it serves static files.

**cache-control: max-age=600** means that the response will be kept in cache for 10 mins.

**access-control-allow-origin: * /** indicates that any other web can visit and fetch the my RDF data, which is important because the idea of Linked data is that data should be reusable across the web.

**strict-transport-security: max-age=31556952** shows that this web can only be visited through HTTPS for one year, which also aligns with the W3C Linked Data best practice to use HTTPS URIs for identifiers in order to keep the integrity of the data.


