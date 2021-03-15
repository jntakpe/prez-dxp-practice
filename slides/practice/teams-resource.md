## Retrieve skills

* Checkout tag `java-resource-teams` or `kotlin-resource-teams`
* Create a resource that publishes a team API that complies with [this](https://ms-doc.asm2.dxp.delivery/guide/training-teams).
    * Hint: Team creation endpoint is allowed only for 'DxpTenantUserBusinessContext.class' user type
    * Hint: Team creation endpoint should validate request input
    * Hint: Users individual skills and stats should be displayed for 'DxpTenantUserBusinessContext.class' user types and hidden for 'DxpEndUserFromTenantBusinessContext.class'
    * Hint: Constants are available in 'ResourceConstants.class' and 'ApiConstants.class'
* All tests should pass
