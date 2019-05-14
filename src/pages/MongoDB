---
title: MongoDB
description : 
date: '2019-05-14'
---



MongoDB is a document-based DB. MongoDB Community is open-source and can always be used by developers to work on their own projects.

## How to install and work with a database with MongoShell?

In this new-age computing, working with databases also is more fun. MongoDB offers a shell-based interactive javascript UI for querying 

the database and performing some administrative tasks on it. Let's learn how to use MongoShell and play around with MongoDB:

1) First, download latest Mongo form : https://docs.mongodb.com/manual/installation/#mongodb-community-edition-installation-tutorials according to the intructions mentioned in the link for your OS environments - Windows, Mac or Linux respectively.

2) Now, create a folder on your favourite disk like C:\Desktop\{dir-name} for storing data on the DB. So, ideally this is your physical path where the databases are created through MongoDB and managed accordingly.

3) Now, please navigate to the /bin folder of the MongoDB installation path usually at : C:\Program Files\MongoDB\Server\4.0\bin and perform the below operations:

Command:

mongod --dbpath <dir-name> created in Step-2

You will see output like below:

2019-05-13T17:32:22.047-0800 I CONTROL  [main] Automatically disabling TLS 1.0, to force-enable TLS 1.0 specify --sslDisabledProtocols 'none'
2019-05-13T17:32:22.050-0800 I CONTROL  [initandlisten] MongoDB starting : pid=9736 port=27017 dbpath=C:\Users\Manu\Desktop\Learnings\DOTNET_Core 64-bit host=manu-pc
2019-05-13T17:32:22.051-0800 I CONTROL  [initandlisten] targetMinOS: Windows 7/Windows Server 2008 R2
2019-05-13T17:32:22.051-0800 I CONTROL  [initandlisten] db version v4.0.9
2019-05-13T17:32:22.051-0800 I CONTROL  [initandlisten] git version: fc525e2d9b0e4bceff5c2201457e564362909765
2019-05-13T17:32:22.052-0800 I CONTROL  [initandlisten] allocator: tcmalloc
2019-05-13T17:32:22.052-0800 I CONTROL  [initandlisten] modules: none
2019-05-13T17:32:22.052-0800 I CONTROL  [initandlisten] build environment:
2019-05-13T17:32:22.053-0800 I CONTROL  [initandlisten]     distmod: 2008plus-ssl
2019-05-13T17:32:22.053-0800 I CONTROL  [initandlisten]     distarch: x86_64
2019-05-13T17:32:22.053-0800 I CONTROL  [initandlisten]     target_arch: x86_64
2019-05-13T17:32:22.053-0800 I CONTROL  [initandlisten] options: { storage: { dbPath: "C:\Users\Manu\Desktop\Learnings\DOTNET_Core" } }
2019-05-13T17:32:22.055-0800 I STORAGE  [initandlisten] wiredtiger_open config: create,cache_size=5557M,session_max=20000,eviction=(threads_min=4,threads_max=4),config_base=false,statistics=(fast),log=(enabled=true,archive=true,path=journal,compressor=snappy),file_manager=(close_idle_time=100000),statistics_log=(wait=0),verbose=(recovery_progress),
2019-05-13T17:32:22.342-0800 I STORAGE  [initandlisten] WiredTiger message [1557797542:342257][9736:140727041412176], txn-recover: Set global recovery timestamp: 0
2019-05-13T17:32:22.568-0800 I RECOVERY [initandlisten] WiredTiger recoveryTimestamp. Ts: Timestamp(0, 0)
2019-05-13T17:32:23.021-0800 I CONTROL  [initandlisten]
2019-05-13T17:32:23.025-0800 I CONTROL  [initandlisten] ** WARNING: Access control is not enabled for the database.
2019-05-13T17:32:23.027-0800 I CONTROL  [initandlisten] **          Read and write access to data and configuration is unrestricted.
2019-05-13T17:32:23.028-0800 I CONTROL  [initandlisten]
2019-05-13T17:32:23.029-0800 I CONTROL  [initandlisten] ** WARNING: This server is bound to localhost.
2019-05-13T17:32:23.031-0800 I CONTROL  [initandlisten] **          Remote systems will be unable to connect to this server.
2019-05-13T17:32:23.032-0800 I CONTROL  [initandlisten] **          Start the server with --bind_ip <address> to specify which IP
2019-05-13T17:32:23.033-0800 I CONTROL  [initandlisten] **          addresses it should serve responses from, or with --bind_ip_all to
2019-05-13T17:32:23.034-0800 I CONTROL  [initandlisten] **          bind to all interfaces. If this behavior is desired, start the
2019-05-13T17:32:23.035-0800 I CONTROL  [initandlisten] **          server with --bind_ip 127.0.0.1 to disable this warning.
2019-05-13T17:32:23.035-0800 I CONTROL  [initandlisten]
2019-05-14T11:32:23.037+1000 I STORAGE  [initandlisten] createCollection: admin.system.version with provided UUID: 1b268390-d98f-4385-8ff3-20059c760c2c
2019-05-14T11:32:23.418+1000 I COMMAND  [initandlisten] setting featureCompatibilityVersion to 4.0
2019-05-14T11:32:23.426+1000 I STORAGE  [initandlisten] createCollection: local.startup_log with generated UUID: 60d03adc-e1b5-45b7-beae-f5b08b1efc80
2019-05-14T11:32:24.029+1000 I FTDC     [initandlisten] Initializing full-time diagnostic data capture with directory 'C:/Users/Manu/Desktop/Learnings/DOTNET_Core/diagnostic.data'
2019-05-14T11:32:24.032+1000 I NETWORK  [initandlisten] waiting for connections on port 27017
2019-05-14T11:32:24.032+1000 I STORAGE  [LogicalSessionCacheRefresh] createCollection: config.system.sessions with generated UUID: ec915067-13ec-45dc-8dcf-2f5cdb8b879c
2019-05-14T11:32:24.969+1000 I INDEX    [LogicalSessionCacheRefresh] build index on: config.system.sessions properties: { v: 2, key: { lastUse: 1 }, name: "lsidTTLIndex", ns: "config.system.sessions", expireAfterSeconds: 1800 }
2019-05-14T11:32:24.969+1000 I INDEX    [LogicalSessionCacheRefresh]     building index using bulk method; build may temporarily use up to 500 megabytes of RAM
2019-05-14T11:32:25.225+1000 I INDEX    [LogicalSessionCacheRefresh] build index done.  scanned 0 total records. 0 secs
2019-05-14T11:32:25.226+1000 I COMMAND  [LogicalSessionCacheRefresh] command config.$cmd command: createIndexes { createIndexes: "system.sessions", indexes: [ { key: { lastUse: 1 }, name: "lsidTTLIndex", expireAfterSeconds: 1800 } ], $db: "config" } numYields:0 reslen:114 locks:{ Global: { acquireCount: { r: 2, w: 2 } }, Database: { acquireCount: { w: 2, W: 1 } }, Collection: { acquireCount: { w: 2 } } } storage:{} protocol:op_msg 1193ms

Now, open another shell instance to use the default testing database and run following:

Command: mongo

You will output as below:
λ mongo
MongoDB shell version v4.0.9
connecting to: mongodb://127.0.0.1:27017/?gssapiServiceName=mongodb
Implicit session: session { "id" : UUID("d05be4bf-acec-4645-87c0-486b06d613dc") }
MongoDB server version: 4.0.9
Welcome to the MongoDB shell.
For interactive help, type "help".
For more comprehensive documentation, see
        http://docs.mongodb.org/
Questions? Try the support group
        http://groups.google.com/group/mongodb-user
Server has startup warnings:
2019-05-13T17:24:26.193-0800 I CONTROL  [initandlisten]
2019-05-13T17:24:26.194-0800 I CONTROL  [initandlisten] ** WARNING: Access control is not enabled for the database.
2019-05-13T17:24:26.194-0800 I CONTROL  [initandlisten] **          Read and write access to data and configuration is unrestricted.
2019-05-13T17:24:26.194-0800 I CONTROL  [initandlisten]
---
Enable MongoDB's free cloud-based monitoring service, which will then receive and display
metrics about your deployment (disk utilization, CPU, operation statistics, etc).

The monitoring data will be available on a MongoDB website with a unique URL accessible to you
and anyone you share the URL with. MongoDB may use this information to make product
improvements and to suggest MongoDB products and deployment options to you.

To enable free monitoring, run the following command: db.enableFreeMonitoring()
To permanently disable this reminder, run the following command: db.disableFreeMonitoring()
---

Now, run the following command :

Command: use BookstoreDb

Output as below:
> use BookstoreDb
switched to db BookstoreDb

We can now create some sample Books Collection 

Command: > db.createCollection('Books')

Output as below:
{ "ok" : 1 }

So, as we have created Books COllections, let's insert 2 books into the collection:

Command: db.Books.insertMany([{'Name':'Design Patterns in .NET','Price':24.14,'Category':'Computers','Author':'Dmitri Nesteruk'}, {'Name':'Programming in C#','Price':24.91,'Category':'Computers','Author':'Rob Miles '}])

Output as below:
> db.Books.insertMany([{'Name':'Design Patterns in .NET','Price':24.14,'Category':'Computers','Author':'Dmitri Nesteruk'}, {'Name':'Programming in C#','Price':24.91,'Category':'Computers','Author':'Rob Miles '}])

        "acknowledged" : true,
        "insertedIds" : [
                ObjectId("5cda2216e5dd209944691062"),
                ObjectId("5cda2216e5dd209944691063")
        ]
}

Now that we have inserted data, we can check the data information of the books through the following command:

Command: 
db.Books.find({}).pretty()

Output:
        "_id" : ObjectId("5cda2216e5dd209944691062"),
        "Name" : "Design Patterns in .NET",
        "Price" : 24.14,
        "Category" : "Computers",
        "Author" : "Dmitri Nesteruk"
}

        "_id" : ObjectId("5cda2216e5dd209944691063"),
        "Name" : "Programming in C#",
        "Price" : 24.91,
        "Category" : "Computers",
        "Author" : "Rob Miles "
}
>



   


