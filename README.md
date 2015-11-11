# BluemixREST using Node.js

Simple RESTful interface on Bluemix to create, read, update or delete bears.

A bear looks like this:

```
{
    "_id": "56427fd15e426984096bdaa9",
    "__v": 0,
    "name": "Coyle's Bear",
    "age": 23,
    "occupation": "painter"
}
```

## GET all bears
http://bluemixrest.mybluemix.net/bears

## GET single bears
http://bluemixrest.mybluemix.net/bears/:bear_id

## POST
http://bluemixrest.mybluemix.net/bears

with the POST parameters:
```
name = Hector's Bear
age = 23
occupation = Gamer
```

## PUT
http://bluemixrest.mybluemix.net/bears/:bear_id

with the PUT parameters to be updated:
```
name = Hector's Bear
age = 23
occupation = Gamer
```

## DELETE
http://bluemixrest.mybluemix.net/bears/:bear_id
