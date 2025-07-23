# Azure Lab: Creating and Managing a Storage Account

## 📌 Objective:
This lab guides users through creating a resource group and a storage account in Microsoft Azure, uploading and editing a text file within the storage container, and practicing responsible resource cleanup to avoid unnecessary costs.

---

## 🧰 Technologies Used:
- Microsoft Azure Portal (https://portal.azure.com)
- Azure Resource Groups
- Azure Storage Accounts
- Azure Blob Storage (File upload/edit)
- Local Text Editor (e.g., Notepad, TextEdit)
- Web Browser

---

## ✅ Prerequisites:
- A valid Microsoft account
- An active Azure subscription (Free Trial or Pay-As-You-Go)
- Access to the internet
- A basic understanding of cloud storage concepts
- Optional: A plain-text editor installed locally (e.g., Notepad for Windows, TextEdit for macOS)

---

## 🛠️ Steps to Perform:

1. **Create an Azure Subscription**  
   - Sign up at: [https://azure.microsoft.com/en-us/free/](https://azure.microsoft.com/en-us/free/)  
   - Alternatively, create a Pay-As-You-Go account.

2. **Log In to the Azure Portal**  
   - Go to [https://portal.azure.com](https://portal.azure.com)

3. **Familiarize Yourself with the Azure Interface**  
   - Observe key sections like Resource Groups, Virtual Machines, and Entra ID.

4. **Create a Resource Group**  
   - Navigate to **Resource Groups** > **Create**  
   - Name it clearly (e.g., `storage-lab-rg`) and select a region.

5. **Create a Storage Account**  
   - Within the resource group created in Step 4  
   - Go to **Storage Accounts** > **Create**  
   - Provide a unique name and select the same region.

6. **Create a Text File on Your Local Machine**  
   - Open your text editor and write a simple message  
   - Save the file with `.txt` extension  
   - ⚠️ If on Mac, go to preferences and ensure the file is saved as **plain text**.

7. **Upload the File to Azure**  
   - Open your storage account in the Azure Portal  
   - Navigate to **Containers**, create one (e.g., `labfiles`), and upload the text file.

8. **Edit the File Inside the Portal**  
   - Use Azure's built-in editor to make changes to the uploaded text file.

9. **Download the File Back to Your Local Machine**  
   - Use the download option from within the storage container.

10. **Open and Observe the Changes**  
    - Confirm that edits made in Azure are reflected locally.

11. **Delete the Resource Group**  
    - Navigate to **Resource Groups**  
    - Select the group created in Step 4  
    - Click **Delete**, confirm the name, and proceed.

12. **Confirm Deletion**  
    - Ensure all associated resources (storage account, containers, files) are removed.

13. **(Optional) Check Billing Insights**  
    - Go to **Cost Management** → **Cost Analysis**  
    - Verify that no unexpected charges were incurred.

---

## 🧼 Best Practice Reminder:
> ⚠️ Always delete unused Azure resources like virtual machines and storage accounts to prevent unnecessary charges.
