990-Mongodb1
============


-----------
mongod -dbpath "C:\mongodb-data\data\db"
mongo
-----------


------------------>
use:
MongoDB shell version: 2.6.5
connecting to: test
> use newDB
switched to db newDB
> db.createCollection("newCollection")
{ "ok" : 1 }
>
-------------------------------

----------------->
shot down
> use admin
switched to db admin
> db.shutdownServer()
----------------------------

