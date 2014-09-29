
## install redis-cli

http://stackoverflow.com/questions/21795340/linux-install-redis-cli-only

```
git clone git@github.com:antirez/redis.git
cd redis/src
git checkout origin/2.8
make redis-cli
cp ./redis-cli /usr/local/bin
```
