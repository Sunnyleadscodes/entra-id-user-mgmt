# entra-id-user-mgmt
Hands-on lab project demonstrating how to create and manage Microsoft Entra ID groups, users, and role assignments in the Azure portal. Includes step-by-step documentation and screenshots.
# Create and Manage Microsoft Entra ID Groups

## 📖 Introduction

Microsoft Entra ID is a central platform for managing identities and access within Azure. In this hands-on exercise, I practiced creating and managing **security groups** to simulate an internship program scenario. This included building a group, adding members, creating a new user, and assigning ownership — all tasks relevant for IAM and Azure administration.

---

## 🛠️ Lab Objectives

* Navigate to Microsoft Entra ID in the Azure portal.
* Create a new security group for an internship program.
* Add an existing user as a member.
* Create a new Entra ID user account.
* Assign the new user as a group owner.

---

## 🚀 Steps Performed

### 1. Create a Security Group

* Logged in to the Azure portal.
* Navigated to **Entra ID → Groups → New group**.
* Configured the group as:

  * Group type: Security
  * Name: Internship Program
  * Description: Group for interns and mentors
* Created the group successfully.

### 2. Add an Existing User

* Opened the **Internship Program** group.
* Went to **Members → Add members**.
* Added `Cloud Student` as a group member.
* Verified membership in the list.

### 3. Create a New User

* Navigated to **Entra ID → Users → New user**.
* Entered details:

  * User principal name: `cloudinternmentor`
  * Display name: Cloud Intern Mentor
* Completed the creation and confirmed user appeared in the directory.

### 4. Assign Group Owner

* Opened the **Internship Program** group.
* Navigated to **Owners → Add owners**.
* Assigned `Cloud Intern Mentor` as an owner.
* Verified ownership was applied correctly.

---

## ✅ Key Learnings

* Learned how to **create and configure security groups** in Microsoft Entra ID.
* Practiced adding both existing and newly created users.
* Understood how to delegate management by assigning group ownership.
* Reinforced identity and group management concepts useful for **AZ-104 and SC-300 certification prep**.

---

## 🏆 Conclusion

This exercise strengthened my ability to manage groups and users in Microsoft Entra ID. I gained hands-on experience in creating, assigning, and verifying group roles, which are critical tasks for IAM and Azure administrators.
