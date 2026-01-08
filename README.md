# 🛠️ Active Directory Home Lab (Windows Server 2022)

This is a hands-on Active Directory Domain Services (AD DS) lab for learning enterprise user/group management.

✅ Domain Controller: `DC01`  
✅ Domain: `lab.local`  
✅ Test Users & Groups created  
✅ Screenshots included for GitHub/portfolio

---

## 🚀 Quick Start
1. Start Windows Server 2022 VM
2. Rename server → `DC01`
3. Set static IP → e.g., 192.168.56.10
4. Install AD DS role
5. Promote server to Domain Controller
6. Create test users & groups
7. Join client VM to domain
8. Verify login

---

## 🎫 Test Users & Groups
- **User:** John Doe (`jdoe`)  
  **Group:** IT-Admins

- **User:** Jane Smith (`jsmith`)  
  **Group:** HR-Team

---

## 📸 Screenshots

### Server Setup
DC01 AD DS Installed  
![AD DS Installed](![DC01 AD DS Installed](https://github.com/user-attachments/assets/4c22841e-a849-45e7-9c77-1a2ccc959456)
/DC01_ADDS_Installed.png)

### Active Directory Users
![AD Users](screenshots/ADUC_Users.png)

### Test User Created
![Test User](screenshots/TestUser_jdoe.png)

### Client Joined Domain
![Client Joined](screenshots/ClientJoined.png)

---

## 🧰 Folder Structure

AD-Lab/
├─ screenshots/        # Lab screenshots
├─ notes/              # Notes and guides
├─ scripts/            # PowerShell or batch scripts
├─ README.md           # Project guide
├─ LICENSE             # MIT License
└─ .gitignore          # Files to ignore in Git


## 👤 Author
**Gokah William**


