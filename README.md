# Azure-Cloud-Resume
Exploring the power of Azure to deploy and optimize static websites, secure custom domains, and leverage cloud technologies. Currently working on deploying static websites using Azure Blob Storage and Azure CDN, with plans to integrate more services in the future. Follow along for updates on cloud projects, automation, and more! 🚀


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

🎉 **Your static website is now hosted on Azure Blob Storage!** 🎉

## 2️⃣ Upload Your Website Files
1. Create a **public container** in your storage account, and upload all your static files (HTML, CSS, JS).
2. You can manage and update these files anytime from the **Azure Blob Storage** interface.

📂 **Pro Tip:** Organize your files well for future updates!

## 3️⃣ Add Azure CDN for Faster Delivery 🚀
1. Create a **CDN Profile** under the Azure CDN service.
2. Link the **origin** to your **Blob Storage** endpoint, which ensures fast and reliable delivery of your static content.
3. Configure caching and compression settings for optimal performance! ⚡

> **Pro Tip:** Azure CDN can significantly improve your website’s load times worldwide 🌍.

## 4️⃣ Secure Your Custom Domain with HTTPS 🔒
1. In your CDN Profile, navigate to **Custom Domains** and add your custom domain (e.g., `www.yourdomain.com`).
2. In your DNS management tool (e.g., Cloudflare), create a **CNAME record** that points to your **Azure CDN endpoint** (e.g., `yourwebsite.azureedge.net`).
3. Enable **HTTPS** by selecting the **Azure Managed Certificate** option. It’s free and easy! 🔐

💡 **Tip:** HTTPS ensures your website is secure and trusted by users.

## 🎯 Test Your Website
Once everything is set up and DNS propagation completes (this can take up to 24 hours), head to your custom domain (e.g., `https://yourdomain.com`) to check out your newly deployed static site!

## 🚀 What’s Next?
In the future, I plan to:
- Integrate more **Azure services** like **Azure Functions**, **Azure Front Door**, and **Application Insights**.
- Add advanced **monitoring** and **automated deployments** with **Azure DevOps**.

Stay tuned for updates! ✨

---

**Resources:**
- [Azure Static Website Documentation](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website)
- [Azure CDN Documentation](https://docs.microsoft.com/en-us/azure/cdn/)



