---
title: "How Single Sign-On (SSO) Works?"
seoTitle: "How Single Sign-On (SSO) Works?"
seoDescription: "How Single Sign-On (SSO) Works?"
datePublished: Thu Feb 16 2023 10:06:10 GMT+0000 (Coordinated Universal Time)
cuid: cle6xsvhq001109jz5t2b5yun
slug: how-single-sign-on-sso-works
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1676542398584/5358bf69-0aeb-4896-91b7-df84a414db6d.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1676542444057/fb778916-c45b-4432-9d40-00ca39be051e.png
tags: cloud, aws, azure, devops, gcp

---

Single Sign-On (SSO) is an authentication method that allows users to access multiple applications or services with a single set of login credentials (username and password). Instead of having separate usernames and passwords for each application, users log in once and are then able to access all the applications they are authorized to use.

Here's how SSO works:

* The user attempts to access an application that requires authentication.
    
* The application redirects the user to an SSO login page.
    
* The user enters their login credentials (username and password) into the SSO login page.
    
* The SSO system verifies the credentials with an identity provider (IdP), which is a centralized service responsible for authenticating users.
    
* If the credentials are valid, the IdP generates a security token that includes information about the user's identity and authorization.
    
* The security token is passed back to the application, which then grants the user access.
    
* For subsequent access to other applications, the user does not need to re-enter their credentials, as the SSO system will recognize the security token generated earlier.
    

This makes it easier for users to access the applications they need and eliminates the frustration and security risks associated with managing multiple usernames and passwords. SSO also improves security by reducing the number of opportunities for unauthorized access, as users are required to authenticate only once.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676541790447/09f3ad3f-a33a-46ca-a273-a38eead774d5.png align="center")

* In this diagram, the user attempts to access Application 1 and is redirected to the SSO login page.
    
* The user enters their login credentials, which are verified by the identity provider (IdP).
    
* If the credentials are valid, the IdP generates a security token and passes it back to the application, which then grants the user access.
    
* For subsequent access to Application 2, the user does not need to re-enter their credentials as the SSO system recognizes the security token generated earlier.
    
* The security token is passed directly to the second application, which grants the user access without requiring additional authentication.
    

### **YouTube Tutorial:** [https://youtu.be/JspAgMxLtgE](https://youtu.be/JspAgMxLtgE)

### [**Subscribe :)**](https://www.youtube.com/@amonkincloud/)