# **Go Rest API test automation demo using Postman**

### Requirements:
README assumes you have installed Postman

### Postman Collection and Environment file Import and setup:
To import test collection and environment variables necessary for test execution, please use import feature in Postman.

1. Browse for both files listed in this repository and upload into your Postman
2. Switch to imported `env` environment
3. Get your bearer token from this resource: https://gorest.co.in/consumer/login
4. Open the `Go Rest demo API automation` collection's root level in editor, select `Authorization` tab and add the `Bearer token` from step 3 as `Type`. Save.

### Test Execution:
Select context menu on imported Collection `Go Rest demo API automation` and choose `Run collection`
to access the test runner.
