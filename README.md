# 📡 Converting an ADSL Router into an FTP Server Using a USB Drive

## 📖 Overview
This guide explains how to configure an ADSL router (e.g., Huawei HG633) as an FTP server using a USB flash drive.  
This setup allows you to store and access media files such as **MP3, PNG, and MP4** across your network.

---

## 💾 Step 1: Prepare the USB Flash Drive

I haved Plug the USB in my laoptop  

This is the flash drive I will be working on contains  
A collection of files such as:

- MP3  
- PNG  
- MP4 file  

I can post any media files.

### 🔧 Verify File System

- Right click on the USb → select **Properties**
- Ensure the USB File System is **NTFS**

---

## 🔌 Step 2: Connect USB to the Router

Now I will remove the flash drive from the computer and connect it With router  

---

## 🌐 Step 3: Log in to Router Interface

- Open **Google Chrome**

I have the Huawei HG633 router  

- Enter the router login page:
```

192.168.1.1
```

- It will asked for the login credential  

I will write the username and password:  
```

username: admin
password: ********
```

- Click **Login**

---

## ⚙️ Step 4: Enable FTP Service

- Navigate to: **Share**
- Click on: **Storage Share**

- Click on the radio button to enable:
  - ✅ **Enable FTPS**

- Click **Save**

---

## 👤 Step 5: Configure FTP User Access

- Go to **User Setting**
- Click on **New USB User**

And make a user who can use the FTP access and write  

- Provide:
  - Username  
  - Password  

Whether:
- Read Only  
- Read and Write  

Then:

- Press **Save**

---

## 🎬 Step 6: Enable Multimedia Sharing

- Click on **Multimedia Share**

- Enable:
  - ✅ **Enable DMS**

- Select:
  - 🔘 **Share all directories**

```

DNS Name: Broadband router

```

- Click **Save**

After sucessfully save, it will show a pop up message as:  
> "your data has been saved."

---

## 🖥️ Step 7: Add Router as a Network Device

- Open **Control Panel**
- Go to **Devices and Printers**

- Click on **Add a device**
- Choose **Everything else**

Wait for a moment and you can see our ftp router name appeared as:  
```

broadband router

```

- Click on: **broadband router**

After sucessfull connecting to it:

- Click **Done**

---

## 📁 Step 8: Access Shared Files

- Open **This PC**
- Navigate to:
```

Network Location → broadband router

```

- Open **broadband router**

It will show our previous files:
- MP3  
- PNG  
- MP4 file  

---

## ▶️ Step 9: Use Media Files

now you can access the video  

- I can play the video file via the Internet  
- If you go to the picture, I will be able to open the image  
- If you go to the first music, you will find it mp3 file  

---

## ✅ Conclusion

You have successfully configured your ADSL router as an FTP server using a USB drive.  
This allows easy access to media files across your network.

---
