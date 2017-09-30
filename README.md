# mongodb-mongoose
(1)基础
  1.MongoDB 由databases组成，databases由collections组成，collections有documents(相当于行）组成，而documents有fields(相当于列）组成。

 MongoDB是异步写数据。

  2.常用命令：
   help:
     db.help() help on db methods
     db.mycoll.help() help on collection methods
     use dbName  切换db
     show dbs  列出数据库列表
     show collections 列出数据列表
     db.collection.find().help()

  3.use dbName  切换db
    如果dbname 不存在，则创建，如果存在，则切换到dbName

  4.show dbs  列出数据库列表
  
  5.show collections 列出数据列表

  6.
