


# 🛠️ Active Directory Home Lab (Windows Server 2022)

A hands-on **Active Directory Domain Services (AD DS)** lab for learning enterprise user and group management in a Windows Server environment.

✅ **Domain Controller:** `DC01`  
✅ **Domain:** `lab.local`  
✅ **Test Users & Groups:** Created  
✅ **Screenshots included** for GitHub/portfolio showcase  

---

## 🚀 Quick Start Guide

Follow these steps to set up your lab environment:

1. Start your **Windows Server 2022 VM**.  
2. Rename the server → `DC01`.  
3. Set a **static IP address** (e.g., `192.168.56.10`).  
4. Install the **Active Directory Domain Services (AD DS)** role.  
5. Promote the server to a **Domain Controller**.  
6. Create **test users and groups**.  
7. Join a **client VM** to the domain.  
8. Verify successful **domain login**.  

---

## 🎫 Test Users & Groups

| User       | Username | Group      |
|------------|----------|------------|
| John Doe   | jdoe     | IT-Admins  |
| Jane Smith | jsmith   | HR-Team    |

---

## 📸 Screenshots

### Server Setup
**DC01 AD DS Installed**  
(![DC01 AD DS Installed](https://github.com/user-attachments/assets/70593ae7-478b-44df-b903-f629e7c4d0f3)
/DC01_ADDS_Installed.png)  

### Active Directory Users
![Active Directory Users](<img width="790" height="502" alt=" Active Directory Users" src="https://github.com/user-attachments/assets/e20f5b22-9450-4624-a244-6e513a866c90" />
/ADUC_Users.png)  

### Test User Created
![Test User Created](<img width="761" height="539" alt="Test User Created" src="https://github.com/user-attachments/assets/e4b70656-28c0-436d-815a-da19ffbb05d3" />
/TestUser_jdoe.png)  

### Client Joined Domain
![Client Joined Domain](<img width="859" height="654" alt="Client Joined Domainpng" src="https://github.com/user-attachments/assets/70296b38-1194-4d8f-ab32-d17a58c4dd8e" />
/ClientJoined.png)  



---

## 🧰 Folder Structure

```text
AD-Lab/
├─ screenshots/        # Lab screenshots (placeholders)
├─ notes/              # Notes and guides
├─ scripts/            # PowerShell or batch scripts
├─ README.md           # Project guide
├─ LICENSE             # MIT License
└─ .gitignore          # Files to ignore in Git
