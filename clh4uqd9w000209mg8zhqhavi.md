---
title: "Host Static Website Using Azure Blob Storage and GitHub Actions"
datePublished: Mon May 01 2023 13:03:49 GMT+0000 (Coordinated Universal Time)
cuid: clh4uqd9w000209mg8zhqhavi
slug: host-static-website-using-azure-blob-storage-and-github-actions
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1682946194476/5dd21f52-58cc-4c97-ac42-506b14942df7.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1682946217281/ce292902-2b56-498c-98a2-48c4330af11e.png

---

Hosting a static website on Azure is relatively easy, and the process involves just a few steps. We will also show you how to set up continuous integration and deployment (CI/CD) for your static website on Azure.

Here are the steps to host a static website on Azure and implement CI/CD:

1. Create an Azure Storage Account
    
    * Sign in to the Azure portal.
        
    * In the left-hand menu, click on "Create a resource" and select "Storage account".
        
    * Fill out the required fields in the "Basics" tab, such as the subscription, resource group, storage account name, and location.
        
    * Click on the "Review + Create" button to review your settings, and then click on the "Create" button to create your storage account.
        
2. Create a Static Website
    
    * After your storage account has been created, go to the "Static website" section under "Settings".
        
    * Click on the "Enabled" button to enable static website hosting.
        
    * Enter the name of your default document, such as "index.html".
        
    * Optionally, you can also specify a custom 404 error document.
        
3. Upload Your Website Files to the Storage Account
    
    * Go to the "Blobs" section in your storage account.
        
    * Click on the "Upload" button to upload your website files, such as your HTML, CSS, and JavaScript files.
        
    * Select "Browse" to navigate to the directory where your files are stored.
        
    * Select the files you want to upload and click on the "Upload" button.
        
4. Set Up CI/CD for Your Static Website
    
    * I am going to use GitHub Actions
        
    * Refer to this Documentation for more details on how to setup CICD: [https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-static-site-github-actions?tabs=userlevel](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-static-site-github-actions?tabs=userlevel)
        

GitHub Repo: [https://github.com/yeshwanthlm/Static-Webhosting-Azure](https://github.com/yeshwanthlm/Static-Webhosting-Azure)

That's it! You have successfully hosted your static website on Azure and Implemented CI/CD for your website.

Follow our tutorials here: [https://www.youtube.com/@amonkincloud/videos](https://www.youtube.com/@amonkincloud/videos)

Follow our GitHub here: [https://github.com/yeshwanthlm](https://github.com/yeshwanthlm)

Follow our blog here: [https://amonkincloud.com/](https://amonkincloud.com/)

Follow my personal blog here:[https://dev.to/yeshwanthlm/](https://dev.to/yeshwanthlm/)

Follow us on Instagram: [https://www.instagram.com/amonkincloud/](https://www.instagram.com/amonkincloud/)