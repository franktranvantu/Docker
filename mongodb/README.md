```bash
docker exec -it [container_id] bash
mongo mongodb://localhost:27017 -u admin -p admin
db.collection.insertOne({...})
show dbs;
```

# Create database if not exist
```bash
use frank;
db.createCollection("test");
show dbs;
```

# Drop database
```bash
db.dropDatabase();
```

# Get help
```bash
db.help();
```

# Create collection
```bash
db.createCollection("student");
show collections;
db.student.stats();
```

# Drop collection
```bash
db.student.drop();
```