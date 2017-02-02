# SimpleHttpCachedProxy
Simple implementation of a threaded Java http proxy server using Caffeine cache.

## Setup
Set a (maven) dependency to Caffeine cache (https://github.com/ben-manes/caffeine)

## Notes
Edit cache size modifying the initial maximum weight of the cache, currently the cache can hold up to 5 MB of data.
Each entry of the cache is weighed based on how many bytes it carries.
