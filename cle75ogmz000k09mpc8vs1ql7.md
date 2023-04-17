---
title: "How HTTPS (Hypertext Transfer Protocol Secure) Works?"
seoTitle: "How HTTPS (Hypertext Transfer Protocol Secure) Works?"
seoDescription: "How HTTPS (Hypertext Transfer Protocol Secure) Works?"
datePublished: Thu Feb 16 2023 13:46:41 GMT+0000 (Coordinated Universal Time)
cuid: cle75ogmz000k09mpc8vs1ql7
slug: how-https-hypertext-transfer-protocol-secure-works
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1676555133062/b676929b-a0ee-4dd6-aeaf-6616a2bd879b.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1676555184233/08ce4c66-866e-42b8-8123-caf305c08d85.png
tags: cloud, aws, azure, devops, gcp

---

HTTPS (Hypertext Transfer Protocol Secure) is a secure version of the HTTP protocol used to transmit data over the internet. It provides secure communication between a client (e.g., a web browser) and a server (e.g., a web server) by encrypting the data being transmitted and ensuring the authenticity and integrity of the data.

Here's how HTTPS works:

* A client requests to access a secure website by sending an HTTPS request to the server.
    
* The server responds with a digital certificate, which contains information about the identity of the website and the public key of the server.
    
* The client verifies the authenticity of the certificate by checking it against a trusted third-party certificate authority (CA).
    
* If the certificate is valid, the client generates a secret key and sends it to the server encrypted with the server's public key.
    
* The server uses its private key to decrypt the secret key and establish an encrypted connection between the client and the server.
    
* Data is then transmitted between the client and server in an encrypted form, ensuring that it cannot be intercepted or modified in transit.
    
* At the end of the communication, the secret key is discarded and a new one is generated for the next communication.
    

This process ensures that data transmitted over HTTPS is encrypted and secure and that the identity of the website and server are verified. This helps to prevent unauthorized access, protect sensitive information, and ensure the integrity of the data being transmitted over the internet.

[![htpps](https://user-images.githubusercontent.com/66474973/218307154-ea5a2cfa-af38-4144-8745-9b91bb4e7c0d.png align="left")](https://user-images.githubusercontent.com/66474973/218307154-ea5a2cfa-af38-4144-8745-9b91bb4e7c0d.png)

In this diagram, the client requests to access a secure website and the server responds with a digital certificate, which contains information about the identity of the website and the public key of the server. The client verifies the authenticity of the certificate by checking it against a trusted third-party certificate authority (CA).

If the certificate is valid, the client generates a secret key and sends it to the server encrypted with the server's public key. The server uses its private key to decrypt the secret key and establish an encrypted connection between the client and the server. Data is then transmitted between the client and server in an encrypted form, ensuring that it cannot be intercepted or modified in transit.

This process helps to ensure the security and privacy of data transmitted over the internet and provides a secure communication channel between the client and server.

### **YouTube Tutorial:** [https://youtu.be/h3tSBn59EgA](https://youtu.be/h3tSBn59EgA)

### [**Subscribe :)**](https://www.youtube.com/@amonkincloud/)