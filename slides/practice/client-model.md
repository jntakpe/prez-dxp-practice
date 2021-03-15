## Create client model

* Checkout tag `java-client-model` or `kotlin-client-model`
* Create an `AssessmentClientDto` class that maps both `quiz.module` and `stats.bestScore` fields of the assessments'
[find by owner API endpoint](https://ms-doc.asm2.dxp.delivery/guide/training-quiz) 
([fallback url](https://jntakpe.github.io/training-quiz-api/)).
    * Hint: To map the endpoint it is possible that the single `AssessmentClientDto` class is not enough 
* Create a `Skill` class with both `name` and `score` fields to hold the data retrieved from the assessments'
 API endpoint.
* In the class `User` add a `skills` field containing a skill list.
    * Hint: `skills` field should not be stored in the database
