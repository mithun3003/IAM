# EX - 6 Implementation Of Identity Management (Amazon IAM) For Your Team

---

## Aim

To implement identity and access management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

---

## Algorithm

1. Sign in to the AWS Management Console.
2. Navigate to the IAM service.
3. Create IAM groups with defined policies (e.g., Admin, Developer).
4. Create IAM users and assign them to appropriate groups.
5. Create IAM roles if cross-account or service-based access is needed.
6. Attach permissions using managed or custom policies.
7. Enable MFA (Multi-Factor Authentication) for users.
8. Monitor access using IAM Access Analyzer and CloudTrail.

---

## Procedure

### 1. Access IAM

- Go to *AWS Console* → *Services* → *IAM*.

### 2. Create IAM Groups

- Click *Groups* → *Create New Group*.
- Name the group (e.g., Admins, Developers).
- Attach predefined or custom policies (e.g., AmazonEC2FullAccess).

### 3. Create IAM Users

- Click *Users* → *Add Users*.
- Enter usernames and choose *Programmatic access* and/or *AWS Management Console access*.
- Assign users to the appropriate group.

### 4. Create IAM Roles (if needed)

- Go to *Roles* → *Create Role*.
- Select use case (AWS service, another AWS account).
- Attach necessary permissions.

### 5. Apply Policies

- Use AWS managed policies or create custom JSON-based policies.
- Assign them to users, groups, or roles.

### 6. Enable MFA

- For each user, go to *Security credentials*.
- Click *Manage MFA* → Choose *Virtual MFA device* (e.g., Google Authenticator).

### 7. Monitor IAM Usage

- Use *IAM Access Analyzer* to detect unused permissions.
- Use *CloudTrail* for auditing user activity.

---

### Outcome

## 1.IAM Group Creation

<img width="1913" height="1047" alt="image" src="https://github.com/user-attachments/assets/160c62b9-30a2-4a41-9809-f39c65215f60" />


## 2.Attach an IAM Policy to the group

<img width="1917" height="1042" alt="image" src="https://github.com/user-attachments/assets/c2d1834e-fd1d-4518-be53-a03c072c4f48" />


## 3.Create an IAM User

<img width="1917" height="1037" alt="image" src="https://github.com/user-attachments/assets/22e712d1-af36-4632-9e31-2cf3d44d77dd" />


## 4.Add The user to the IAM Group

<img width="1907" height="1027" alt="image" src="https://github.com/user-attachments/assets/06e1b283-f10e-489d-b40e-8c13ccfbd1ae" />


## 5.Verify user Permissions

<img width="1917" height="1042" alt="image" src="https://github.com/user-attachments/assets/8e813358-94e8-4c7e-92ab-4b1c16d6ed25" />


## 6.Verify Least-Privilege Access

<img width="1917" height="1045" alt="image" src="https://github.com/user-attachments/assets/5a83786a-bc97-4d5b-84cf-3b14f7d7de55" />

---

## Result

Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.
