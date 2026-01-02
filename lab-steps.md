# Active Directory Lab Step-by-Step

## Server Setup
1. Start Windows Server 2022 VM
2. Rename server to `DC01`
3. Set static IP (example: 192.168.56.10)
   - Subnet mask: 255.255.255.0
   - Default gateway: 192.168.56.1
   - Preferred DNS: 192.168.56.10

## Install Active Directory Domain Services
1. Open **Server Manager → Add Roles and Features**
2. Select **Active Directory Domain Services**
3. Click Install

## Promote Server to Domain Controller
1. Server Manager → ⚠️ flag → Promote this server to a Domain Controller
2. Add new forest → Domain: `lab.local`
3. Set DSRM password
4. Restart VM

## Verify Active Directory
1. Open **Active Directory Users and Computers (ADUC)**
2. Create user:
   - Name: John Doe
   - Username: jdoe
3. Create group:
   - Name: IT-Admins
   - Add jdoe to the group

## Client Machine
1. Configure client VM on same subnet
2. Join domain: `lab.local`
3. Test login as `jdoe`

## Optional
- Create Group Policies
- Document advanced configurations
- Add screenshots to `screenshots/` folder


