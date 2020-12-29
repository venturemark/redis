# redis

Redis deployment for kubernetes. The redis sentinel setup configured here is
managed using https://github.com/spotahome/redis-operator.

```
helm -n infra install redis-operator ./hlm/redis-operator/
```

```
helm -n infra install redis-failover ./hlm/redis-failover/
```
