## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb+srv://antomore:Antom.01@cluster0.j7ipfyp.mongodb.net/"
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.productos.find()```