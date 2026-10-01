# Module-01: create, configure and manage identities

## Subjective Summary
microsoft Entra ID is cloud-based Identity and Access Management service (IAM) that helps manage the identity and access of users and data. Transitioning workloads to cloud isn't just about moving servers, websites and data. Companies needs to ensure that these resources are secured by defining authentication to users. Ensuring users have access to only the resources they need to have access to. Also ensuring that users perform roles and responsibilities assigned to them to perform. Cloud workload access, can be done in two ways; firstly by providing definitive identity to each users they use for every service, seconding by ensuring employees and vendor have enough access to their jobs.


## Unit 1: Create, configure and manage users
## Task
I created my first user named "Chris Green". <img width="1918" height="850" alt="Screenshot 2026-09-30 122328" src="https://github.com/user-attachments/assets/ade52bee-91de-443e-b212-a3b725afc53c" />

## Unit 2: Create and configure security Group
## Task
Here I created a security group named "marketing", assigned myself the group owner role, and also assigned the user "Chris Green" as the group member. <img width="1919" height="915" alt="Screenshot 2026-09-30 122647" src="https://github.com/user-attachments/assets/12911e34-4f9b-438c-8005-8a4ed1ab837d" />

## Unit 3: Assign License to the security group
## Task
The provisioned virtual Microsoft Entra ID is basically for beginner practice; hence, I don't have access to a purchased Microsoft license that I can assign to users in my organization or tenant. 

However, the process is quite simple: open the Microsoft Entra admin center, navigate left, scroll down, select billing, and under billing select license. Then assign the available/purchased license to identities such as groups or users. <img width="1912" height="924" alt="Screenshot 2026-09-30 130639" src="https://github.com/user-attachments/assets/daa97c4a-2b6c-40ca-aef8-6f824a22fed9" />

### Unit 4: Restore or Remove Deleted Users
## Task
* **Concept:** Deleted users are held in a temporary "Deleted users" folder for a 30-day grace period.
* **Action:** Restored a deleted user profile, recovering all original properties before the 30-day permanent deletion threshold.. <img width="1911" height="983" alt="Screenshot 2026-09-30 124010" src="https://github.com/user-attachments/assets/d9f5c6fc-5598-44b4-a9fb-533283a50198" />

### Unite 5: Create, configure and manage groups
* *Concept* Microsoft entra group helps to organize users, it is the easiest way to manage user permissions. As stated earlier, the objective of the company is to protect cloud based workloads and by so doing microsoft entra groups draws us closer to that. In microsoft Entra there are two sets of groups; the security group and the microsoft 365 group. The security group is only available to administrators while that of of microsoft 365 is available to both users and admins.

* 
## Task
Here I created a microsoft 365 group using the "assigned" membership type <img width="1916" height="909" alt="Screenshot 2026-09-30 140756" src="https://github.com/user-attachments/assets/40fdf7ca-7e64-4f96-b659-ced2a6ebd0c6" />

### Unit 6: Configure and manage device registrations
Microsoft Entra ID helps organizations manage users, devices, and access to organizational resources while maintaining security. Microsoft Intune can be used to enforce device security and compliance policies.
* *Key Concepts* 
* *Microsoft Entra Registered:* Primarily for personal/BYOD devices. The device remains signed in with a local/personal account but is connected to Entra ID for access to organizational resources.
*Example:* Using a personal laptop to access company email.
* *Microsoft Entra Joined:* Primarily for organization-owned devices. Users sign in directly with their organizational Entra ID account.
*Example:* Signing into a company Windows laptop with a work account.
* *Hybrid Microsoft Entra Joined:* Used when an organization has both on-premises Active Directory and Microsoft Entra ID. The device is connected to both systems.
*Example:* A company continuing to use Group Policy and Active Directory while adopting cloud services.
* *Microsoft Intune:* Manages and secures devices by enforcing policies such as encryption, strong passwords, software updates, and compliance requirements.
* *Conditional Access:* Controls access to organizational resources based on conditions such as user identity, device compliance, and security status.

## Key Takeaway
*Registered = Personal/BYOD device*
*Joined = Organization-owned device*
*Hybrid Joined = On-premises AD + Entra ID*

**Verified Achievement:** I have successfully completed the official Microsoft Learn module assessment. You can verify my badge and module completion transcript directly via the official [Microsoft Learn Achievement Verification Link](https://learn.microsoft.com/api/achievements/share/en-us/AKATAOBICHIMEZIEPETER-5627/U75UEFT3?sharingId=3165879800C3B91C).







 






