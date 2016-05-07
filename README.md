#MemcacheQ - Simple Queue Service over Memcache

detail : [http://memcachedb.org/memcacheq/](http://memcachedb.org/memcacheq/)

**Version**

0.2.0     [Dockerfile](https://github.com/wupeng1988/docker-memcacheq/blob/master/Dockerfile)
latest     [Dockerfile](https://github.com/wupeng1988/docker-memcacheq/blob/master/Dockerfile)

**Usage**

  docker run -d -p 22201:22201 --name memcacheq wupeng/memcacheq:0.2.0
  
**Store Data**

  docker run -d -p 22201:22201 --name memcacheq -v /my-data-dir:/home/mcq-data wupeng/memcacheq:0.2.0
  
  
