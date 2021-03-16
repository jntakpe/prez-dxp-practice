## Regular service

* Checkout tag `java-service-blocking` or `kotlin-service-blocking`
* Implement `ITeamService` interface
    * Hint: create a blocking repository that performs operations on `Team` entity
([see Spring Data usage](https://spring.io/guides/gs/accessing-data-mongodb/))
    * Hint: use `DxpSbsException` to handle errors
    * Hint: you can leverage MongoDB's indexes to avoid duplicating field name 
    * Actions performed by the service should be logged
    * Make sure you have implemented the desired behaviour executing unit tests
