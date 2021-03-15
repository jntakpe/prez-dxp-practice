## Implement HTTP client call

* Checkout tag `java-client` or `kotlin-client`
* Annotate the `QuizClient` interface with [Retrofit's](https://square.github.io/retrofit/) annotations to call 
assessments' [find by owner API endpoint](https://ms-doc.asm2.dxp.delivery/guide/training-quiz) 
([fallback url](https://jntakpe.github.io/training-quiz-api/)) 
    * Hint: Don't forget the secret SCBP's annotation to declare a 'Retrofit client'
* All tests should pass
