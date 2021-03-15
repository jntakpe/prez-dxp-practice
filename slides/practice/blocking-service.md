## Regular service

* Checkout tag `java-service-blocking` or `kotlin-service-blocking`
* Implement `ITeamService` interface
    * Hint: create a blocking repository that performs operations on `Team` entity
([see Spring Data usage](https://spring.io/guides/gs/accessing-data-mongodb/))
    * Hint: use `DxpSbsException` to handle errors
    * Actions performed by the service should be logged
    * To make sure you have implemented the desired behaviour executing unit tests
