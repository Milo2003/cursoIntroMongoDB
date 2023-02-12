## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb+srv://milo2508:adminroot2508@labnodejs.zi1ocf5.mongodb.net/test"
mongosh "mongodb://root:root2508@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```
