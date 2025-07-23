<img width="693" height="370" alt="microsoft azure logo" src="https://github.com/user-attachments/assets/06a147e6-f24e-436a-abc7-b67227d4ce67" />

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

CONFIGURATION STEPS

<img width="1910" height="880" alt="Azure portal" src="https://github.com/user-attachments/assets/410f8721-53ba-48e0-acd2-0d25d82a3076" />

## Azure Portal Overview – Starting Configuration

![Azure Portal - Configuration Steps Overview](https://user-images.githubusercontent.com/YOUR_IMAGE_LINK.jpg)

This screenshot displays the **Microsoft Azure Portal** landing page, specifically highlighting the **Azure services** section used to begin resource setup and management.

### Key Elements Displayed:
- **Create a resource**: Entry point for launching any new Azure service (e.g., VMs, storage, databases).
- **Virtual machines**: Shortcut to manage or create virtual machines.
- **Storage accounts**: Used to access Azure Blob/File/Table/Queue storage services.
- **Resource groups**: Central management containers for logically grouping related resources.
- **Microsoft Entra ID**: Identity management section (formerly Azure Active Directory).
- **Cost Management**: Budgeting, cost analysis, and usage reporting.
- **Quickstart Center**: Guided onboarding for Azure beginners.
- **Dashboard**: Customizable workspace to pin and view Azure resources.

The lower section confirms that **no resources have been viewed recently**, indicating a fresh or reset user session.

### Purpose of This Screen

This view acts as the **launchpad** for nearly all Azure lab configurations. From this page, users can:
- Create and manage core infrastructure like resource groups and storage accounts
- Begin tracking and budgeting costs via the Cost Management service
- Access recently used items or navigate to subscriptions and dashboards

This interface is commonly used as the first step when setting up environments for hands-on labs, cloud application deployments, or cost optimization exercises.

<img width="1915" height="885" alt="Creating a resource group" src="https://github.com/user-attachments/assets/5358a412-f06c-4306-abb4-95486ba311ff" />









<img width="1919" height="878" alt="Resource group created" src="https://github.com/user-attachments/assets/70adfc4d-5674-4a49-b324-fe8c0325e712" />








<img width="1904" height="865" alt="before creating a storage account" src="https://github.com/user-attachments/assets/f37e816f-e8cd-4cfc-b32a-3a5e2bce4911" />









<img width="1908" height="870" alt="after creating a Storage Account which resides inside of the resource group" src="https://github.com/user-attachments/assets/c3cc15a1-1062-4dd9-9661-48550a87ac6e" />







<img width="1505" height="830" alt="text file that was created" src="https://github.com/user-attachments/assets/cdafff3e-21fd-4329-9f0e-be32e1496d6b" />







<img width="1902" height="871" alt="create a text file and upload it to your Azure storage account" src="https://github.com/user-attachments/assets/5fe5af2d-a445-46c5-9449-5ecef05c1837" />






<img width="1905" height="834" alt="view or edit the file created inside storage account earlier" src="https://github.com/user-attachments/assets/31145fb7-0810-4685-ad92-5528b61d9248" />






<img width="1881" height="853" alt="editing the file , downloading and watching the changes" src="https://github.com/user-attachments/assets/fab2befb-7b21-4c30-bcc1-cbfa2444e10c" />





<img width="1884" height="855" alt="the file has been downloaded as azurelab 2" src="https://github.com/user-attachments/assets/50a7513c-6b0b-4521-aa0a-d99f7e5a0f70" />





<img width="1886" height="865" alt="deleting resouce group created in previous steps" src="https://github.com/user-attachments/assets/939dc313-b53d-47ac-9c8f-9ff3a7c0d1ef" />




















