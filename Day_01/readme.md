# Redis

Foobar is a Python library for dealing with word pluralization.

## Redis Installation For Windows

Enable WSL from "Turn Windows features on or off settings"

Restart the machine

Install Ubuntu20.04 from Windows Store

Open Ubuntu and setup name and password

### Run the following commands:

```bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install redis-server
sudo service redis-server restart
redis-cli
```

## Redis Installation For Linux


### Run the following commands:

```bash
sudo apt-get install redis-server
sudo service redis-server restart
redis-cli
```


## Usage

SET key value

GET key

ttl key

KEYS *

DEL key

FLUSHALL

EXISTS key

expire key time

setex key time value

### For Arrays

LPUSH array value

RPUSH array value

LRANGE array start stop

LPOP array

RPOP array

For Sets

### For Object/Hash
HSET key field value

HGET key field

HGETALL key

HDEL key field

HEXISTS key field