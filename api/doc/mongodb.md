>  mongo 运行报错 ： [thread1] Failed to connect to 127.0.0.1:27017, reason: errno:111 Connection refused

    原因是mongodb的服务没有开启，开启服务后问题就能解决。
    开启服务命令： mongod --dbpath  /data/db(保存路径)

> node and mongo

> ubuntu 启动 mongo

/usr/bin/mongo

dbPath: /var/lib/mongodb

mongod --dbpath /var/lib/mongodb/





[官方教程](https://docs.mongodb.com/getting-started/node/client/)

[mongo自启动](http://www.cnblogs.com/hamy/p/3448051.html)

[ubuntu 配置mongo](http://blog.fens.me/linux-mongodb-install/)
