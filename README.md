# memcached + healthcheck

Standard memcache image, adding a healtcheck.

```
docker service create \
  --detach \
  --name memcached \
  --publish 11211:11211 \
  johnhwhite/memcached-healthcheck
```

