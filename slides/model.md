## Create model

* Checkout tag `java-model` or `kotlin-model`
* Create a class `Teams` with toString, equals, hashcode matching the following:
    * hint: `MongoAuditable` class contains auditing fields 
    * hint: field `_id` is mapped by the MongoDB driver and is equivalent to `id`
    
```json
{
  "_id": "",
  "name": "",
  "createdBy": "",
  "createdAt": "",
  "lastModifiedBy": "",
  "lastModifiedAt": "",
  "users": [{
    "username": "",
    "familyName": "",
    "givenName": ""
  }]
}
```
