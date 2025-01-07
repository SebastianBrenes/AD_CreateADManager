<p align="center">
<img src="https://i.imgur.com/chjNHqp.png" height="50%" width="50%" alt="ManageEngine ADManager Plus logo"/>
</p>

# Creating Users and Groups (ManageEngine ADManager Plus)

This guide provides a step-by-step process for creating users and groups in ManageEngine ADManager Plus. Follow the instructions below to simplify user and group management in Active Directory.

---

## Tools and Technologies Used

- **Platform**: ManageEngine ADManager Plus
- **Dependencies**: Active Directory Integration

---

## Operating Systems Used

- **Operating System**: Windows Server 2019/2022

---

## Overview of Steps

1. **Access the ADManager Plus Console**  
   - Log in to the web interface.

2. **Navigate to User Creation Settings**  
   - Access the options for creating new users.

3. **Create a Single User**  
   - Define user properties and attributes.

4. **Create Multiple Users**  
   - Use bulk user creation features.

5. **Navigate to Group Creation Settings**  
   - Access the options for creating new groups.

6. **Create and Configure Groups**  
   - Define group properties and assign users.

7. **Validate User and Group Creation**  
   - Confirm that users and groups were created successfully.

---

## Configuration Steps

### Step 1: Access the ADManager Plus Console

- **Action**: Log in to the ManageEngine ADManager Plus web interface using admin credentials.

<p align="center">
<img src="" height="75%" width="100%" alt="Accessing ADManager Plus console"/>
</p>

---

### Step 2: Navigate to User Creation Settings

- **Action**:  
  - Go to **Management > User Management > Create Single User**.  
  - Alternatively, select **Bulk User Creation** for creating multiple users.

<p align="center">
<img src="" height="75%" width="100%" alt="User creation settings"/>
</p>

---

### Step 3: Create a Single User

- **Action**:  
  - Fill in required details such as:  
    - **User Logon Name**  
    - **First Name**  
    - **Last Name**  
    - **Email Address**  
  - Assign the user to a specific Organizational Unit (OU).

<p align="center">
<img src="" height="75%" width="100%" alt="Single user creation"/>
</p>

---

### Step 4: Create Multiple Users

- **Action**:  
  - Use the bulk user creation feature by importing a CSV file with user details.  
  - Map CSV fields to AD attributes and validate the entries.

<p align="center">
<img src="" height="75%" width="100%" alt="Bulk user creation"/>
</p>

---

### Step 5: Navigate to Group Creation Settings

- **Action**:  
  - Go to **Management > Group Management > Create Groups**.

<p align="center">
<img src="" height="75%" width="100%" alt="Group creation settings"/>
</p>

---

### Step 6: Create and Configure Groups

- **Action**:  
  - Define group properties such as:  
    - **Group Name**  
    - **Group Scope**: Global, Domain Local, or Universal.  
    - **Group Type**: Security or Distribution.  
  - Add users to the group during creation or modify group membership later.

<p align="center">
<img src="" height="75%" width="100%" alt="Group creation"/>
</p>

---

### Step 7: Validate User and Group Creation

- **Action**:  
  - Use the **Reports** section in ADManager Plus to confirm:  
    - Newly created users are listed in their assigned OUs.  
    - Group memberships are accurate.

<p align="center">
<img src="" height="75%" width="100%" alt="Validation of users and groups"/>
</p>

---

## Summary

This tutorial covered:  

- **User Creation**: Creating single and bulk users with proper attributes.  
- **Group Creation**: Setting up groups and assigning users.  
- **Validation**: Ensuring proper configuration and visibility in Active Directory.  

With these steps, you can effectively manage users and groups in Active Directory using ManageEngine ADManager Plus, enhancing your organization's IT administration efficiency.
