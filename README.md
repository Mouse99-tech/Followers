###Termux Use Comment's

---
### **1. Update & Upgrade Termux**  

-`pkg update && pkg upgrade -y`
---
### **2. Install Essential Packages**  
```
-`pkg install git curl wget nano -y`
---
### **3. File & Directory Management**  
-`ls`          # List files and folders  
-`cd foldername`  # Navigate to a folder  
-`mkdir myfolder`  # Create a new folder  
-`rm filename`  # Delete a file  
-`rm -rf foldername`  # Delete a folder  
---
### **4. Text Editing (Using Nano Editor)**  
-`nano myfile.txt`  # Create & edit a file  
-`cat myfile.txt`  # View file content  
---
### **5. Install & Run Python**  

-`pkg install python -y`
-`python --version`  # Check installation  
-`python`  # Start Python  
```
---
### **6. Clone a Project from GitHub**  
-`git clone https://github.com/username/repository.git`
-`cd` repository
-`ls`
---
### **7. Run Bash Scripts**  
-`chmod +x script.sh`
-`./script.sh`

---

### **8. Download Files from the Web**  

-`wget https://example.com/file.zip`
-`curl -O https://example.com/file.zip`
---
### **9. Port Forwarding (Using Ngrok or Serveo.net)**  
-`pkg install openssh -y`
-`ssh -R 80:localhost:8080 serveo.net`

---
