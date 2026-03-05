


The server returns Content-Type: text/turtle, meaning the resource is served as Turtle RDF.
The header Vary: Accept-Encoding indicates that the response may vary depending on compression methods (e.g., gzip).
However, GitHub Pages does not implement full content negotiation based on the Accept header, since it serves static files.