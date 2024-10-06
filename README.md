# ByteSave
ByteSave is a application that  is tailored to do recovery of deleted files in BTRFS and XFS file systems.  
Designed with modern standards, ByteSave gives a comprehensive and easy to understand QT Interface for navigation.  
Also provides with a intuitive reports generation and courrputed files restoration using modern techniques such as Semantic Carving.  

---

### Here's how to use it. 


1. Select the files you want to be restored (after selecting the partition).
![image](https://github.com/user-attachments/assets/a0b3a1f3-892a-46c8-a101-50a6debd85e7)

2. Click on ByteSave to check the recovery status of files. 
![image](https://github.com/user-attachments/assets/4e775e0a-c7d0-498f-b5ad-9b433effe1e7)

3. You can now restore the files using command line or in app  

```bash
bytesave recover --device /dev/sdX -v
```
here `recover` is a must flag, `--device` gives the device (Note replace X with your parition number running btrfs / xfs)  
pass `-v` for verbose output. 

---
