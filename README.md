# Azure-Cloud-Resume
Exploring the power of Azure to deploy and optimize static websites, secure custom domains, and leverage cloud technologies. Currently working on deploying static websites using Azure Blob Storage and Azure CDN, with plans to integrate more services in the future. Follow along for updates on cloud projects, automation, and more! 🚀

# Website Here
https://www.maliksazureresume.org/

# 🌐 Deploying a Static Website with Azure Blob Storage and Azure CDN 🎉

This guide will help you deploy a static website using **Azure Blob Storage** and **Azure CDN** with your own custom domain, and secure it with **HTTPS**! 🔒

> 🚀 **Future Updates:** I will be expanding this project to integrate more Azure services, so stay tuned! 

## 🌟 Prerequisites
Before starting, ensure you have the following ready:
- ✅ An active **Azure subscription**
- ✅ A **custom domain** (e.g., from Cloudflare, GoDaddy, etc.)
- ✅ Optional: **Azure CLI** for quicker deployment commands

## 1️⃣ Create and Configure Azure Blob Storage for Static Website Hosting
1. Head over to the **Azure Portal** and create a new **Storage Account**.
2. In the **Data Management** section, find **Static website** and turn it on. 🌍
3. Set your **index document** (e.g., `index.html`) and an error document (e.g., `404.html`).
![Screenshot 2024-10-19 094745](https://github.com/user-attachments/assets/3040ef0c-4604-4bd6-b9fd-d72d56e49c66)
![Screenshot 2024-10-19 094811](https://github.com/user-attachments/assets/fec03c7d-0ce7-457f-a0ba-21ec880da3d5)




🎉 **Your static website is now hosted on Azure Blob Storage!** 🎉

## 2️⃣ Upload Your Website Files
1. Create a **public container** in your storage account, and upload all your static files (HTML, CSS, JS).
2. You can manage and update these files anytime from the **Azure Blob Storage** interface.
![Screenshot 2024-10-19 100536](https://github.com/user-attachments/assets/b0dcec12-3ee2-4094-ba85-9fe492882a60)






📂 **Pro Tip:** Organize your files well for future updates!

## 3️⃣ Add Azure CDN for Faster Delivery 🚀
1. Create a **CDN Profile** under the Azure CDN service.
2. Link the **origin** to your **Blob Storage** endpoint, which ensures fast and reliable delivery of your static content.
3. Configure caching and compression settings for optimal performance! ⚡
![Screenshot 2024-10-19 094848](https://github.com/user-attachments/assets/22b938d3-3b29-4f99-9829-f65127572d4c)


> **Pro Tip:** Azure CDN can significantly improve your website’s load times worldwide 🌍.

## 4️⃣ Secure Your Custom Domain with HTTPS 🔒
1. In your CDN Profile, navigate to **Custom Domains** and add your custom domain (e.g., `www.yourdomain.com`).
2. In your DNS management tool (e.g., Cloudflare), create a **CNAME record** that points to your **Azure CDN endpoint** (e.g., `yourwebsite.azureedge.net`).
3. Enable **HTTPS** by selecting the **Azure Managed Certificate** option. It’s free and easy! 🔐
![Screenshot 2024-10-19 100735](https://github.com/user-attachments/assets/5bf837dd-fc62-48d9-8cc3-d505918a1ac6)



💡 **Tip:** HTTPS ensures your website is secure and trusted by users.

## 🎯 Test Your Website
Once everything is set up and DNS propagation completes (this can take up to 24 hours), head to your custom domain (e.g., `https://yourdomain.com`) to check out your newly deployed static site!
![Screenshot 2024-10-19 100935](https://github.com/user-attachments/assets/5c58711d-e666-490d-baf0-2a001f1bebbd)


## 🚀 What’s Next?
In the future, I plan to:
- Integrate more **Azure services** like **Azure Functions**, **Azure Front Door**, and **Application Insights**.
- Add advanced **monitoring** and **automated deployments** with **Azure DevOps**.

Stay tuned for updates! ✨

---

**Resources:**
- [Azure Static Website Documentation](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website)
- [Azure CDN Documentation](https://docs.microsoft.com/en-us/azure/cdn/)



