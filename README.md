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

![image](https://github.com/user-attachments/assets/aa8d1949-5443-46cd-b071-070cb8ee5b99)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/87936bba-737b-428d-82ea-45c7139e3cf8)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/b8da55ce-0445-4a99-954b-98b97f861082)


- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/fdb86c22-b80f-4c42-9d99-6323fe938333)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/cff2ed1b-88fe-45f3-8a93-1bf64ad6e0ef)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![image](https://github.com/user-attachments/assets/5ad18bcf-1cae-4be7-bcff-1ab318a30fa0)

![image](https://github.com/user-attachments/assets/41ff7e56-b004-4bda-b5be-b58041ae58f6)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![image](https://github.com/user-attachments/assets/22b4a624-3cc8-40d7-9ac2-7ef1d5fe2750)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![image](https://github.com/user-attachments/assets/b026e3dd-18d6-4edb-84d2-078a12218250)

### Folder after deleting the files
![image](https://github.com/user-attachments/assets/83399dfe-9c1a-41b1-8a49-05537f9a8cb6)


### Folder after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/f5745f04-5009-4de9-80f5-6697e9a1741d)


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
