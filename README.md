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

## 🔧 Prerequisites

Before beginning this Azure lab, ensure the following requirements are met:

- A valid Microsoft account for Azure access  
- A free Azure subscription or Pay-As-You-Go option  
- Access to the [Azure Portal](https://portal.azure.com)  
- A computer with internet access  
- A local text editor (e.g., Notepad or VS Code) to create and modify `.txt` files  
- Browser access to view Azure Storage resources  
- If using macOS: ability to adjust text editor settings (e.g., plain text mode)  
- Basic familiarity with navigating the Azure Portal (Resource Groups, Storage Accounts)

---

## 🛠️ Installation Steps

Follow these 12 step-by-step instructions to complete your Azure storage lab.

1. **Sign into the Azure Portal**  
   <img width="1910" height="880" alt="Azure portal" src="https://github.com/user-attachments/assets/410f8721-53ba-48e0-acd2-0d25d82a3076" /> 
Go to [https://portal.azure.com](https://portal.azure.com) and log in with your Microsoft account.

2. **Create a New Resource Group**  
   <img width="1915" height="885" alt="Creating a resource group" src="https://github.com/user-attachments/assets/5358a412-f06c-4306-abb4-95486ba311ff" />
Click **Resource groups** → **+ Create**.  
Name the resource group `Lab-Test-Anthony`, select your subscription and region, then click **Create**.

3. **Verify the Resource Group Was Created**  
 <img width="1919" height="878" alt="Resource group created" src="https://github.com/user-attachments/assets/70adfc4d-5674-4a49-b324-fe8c0325e712" />
Return to **Resource groups** and check that `Lab-Test-Anthony` appears in the list.

4. **Create a Storage Account**  
 <img width="1904" height="865" alt="before creating a storage account" src="https://github.com/user-attachments/assets/f37e816f-e8cd-4cfc-b32a-3a5e2bce4911" />
Click **Storage accounts** → **+ Create**.  
Choose the same resource group and complete the fields to set up the storage account.

5. **Create a Local Text File**  
 <img width="1505" height="830" alt="text file that was created" src="https://github.com/user-attachments/assets/cdafff3e-21fd-4329-9f0e-be32e1496d6b" /> 
Open Notepad on your computer.  
Type `Hello` and save the file as `azure-lab.txt`.

6. **Create a Container in the Storage Account**  
   <img width="1902" height="871" alt="create a text file and upload it to your Azure storage account" src="https://github.com/user-attachments/assets/5fe5af2d-a445-46c5-9449-5ecef05c1837" />
In your storage account, go to **Containers** → **+ Container**.  
Enter the name `labtest` and click **Create**.

7. **Upload the Text File to the Container**  
 <img width="1905" height="834" alt="view or edit the file created inside storage account earlier" src="https://github.com/user-attachments/assets/31145fb7-0810-4685-ad92-5528b61d9248" />
Select the `labtest` container.  
Click **Upload** and choose the `azure-lab.txt` file from your computer.

8. **Verify That the File Was Uploaded**  
 <img width="1908" height="870" alt="after creating a Storage Account which resides inside of the resource group" src="https://github.com/user-attachments/assets/c3cc15a1-1062-4dd9-9661-48550a87ac6e" />
Check that `azure-lab.txt` is now listed inside the `labtest` container.

9. **Edit the File in Azure**  
 <img width="1881" height="853" alt="editing the file , downloading and watching the changes" src="https://github.com/user-attachments/assets/fab2befb-7b21-4c30-bcc1-cbfa2444e10c" />
Click on `azure-lab.txt` → go to the **Edit** tab.  
Type `goodbye` below `Hello` and save your changes.

10. **Confirm File Was Updated**  
 <img width="1884" height="855" alt="the file has been downloaded as azurelab 2" src="https://github.com/user-attachments/assets/50a7513c-6b0b-4521-aa0a-d99f7e5a0f70" />
Open `azure-lab.txt` again in the Azure portal.  
Both lines `Hello` and `goodbye` should now appear.

11. **Delete the Resource Group**  
<img width="1886" height="865" alt="deleting resouce group created in previous steps" src="https://github.com/user-attachments/assets/939dc313-b53d-47ac-9c8f-9ff3a7c0d1ef" />
Go to **Resource groups** → click `Lab-Test-Anthony`.  
Click **Delete resource group**, confirm the name, and proceed.







   

















