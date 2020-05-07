Prerequisites
1. Tenant Name
2. proxyidentityexperienceframework application Id
3. identityexperienceframework application id

open SignInWithPhoneNumberBase.xml
-> Copy and replace all tenantname with Tenant Name
-> Copy and replace all proxyidentityexperienceframework with Application Id
-> Copy and replace all identityexperienceframework with Application Id

open SignInWithPhoneNumber.xml
-> Copy and replace all tenantname with Tenant Name

Update the UI URI
-> open SignInWithPhoneNumberBase.xml
-> Search phoneSignIn Content Defination
-> change the LoadUri with staic site uri
-> do same for phoneInput

For More Information visit
https://docs.microsoft.com/en-us/azure/active-directory-b2c/custom-policy-get-started
 
