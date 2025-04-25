# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

## DESIGN STEPS:
### Step 1:
Install Autopsy using the terminal with the command(Kali Linux) or GUI application (windows)

### Step 2:
Launch Autopsy from the terminal or application menu and create a new case.

### Step 3:
Add a disk image or file to the case and analyze the contents such as deleted files, metadata, and folder structure.

## PROGRAM:
### **Install Autopsy for Windows (GUI-based Forensic Tool)**
🔗 **Download Autopsy**: [Click Here](https://www.autopsy.com/download/)  
1. Download the **Autopsy Windows Installer** from the official website.  
2. Extract the ZIP file and open the **bin** folder.  
3. Run `autopsy.exe` and set up a new forensic case for analysis.

### **Install Autopsy for Linux**
1. Open Terminal.
2. Update your package list: sudo apt update
3. Install Autopsy: sudo apt install autopsy
4. Launch Autopsy using: autopsy
5. Open http://localhost:9999/autopsy in a web browser.

### **Create & Configure a Virtual Hard Disk (VHD) in Windows**

1. Press **Win + X**, Select Disk Management.
2. Click Action > Create **VHD**.
3. Choose a location and set a disk size (e.g., 10GB+).
4. Select Fixed Size or Dynamically Expanding and click OK.
5. In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select **MBR**.
6. Right-click Unallocated Space → **New Simple Volume** → Format the disk -> Click next → Finish.


## OUTPUT:
### Autopsy for Windows
![image](https://github.com/user-attachments/assets/8c8802bc-ca88-4b73-b92a-381fef80bf6a)

### Autopsy for kali linux
![image](https://github.com/user-attachments/assets/01c09335-a61f-4260-95ac-f87095f5eed8)

![image](https://github.com/user-attachments/assets/f0f2f6a8-e53f-4707-934f-605d8a6a05d6)

![image](https://github.com/user-attachments/assets/a4496473-6f61-4e0d-a734-55c4e8a35b34)

![image](https://github.com/user-attachments/assets/0ec73b31-6581-4330-aeef-3f62ec03f970)

### Creating Virtual Disk:
![Screenshot 2025-04-25 090812](https://github.com/user-attachments/assets/509f703d-56c4-4ac1-85bf-75140c694ba0)

![Screenshot 2025-04-25 090841](https://github.com/user-attachments/assets/5f17d252-924c-4701-b325-a9c22ed69f6e)

![Screenshot 2025-04-25 091004](https://github.com/user-attachments/assets/af54c547-c1a3-456b-b2d4-b80efec290be)


### Analysing the disk file and configuration:
![image](https://github.com/user-attachments/assets/9197aff7-15b6-4f52-a9c9-a405a5a01d14)

### Timeline:
![image](https://github.com/user-attachments/assets/2ddc3bd5-e5b5-4d21-ab4f-201c0f2452f9)

![image](https://github.com/user-attachments/assets/1906828f-8a17-4ef8-b5a9-e42340ae2b8c)


## Data Source Summary Report:
![image](https://github.com/user-attachments/assets/f8cfafb5-effb-4737-824f-93499bc68aff)


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
