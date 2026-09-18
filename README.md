# EX - 6 Implementation Of Identity Management (Amazon IAM) For Your Team

## NAME: Arigala Hema
## REG. NO: 212224110005
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
<img width="1617" height="692" alt="image" src="https://github.com/user-attachments/assets/4a7265da-4a6d-4b8c-935f-3f7437d75283" />



## 2.Attach an IAM Policy to the group

<img width="1597" height="692" alt="Screenshot 2026-09-19 032813" src="https://github.com/user-attachments/assets/9c9380ca-fbf0-401f-966b-5ba11ec74586" />

## 3.Create an IAM User

<img width="1533" height="716" alt="Screenshot 2026-09-19 033503" src="https://github.com/user-attachments/assets/a6cd3718-0c76-4d91-8f47-5ea6194c31ea" />

## 4.Add The user to the IAM Group

<img width="1622" height="716" alt="image" src="https://github.com/user-attachments/assets/5d1067df-b9e6-4ec3-bc1c-e2c5872d0309" />


## 5.Verify user Permissions

<img width="1607" height="720" alt="image" src="https://github.com/user-attachments/assets/f7b110af-e53e-4f35-9099-b24ffe7ffe73" />

## 6.Verify Least-Privilege Access

<img width="1606" height="705" alt="image" src="https://github.com/user-attachments/assets/88aabe48-022d-49b4-b22c-417609728cc5" />

<img width="1605" height="707" alt="Screenshot 2026-09-19 035020" src="https://github.com/user-attachments/assets/5119a07c-f321-4e27-bcf2-e23ac5e7db8a" />



---

## Result

Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.
