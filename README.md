<h1> Active Directory: Organizational Unit (OU) Management & Domain Setup </h1>


<p>Welcome to the "Active Directory Organizational Unit (OU) Management & Domain Setup" project. In this project, we'll  </p>

-  

<h2>Environments and Technologies Used</h2>

- Hyper-V (Virtual Machines/Compute)
- Remote Desktop
- Active Directory

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 11 (23H2)


<br>



<h1>Organizational Unit (OU) Management</h1>

<h3>Step 1: </h3>
<p>First we will be creating any new OUs, users and groups that are relevant to changes within the company such as new teams, departments or employees </p>

- in this example, we have created a OU named 'CORP'. This will nest our other OUs that will contain our objects such as users and groups.
- in this case, we have security groups for departments such as finance and marketing and users for employees in each department.

![1](https://github.com/user-attachments/assets/6cfc904c-8828-4b03-90ce-fd39f509e9b3)

____

![2](https://github.com/user-attachments/assets/43839d64-2072-4d43-a04e-1e7cd7a3b707)


____


<h3>Step 2: </h3>
<p>Second we will be adding users to the appropriate groups </p>

- 

![3](https://github.com/user-attachments/assets/48c9dbcd-26d5-4abb-942a-fb2165b6e2f6)



____


<h3>Step 3: joining the client devices to the domain; log into the local admin account on the device </h3>
<p> </p>


![1](https://github.com/user-attachments/assets/42b21543-8c8a-4ac3-8687-97206f453d0f)


____


![2](https://github.com/user-attachments/assets/6dec5922-4bf0-4995-8647-840cf0c88d02)


____


![3](https://github.com/user-attachments/assets/96ec8827-4f78-45ce-a9bd-987510e5a8ee)


____


log into a domain account with the permission to connect to the domain (ex. lab admin in domain admin group)


![4](https://github.com/user-attachments/assets/3af805c2-aeef-45f2-b348-7cfd669ee256)


____


skip adding a user account as we will be logging in with our domain user account (ex. testuser1)


![5](https://github.com/user-attachments/assets/cff70d5e-422d-4d26-8886-962a1a20f0df)


____





![6](https://github.com/user-attachments/assets/af04abee-6998-4dd5-8e22-2d67550eb43c)


____

verify you are connected to the domain name

![7](https://github.com/user-attachments/assets/11ee7c68-fb66-4cb6-8240-fbc476f38ea3)


____
<h3>Step 4: enabling Remote Desktop on the devices via groups such as domain users </h3>
<p> </p>

<br>

log back into the client's local admin user account (ex. administrator on CLIENT1) or a domain admin account (ex. lab admin on CORP)

![8](https://github.com/user-attachments/assets/f45049e6-232d-411c-b85a-1f6ebff4768b)



____


![9](https://github.com/user-attachments/assets/b2703a48-9189-4712-aad6-ff027020954f)


____

enable remote desktop; then press "Remote Desktop Users" to add users or groups; you will need a domain account with admin credentials (ex. labadmin)


![10](https://github.com/user-attachments/assets/e02b4356-6bc0-4601-b515-51d32d3bd8f3)


____

![11](https://github.com/user-attachments/assets/45e3dfff-5b02-42fd-b4bf-6b92e20a4f46)


____
you can add or remove users or groups from the remote desktop users for this device from here

![12](https://github.com/user-attachments/assets/4bcabd40-7c77-4f7b-b4ff-023b1fa1cb05)



____


![13](https://github.com/user-attachments/assets/f021b201-c197-470b-a01b-fa1105e01048)



____




____
<br>

____




<br>



<h2> Final Thoughts </h2>

<p> In closing, the "Active Directory Organizational Unit (OU) Management" project streamlines our  .</p>

