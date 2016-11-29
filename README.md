
###without CouchDB:

```

docker-compose -f docker-compose-2peers.yml up -d --force-recreate

docker-compose -f docker-compose-add-1peer.yml up -d --force-recreate

```

###with CouchDB:

```

docker-compose -f docker-compose-2peers-with-couchdb.yml up -d --force-recreate

docker-compose -f docker-compose-add-1peer-with-couchdb.yml up -d --force-recreate

```

