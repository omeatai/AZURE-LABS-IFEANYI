# AZURE-LABS-IFEANYI
### BY Ifeanyi Omeata

- [ ] **Set up development environment**
- [x] **Install dependencies**
- [ ] **Write initial code**

<details>
  <summary>LAB 1 - Create an IAM User and Group in AWS</summary>
- [ ] **Set up development environment**
- [x] **Install dependencies**
- [ ] **Write initial code**
- [ ] **Test the application**
<details>
    <summary>1 - Open IAM Console </summary>
      - [ ] **Set up development environment**
      - [x] **Install dependencies**
      - [ ] **Write initial code**
      - [ ] **Test the application**
      - [ ] **Deploy to production**
      - [ ] **Go to the AWS Management Console.**
      - [ ] **Enter "IAM" in the search bar and go to the IAM console.**
      - [ ] **Notice the IAM service is global and doesn't require region selection.**
  </details>
  <details>
      <summary>2 - Others </summary>
        - 2. **Viewing Current Users**
            - [ ] On the left-hand side, click on "Users" to view the current user list.
        - 3. **Create a New IAM User and Set Password**
            - [ ] Click on "Create user."
            - [ ] Enter a username (e.g., admin).
            - [ ] Select "Provide user access to the AWS Management Console."
            - [ ] Choose "I want to Create an IAM user" option.
            - [ ] Choose "Custom password" and enter your password.
            - [ ] Uncheck "Users must create a new password at next sign-in”.
            - [ ] Click "Next".
        - 4. **Create a User Group and Assign Permissions**
            - [ ] Choose "Add user to group."
            - [ ] Click "Create group."
            - [ ] Name the group (e.g., administration).
            - [ ] Attach "AdministratorAccess" policy to the group.
            - [ ] Click "Create user group".
            - [ ] Add the user to the newly created admin group by selecting the group.
            - [ ] Click "Next".
        - 5. **Review and Create User**
            - [ ] Review the settings: username, permissions, groups, etc.
            - [ ] Optionally, add tags (e.g., department: engineering).
            - [ ] Click "Create user."
        - 6. **Verify User and Group Setup**
            - [ ] Optionally, download the CSV file for sign-in credentials.
            - [ ] View the user list to ensure the user is created.
            - [ ] Verify the user belongs to the "administration" group.
            - [ ] Check the "administration" group to confirm "AdministratorAccess" policy is attached.
        - 7. **Create an Account Alias (Optional)**
            - [ ] Go to your AWS IAM Dashboard.
            - [ ] Create an account alias (e.g., aws-adminaccess-v2).
        - 8. **Sign in with IAM User**
            - [ ] Open a new private browser window.
            - [ ] Use the IAM sign-in URL.
            - [ ] Enter account alias or account ID, and IAM username (e.g., admin).
            - [ ] Enter the IAM user password to log in.
            - [ ] Check the top right to ensure you're signed in as the IAM user.
    </details>
</details>
