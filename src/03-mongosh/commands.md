## Connect to container
```sh
docker-compose exec mongo db bash
```
## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
```

```sh
show dbs
show collections
```

```sh
use (isp20_store)
db.products.find()
```