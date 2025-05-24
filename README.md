# AWS IAM Practical Projects

## 📘 Overview

This repository contains four hands-on AWS IAM practical projects demonstrating key Identity and Access Management (IAM) features. Each project includes screenshots and step-by-step tasks involving user/group/role creation, policy assignment, and access validation using both the AWS Management Console and AWS CLI.

---

## 🧰 Tools & Services Used

- **AWS IAM** (Users, Groups, Roles, Policies)
- **Amazon EC2**
- **Amazon S3**
- **AWS CLI**
- **MFA (Multi-Factor Authentication)**

---

## 📁 Project Structure

### 📂 1. IAM Group and User Management with EC2 Access

This project shows how to create an IAM group, attach a predefined EC2 full access policy, create a user, and add the user to the group.

#### 🔧 Steps:
1. **Group Creation** – `01-Group-Creation.png`
2. **Attach EC2FullAccess Policy to Group** – `02-Attach-Permission-Group-EC2Full.png`
3. **User Creation** – `03-User-Creation.png`
4. **Add User to Group** – `04-User-Added-to-Group.png`

---

### 📂 2. IAM User, MFA, and EC2 Launch via CLI

This project includes user creation, enabling MFA, creating and configuring an IAM user with CLI access, and launching EC2 instances from the CLI.

#### 🔧 Steps:
1. **Another User Creation** – `01-Another-User-Creation.png`
2. **EC2FullAccess to New User** – `02-EC2FullAccess-Permission-Another-User.png`
3. **Set Console Password** – `03-Console-Password-to-User.png`
4. **Create MFA Device** – `04-MFA-Creation.png`
5. **Scan with Authenticator App** – `05-Scan-Authenticator-App.png`
6. **Create Access Key** – `06-Access-Key-Creation-CLI.png`
7. **Access Key Details** – `07-Access-Key-Created.png`
8. **Configure AWS CLI** – `08-AWS-Configure-CLI.png`
9. **Login to IAM User** – `09-Sign-In-IAM-User.png`
10. **MFA Verification** – `10-MFA-Code.png`
11. **EC2 Launch by IAM User** – `11-Instance-Created-IAM-User.png`
12. **EC2 Launch via CLI Command** – `12-Instance-Creation-Command-CLI.png`
13. **Instance Creation Verified** – `14-Instance-Created-CLI-Verified-AWS.png`

---

### 📂 3. IAM Role for EC2 and S3 Access Validation

This project focuses on creating an IAM role with S3 read permissions, attaching it to an EC2 instance, and testing S3 access.

#### 🔧 Steps:
1. **Create IAM Role for EC2** – `01-Role-Creation-For-EC2.png`
2. **Attach S3 ReadOnly Permission** – `02-Added-Permission-AmazonS3ReadOnlyAccess.png`
3. **Attach Role to EC2 Instance** – `03-Adding-Created-IAM-Role-to-Instance.png`
4. **List Bucket Success** – `04-List-Bucket-YES.png`
5. **Attempt Create Bucket - Permission Denied** – `05-Create-Bucket-NO.png`

---

### 📂 4. Custom IAM Policy for S3 with CLI Validation

This project demonstrates creating a custom IAM policy for S3, attaching it to users/roles, and validating operations such as upload/download/delete via CLI.

#### 🔧 Steps:
1. **Policy Creation for S3** – `01-Policy-Creation-S3.png`
2. **Allowed Actions Defined** – `02-Actions-Allowed-In-Policy.png`
3. **Attach Policy to Role** – `03-Added-Policy-to-IAM-Role.png`
4. **Attach Policy to User** – `04-Policy-Attach-to-User.png`
5. **Create Bucket via CLI** – `05-Create-Bucket-CLI.png`
6. **Check Bucket in Console** – `06-Check-Bucket-Created-AWS-Console.png`
7. **Upload Object via CLI** – `07-Put-Object-CLI.png`
8. **Check Upload in Console** – `08-Check-Object-Uploaded-AWS-Console.png`
9. **Download Object via CLI** – `09-Get-Object-CLI.png`
10. **Verify File Downloaded** – `10-Check-File-Downloaded.png`
11. **List Bucket and Object via CLI** – `11-List-Bucket-and-Object-CLI.png`
12. **Delete Object via CLI** – `12-Delete-Object-CLI.png`
13. **Confirm Deletion in Console** – `14-Check-Object-Deleted-AWS-Console.png`

---

## ✅ Learning Outcomes

- IAM user, group, and role creation
- Attaching managed and custom policies
- CLI configuration and EC2 provisioning
- Role-based access control and least privilege principle
- Custom IAM policy creation and S3 access testing
- Enabling MFA for secure user authentication
