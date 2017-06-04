# EDU partner Developer Bootcamp
This hands-on challenge will help you understand the application registration process and the sign in flow.

---

## Steps to complete the challenge ##
* Register you application in the correct portal
* Add the required libraries to your solution
* Design your sign in flow
* Design your permissions and consent flow
* Add a sign in button and trigger the sign in process

## Hints for All Platforms ##
* Read [https://aka.ms/aaddev ]()
* View samples
    * [https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-code-samples]()
    * [https://github.com/Azure-Samples?q=active-directory]()

* Node.JS
    * Use Passport
    * Set strategy correctly for the type of flow

* .NET
    * Use OWIN libraes if possible
    * Avoid Pre-release libraries
    * Beware of dependencies with token parsers
    * Know your flow
    * Remember Single vs. Multi tenant
    * Different libraries for different endpoints
        * MSAL – 2.0
        * ADAL – 1.0
        * Microsoft Graph – 2.0
* Client side libraries
    * Remember CORS for client side flows


---

Copyright 2016 Microsoft Corporation. All rights reserved. Except where otherwise noted, these materials are licensed under the terms of the MIT License. You may use them according to the license 
as is most appropriate for your project. The terms of this license can be found at https://opensource.org/licenses/MIT.