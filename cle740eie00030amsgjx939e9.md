---
title: "How SSH (Secure Shell) Works?"
seoTitle: "How SSH (Secure Shell) Works?"
seoDescription: "How SSH (Secure Shell) Works?"
datePublished: Thu Feb 16 2023 12:59:59 GMT+0000 (Coordinated Universal Time)
cuid: cle740eie00030amsgjx939e9
slug: how-ssh-secure-shell-works
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1676552243736/f450d72e-7acf-42e7-8677-152abbe29316.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1676552382489/66b8aebe-41f3-48c6-8e51-16ef081466b5.png
tags: cloud, aws, azure, devops, gcp

---

SSH (Secure Shell) is a protocol used to securely log into a remote computer and execute commands on that computer over an unsecured network. SSH provides strong authentication and encryption for secure data transmission over an insecure network.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676552294789/aa0c832d-f66e-4217-813e-cf5a72486f42.png align="center")

Here's how SSH works:

1. The client initiates a connection to the server and requests to establish an SSH session. The client and server agree on the version of SSH to use.
    
2. The server sends its public key to the client.
    
3. The client verifies the server's public key by checking it against a list of trusted keys or by prompting the user to confirm the key's fingerprint.
    
4. The client generates a session key and encrypts it with the server's public key. This encrypted session key is sent to the server.
    
5. The server decrypts the session key using its private key and sends an acknowledgment to the client.
    
6. The client and server now use the session key to encrypt and decrypt all data that is sent over the SSH connection.
    
7. The client is now authenticated and can execute commands on the server. The client can also request port forwarding, X11 forwarding, or file transfers.
    
8. Once the session is complete, the client sends a message to the server indicating that it wishes to disconnect. The server acknowledges the message and terminates the session.
    

Overall, SSH provides secure authentication and encrypted communication between two networked devices.

SSH is widely used to remotely access and manage servers, perform administrative tasks, transfer files, and perform other tasks that require secure access to a remote computer over an unsecured network. SSH provides a secure and encrypted alternative to traditional remote access protocols, such as Telnet, that transmit data in clear text, making them vulnerable to eavesdropping and tampering.

### **YouTube Tutorial:** [https://youtu.be/tt\_DeyDpLkw](https://youtu.be/tt_DeyDpLkw)

### [**Subscribe :)**](https://www.youtube.com/@amonkincloud/)