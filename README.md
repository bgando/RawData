RawData
=======

MongoDump of OpenShakespeare Data


mongorestore restores a backup of the database instance located in dump to a database instance stored in the /srv/mongodb on the local machine. This requires that there are no active mongod instances attached to /srv/mongodb data directory.

```
mongorestore --dbpath /srv/mongodb
```
