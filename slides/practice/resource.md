## Publish API

* Checkout tag `java-resource` or `kotlin-resource`
* Create a resource that publishes a team API that complies with [this spec](https://ms-doc.asm2.dxp.delivery/guide/training-teams).
    * Hint: Constants are available in 'ResourceConstants.class' and 'ApiConstants.class'
    * Hint: All SBCP's endpoints should be secured
    * Hint: Annotate your methods with: '@TypeAllowed(DxpTenantUserBusinessContext::class)'
    * Hint: Team creation endpoint should validate request input
* All tests should pass
