# osTicket Setup Guide

This guide provides step-by-step instructions on setting up various components of osTicket.

## Login and Access Admin Panel
1. Open your browser and go to [osTicket Login](http://localhost/osTicket/scp/login.php)
2. Log in using your credentials.
3. Navigate to the **Admin Panel**.
![login](https://github.com/user-attachments/assets/bd35ef85-21b1-4fa2-82bc-ef5d34f81be7)


## Create New Role
1. Go to the **Agents** tab.
2. Select **Roles**.
3. Click on **Add New Role**.
4. Name the new role **Administrator**.
5. Assign all available permissions to this role to ensure it has full administrative access.
6. Click **Create** to save the role.
![add role](https://github.com/user-attachments/assets/ac717218-3ea3-40c5-a0a2-ad4ddeffa76f)

## Add New Department
1. Navigate to **Departments**.
2. Click on **Add New Department**.
3. Name the department **System Admin**.
4. Click **Create Department** to finalize.
![create dept](https://github.com/user-attachments/assets/2db24ec0-05ea-4ec0-b9cf-18c19649fb91)

## Create New Team
1. Select the **Teams** tab.
2. Click **Add New Team**.
3. Name the team **Level II Support**.
4. Click **Create Team** to save.
![createTeam](https://github.com/user-attachments/assets/ea2235d5-020c-4b43-b21d-ef019b535f25)

## Set User Registration Requirements
1. Go to the **Settings** tab.
2. Select **Users**.
3. Ensure that the option **Require registration and login to create tickets** is enabled.

## Add New Agent
1. Go to the **Agents** tab.
2. Select **Add New Agent**.
3. Fill in the agent’s details:
   - **Name**
   - **Email**
   - **Username**
4. Under **Authentication**:
   - Click on **Set Password**.
   - In the pop-up, choose to send a password reset to the agent's email or manually set a password.
   - You can also require the agent to change their password at the next login.
5. Under **Status and Settings**:
   - Optionally grant administrative privileges.
   - Limit ticket access to assigned tickets only, if needed.
   - Set agent status to locked or on vacation mode if necessary.
6. In the **Access** tab, assign the agent to the relevant departments and roles.
7. In the **Permissions** tab, configure specific permissions for the agent.
8. In the **Teams** tab, assign the agent to receive notifications from other teams as needed.
9. Once satisfied, click **Create** to save the agent's profile.

## Add New User
1. Select the **Agent Panel** next to your name.
2. Go to the **Users** tab.
3. Click **Add New User**.
4. Provide the user’s **Email** and **Name**.
5. Click **Register**.
6. Uncheck the option to **Send Account Activation Email** to set a temporary password.
7. Under **Password Confirmation**, choose whether to require a password change after the first login or to prevent the user from changing the password.
8. Click **Create Account**.

## Add New Help Topic
1. Return to the **Admin Panel**.
2. Navigate to the **Manage** tab.
3. Select **Help Topics**.
4. Click **Add New Help Topic**.
5. Name the help topic.
6. Optionally, add internal notes.
7. Click **Create** to save the help topic.

## Create SLA Plan
1. Under the **Manage** tab, select **SLA**.
2. Click **Add New SLA Plan**.
3. Provide a **Name** for the SLA plan.
4. Set the **Grace Period**.
5. Choose the **Schedule**.
6. Lastly, click **Add Plan** to save the SLA plan.

Feel free to reach out if you need further details or clarification on any step! 😊
