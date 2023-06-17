# Learn-MERN
Installation, Starting of all tools and learning

|Table of Contents|
| ---|
| ES6 & Typescript|
|[Json](https://github.com/Sandip-Kanzariya/Learn-MERN/tree/main#json--javascript-object-notation)|
|[MongoDB](https://github.com/Sandip-Kanzariya/Learn-MERN/tree/main#mongodb-)|
|[ReactJS](https://github.com/Sandip-Kanzariya/Learn-MERN/tree/main#react-js-) |
|NodeJS |
|ExpressJS|

# React JS : 
[ Best Tutorial ](https://youtube.com/playlist?list=PLpPqplz6dKxW5ZfERUPoYTtNUNvrEebAR) 
> Installation & Set up
1. [Download Node](https://nodejs.org/en/download)
~~~
Check First this : 
npm -v
node -v
~~~
2. Create First Project Of React 
~~~
npx create-react-app .
npm start 

        OR
        
npx create-react-app app-name
cd app-name
npm start
~~~

# ES6 & Typscript 

[TS Playground](https://www.typescriptlang.org/play?#code/MYewdgziA2CmB00QHMAUAiAFraT0Eog)

>Installation Globally
```
npm install typescript -g

tsc  filename.ts
```
>create tsconfig.json
```
tsc -v
tsc --init
```
```json
<!-- All .js files store in scripts -->
{
  "compilerOptions": {
    "target": "es2016",
    "module": "commonjs",
    "esModuleInterop": true,
    "forceConsistentCasingInFileNames": true,
    "strict": true,
    "sourceMap": true,
    "outDir": "scripts/"
  }
}
```


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
>Get All Collections : 
~~~
 db.getCollectionNames()
~~~

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



