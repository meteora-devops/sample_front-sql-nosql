- open http://localhost/
- in order to check availability:
```
docker exec -it web-dev bash
ping mysql-dev
ping redis-dev
```

# Why Redis?

Redis is an open-source and Berkeley Software Distribution (BSD) licensed platform. It serves as a memory data structure storage solution and is often used as a database, cache, and message broker. Redis can support data structures including elements like strings, hashes, sorted sets, range queries, bitmaps, hyperlogs, geospatial indexes, lists, sets, and streams.

- Redis operates as an in-memory database for faster performance. This makes it a great choice for building complicated data structures quickly.
- The speed and efficiency of Redis are very high in case of higher latency throughputs.
