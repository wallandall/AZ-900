# Authentication and Authorization

## Azure Identity Services
Access management is a critical part of any system and provides Authentication and Authorisation services 
- Authentication
  - Makes sure you are you
  - Confirms your identity
  - First test for access
- Authiorisation
  - Comes after authentication
  - Asks if you do have access
 

## Azure Active Directory
[Azure Active Directory (Azure AD)](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis) is a cloud-based identity and access management service. This service helps your employees access external resources, such as Microsoft 365, the Azure portal, and thousands of other SaaS applications. Azure AD also helps them access internal resources. These are resources like apps on your corporate network and intranet, along with any cloud apps developed by your own organization

- Tenant: A Tenant is a represents the organisation and has a dedicated instance of AAD. Each Tenant is distinct and completely seperate from other AAD Tenants. Each user in Azure can be a member or guest of up to 500 Azure AD Tenants
- Subscriptions : Are billing entities where all resources are billed together. Each tenant can have multiple Subscriptions to seperate costs. 

- Hybrid Cloud Architecture: is where some resources are hosted on premise and others in the cloud. AAD can help manage the resources in both environments

## Multi Factor Authentication
[Multi-factor authentication](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-mfa-howitworks) is a process in which users are prompted during the sign-in process for an additional form of identification, such as a code on their cellphone or a fingerprint scan.

If you only use a password to authenticate a user, it leaves an insecure vector for attack. If the password is weak or has been exposed elsewhere, an attacker could be using it to gain access. When you require a second form of authentication, security is increased because this additional factor isn't something that's easy for an attacker to obtain or duplicate.

## Single Sing on
[Single sign-on](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/what-is-single-sign-on) is an authentication method that allows users to sign in using one set of credentials to multiple independent software systems.



[back](ReadMe.md)