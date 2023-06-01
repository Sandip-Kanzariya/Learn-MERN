# Learn-MERN
Installation, Starting of all tools and learning

|Topic|
| ---|
|[Json](https://github.com/Sandip-Kanzariya/Learn-MERN/tree/main#mongodb-)|
|[MongoDB](https://github.com/Sandip-Kanzariya/Learn-MERN/tree/main#json--javascript-object-notation) |
|[ReactJS](https://github.com/Sandip-Kanzariya/Learn-MERN/tree/main#react-js-) |

# JSON : JavaScript Object Notation
1. [Amazing Tutorial On Json For Beginners](https://youtu.be/6OhMbf2v_jI)
2. [Json Formatter](https://jsonformatter.org/)
# MongoDB : 
>Installation & Setup :


1. [MongoDB](https://www.mongodb.com/try/download/community) | Set Path of bin folder in Environment Variable

2. [mongosh](https://www.mongodb.com/try/download/shell) | Set Path of bin folder in Environment Variable    

~~~~
mongod
mongosh
show dbs
~~~~

https://github.com/Sandip-Kanzariya/Codeforces/assets/105594748/75464082-67b4-4631-812d-5686729e8602

>Use Particular Database :
~~~~
use databasename
~~~~

>Create  
~~~~
db.collectionName.insertOne()
db.collectionName.insertMany()
~~~~

~~~~
db.collectionName.insertOne({   
    "name": "San", 
    "email": "san@gmail.com"
})
    
db.collectionName.insertOne({   
    name: "San", 
    email: "san@gmail.com"
})
~~~~


>Read
~~~~
db.collectionName.find()
db.collectionName.find().pretty()
~~~~

>Update
~~~~
db.collectionName.updateOne()
db.collectionName.updateMany()

db.collectionName.update()
~~~~

>Delete
~~~~
db.collectionName.deleteOne()
db.collectionName.deleteMany()

db.collectionName.delete()
~~~~


# React JS : 
> Installation & Set up
1. [Download Node JS](https://nodejs.org/en/download)
