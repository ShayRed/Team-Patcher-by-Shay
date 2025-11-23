# Information

**Important:**  
This tool is intended **only for team use**, **not** as a live patcher.  
Its purpose is to make file management and collaboration between team members easier.

---

# Instructions

## Step 1

1. Upload the three included folders to your server:  
   - `Client`  
   - `Client_SRC`  
   - `Proto`  

2. Once the upload is complete, you can delete these folders from your desktop or local storage.

---

## Step 2

1. Click on **Patch List** in the tool and select the folders you want to prepare for patching.  
2. Explanation:  
   - Files from **Client_SRC** go into the `Client_SRC` folder on the server.  
   - Files from **Client** go into the `Client` folder.  
3. The **patchlist.txt** file is always saved in the folder you prepared for patching (e.g. `Client_SRC`).

---

## Step 3

In the **Update Options**, you can select which section the prepared patch is for.

---

# Notes

- Under **Server IP Address**, enter your (Apache) server’s IP.  
- The patcher automatically creates a **config.txt** file that stores your IP address.  
  You can edit this file manually at any time.
