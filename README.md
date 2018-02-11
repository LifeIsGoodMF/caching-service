# caching-service
he service gets HTTP requests for movie info by rank in IMDb (loaded from file), checks the Redis cache first, and serves the data found in the cache. If the cache does not have the data, it will fetch the data from the mongo database, and then update the cache.
