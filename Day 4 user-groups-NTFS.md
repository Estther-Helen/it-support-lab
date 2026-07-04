# Day 4 – Users, Groups and NTFS Permissions

## Objective

The purpose of this lab was to understand how Windows manages users, groups, and file permissions. I also explored Access Control Lists (ACLs) and learned how permissions are assigned to files and folders.

---

## Commands Used

### Display Local Users

```powershell
Get-LocalUser
```

This command displays all local user accounts configured on the computer.

---

### Display Local Groups

```powershell
Get-LocalGroup
```

This command shows all groups available on the system.

---

### Display Members of the Administrators Group

```powershell
Get-LocalGroupMember Administrators
```

This command displays users that belong to the Administrators group.

---

### Create a New File

```powershell
New-Item -Path C:\Users\Pc\Desktop\Admin-Lab\TestFile.txt -ItemType File
```

This command creates a new file called TestFile.txt inside the Admin-Lab folder.

---

### View Folder Permissions

```powershell
Get-Acl C:\Users\Pc\Desktop\Admin-Lab
```

This command displays the Access Control List (ACL) for the folder.

---

## Output Observations

* The built-in Administrator account is disabled.
* My user account (Pc) is enabled.
* My account belongs to the Administrators group.
* The Admin-Lab folder is owned by DESKTOP-GUOMNMA\Pc.
* The SYSTEM account has Full Control permissions.

---

## Key Concepts Learned

### User Accounts

Users are accounts that allow individuals to access and use a computer system.

Examples:

* Administrator
* Guest
* DefaultAccount
* Pc

---

### Groups

Groups are collections of users used to simplify permission management.

Examples:

* Administrators
* Users
* Guests
* Backup Operators
* Remote Desktop Users

---

### NTFS Permissions

NTFS permissions determine what actions users can perform on files and folders.

Common permissions include:

* Read
* Write
* Modify
* Full Control

---

### Access Control List (ACL)

An Access Control List contains information about which users and groups have access to a resource and the permissions assigned to them.

---

### File Ownership

Every file or folder has an owner. The owner can manage permissions and control access to the resource.

---

## Importance to System Administration

System administrators use users, groups, and permissions to:

* Secure files and folders.
* Control access to resources.
* Manage user privileges.
* Protect sensitive information.
* Implement the principle of least privilege.

---

## Conclusion

This lab improved my understanding of user management, group management, NTFS permissions, and Access Control Lists in Windows. These concepts are fundamental to Windows System Administration and are also applicable to Active Directory, Linux permissions, AWS IAM, and Azure RBAC.



