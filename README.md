# Surveying and Preserving the Digital Crime Scene

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.
` ![image](https://github.com/user-attachments/assets/bc7785cd-d9cb-4eed-913e-be53b7715344) 
- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**. 
- ![image](https://github.com/user-attachments/assets/cb4d9f43-6976-483e-b1e1-f1fe67b75e8f)
- ### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**
![image](https://github.com/user-attachments/assets/5fd7d364-fa4d-4c5b-b3ac-5734073fab05)
- Select **Local Disk** → **next**
- ![image](https://github.com/user-attachments/assets/b9205035-45a6-4f85-8329-83441e4d7b34)
 Select Disk → **Choose the VHD drive (`Drive1`)**
![image](https://github.com/user-attachments/assets/31068bf6-3a28-449e-85c7-6cb293d408e8)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).
![image](https://github.com/user-attachments/assets/db580ed6-d75e-43e1-8612-143a18122312)
![image](https://github.com/user-attachments/assets/6c49c60e-a367-4052-ae68-9bc994b6a6ce)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.
- ![image](https://github.com/user-attachments/assets/ddb19aef-b88d-4409-b8a2-44845f4ce6f3)

 Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.
## Output :
### Folder before deleting the files
![image](https://github.com/user-attachments/assets/dcc27727-d84e-4b10-9ec6-a86b2179d494)

### Folder after deleting the files
![image](https://github.com/user-attachments/assets/de3193d8-6370-418a-9729-fad7dc20de7f)

### Folder after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/7b73ec71-df3a-4df7-b724-3faa46bb024f)

## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.


 

