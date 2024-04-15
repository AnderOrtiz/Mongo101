## Connect to container

```sh
    sudo docker-compose exec mongodb bash
    ## sudo docker compose exec mongodb mongosh 
```

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://ortizone620:4TunMYfXbtsDIT0i@andersonortiz.vaknlzs.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```