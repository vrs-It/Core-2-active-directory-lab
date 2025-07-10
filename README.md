# Core-2-active-directory-lab
A collection of Active Directory labs and video walkthroughs-from domain joins setups to GPO configuration-captured with real effort, real learning, and the occasional cameo from my bright yellow nails and overly ambitious time-lapse.  
# 📂 Active Directory (AD) — Core 2 Study Notes

## 🧠 What Is Active Directory (AD)?

**Active Directory** is a centralized database and service used in enterprise networks to manage users, computers, and permissions.

It is part of **Windows Server** and helps IT admins control access, apply policies, and secure the environment through domain-based structure.

---

## 🧾 Key Concepts

- **Domain Controller (DC):** The server that runs Active Directory services
- **Domain:** A group of networked systems under a shared directory/database
- **OU (Organizational Unit):** Logical containers for grouping users or devices
- **Group Policy (GPO):** Used to apply settings to users/devices in a domain
- **LDAP:** Protocol AD uses for querying and updating the directory
- **FQDN (Fully Qualified Domain Name):**
- Format: `hostname.domain.local` (e.g., `pc1.sales.company.local`)
- ---

## 🧪 Real-World Use Cases

| Scenario | Tool or Feature |
|----------|------------------|
| Join a machine to a domain | `System Properties` > `Change Settings` |
| Create/manage user accounts | Active Directory Users and Computers (ADUC) |
| Enforce password policies | Group Policy (GPO) |
| Organize departments | Organizational Units (OUs) |
| Authenticate login access | Domain credentials verified by DC |

---

## 🔐 Commands to Know

### Windows:
```powershell
net user /domain            # View domain user accounts
gpupdate /force             # Force Group Policy update
set /p                      # Can be used in scripts for prompts
```

### Linux (to test domain connections via ping):
```bash
ping domaincontroller.local
```

---

## 🛠️ How DHCP & DNS Tie into AD

- **DHCP** assigns IP addresses automatically
- **DNS** allows domain-joined devices to locate the Domain Controller (e.g., to log in or join domain)

---

## 🎥 Attached Lab Videos

> Upload your videos to your GitHub repo (`/videos` folder or use Git LFS)

Example embed with YouTube:
```markdown
### Lab: Joining a Windows VM to AD Domain
[![Join Domain Lab](https://img.youtube.com/vi/your_video_id/0.jpg)](https://www.youtube.com/watch?v=your_video_id)
```

Or direct file link:
```markdown
📹 [Watch Lab Video: AD Domain Join](videos/AD_DomainJoin.mp4)
```

---

## 🧩 Related Concepts

- Domain vs Local Accounts
- FQDN vs Hostname
- Group vs User Permissions
- NTFS & Share Permissions
- Backup Domain Controllers (BDC)
- SYSVOL & NETLOGON folders

---

## 📎 Study Tip

Understand how AD connects with:
- **Windows Command Line**
- **Disk and User Management Tools**
- **Security Policies**
- **Networking (DNS, DHCP)**



https://github.com/user-attachments/assets/4dbf4201-2267-490a-b393-e0204403561d



https://github.com/user-attachments/assets/170574ad-936a-48c1-9aac-761800b90c9a


