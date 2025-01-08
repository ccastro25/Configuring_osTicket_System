# osTicket Setup Guide

This guide provides instructions on setting up various components of osTicket.

## If osTicket isn't installed yet, click [here](https://github.com/ccastro25/Setting_up_osTicket) to get started. Afterward, come back and follow these steps.

## Login and Access Admin Panel
1. Open your browser and go to [osTicket Login](http://localhost/osTicket/scp/login.php)
2. Log in using your credentials.
3. Navigate to the **Admin Panel**.
![login](https://github.com/user-attachments/assets/bd35ef85-21b1-4fa2-82bc-ef5d34f81be7)


## Create New Role
  ### Roles determine what actions users can perform within the system
1. Go to the **Agents** tab.
2. Select **Roles**.
3. Click on **Add New Role**.
4. Name the new role **Administrator**.
5. Assign all available permissions to this role to ensure it has full administrative access.
6. Click **Create** to save the role.
![add role](https://github.com/user-attachments/assets/ac717218-3ea3-40c5-a0a2-ad4ddeffa76f)

## Add New Department
### Departments help you manage and route tickets efficiently by assigning them to the appropriate team or individual who specializes in that particular area
1. Navigate to **Departments**.
2. Click on **Add New Department**.
3. Name the department **System Admin**.
4. Click **Create Department** to finalize.
![create dept](https://github.com/user-attachments/assets/2db24ec0-05ea-4ec0-b9cf-18c19649fb91)

## Create New Team
### Teams allow you to organize agents based on their skills, responsibilities, or areas of expertise
1. Select the **Teams** tab.
2. Click **Add New Team**.
3. Name the team **Level II Support**.
4. Click **Create Team** to save.
![createTeam](https://github.com/user-attachments/assets/ea2235d5-020c-4b43-b21d-ef019b535f25)

## Set User Registration Requirements
### Users must log in or create an account to submit a ticket
1. Go to the **Settings** tab.
2. Select **Users**.
3. Ensure that the option **Require registration and login to create tickets** is enabled.
![user registration](https://github.com/user-attachments/assets/a2b1a39b-07d2-47bb-8c6a-f5807cfd60d0)

## Add New Agent
### Agents are essentially the frontline support staff who handle customer inquiries, troubleshoot issues, and ensure that tickets are resolved efficiently
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
![add agent](https://github.com/user-attachments/assets/fe02e3ee-e77e-4eff-a886-1ea1c5bfd3e7)

## Add New User
### Users are typically the customers or clients seeking assistance with issues or inquiries
1. Select the **Agent Panel** next to your name.
2. Go to the **Users** tab.
3. Click **Add New User**.
4. Provide the user’s **Email** and **Name**.
5. Click **Register**.
6. Uncheck the option to **Send Account Activation Email** to set a temporary password.
7. Under **Password Confirmation**, choose whether to require a password change after the first login or to prevent the user from changing the password.
8. Click **Create Account**.
![add user'](https://github.com/user-attachments/assets/1af56f4a-8671-4525-8f4e-9b3d3b5f0e00)

## Add New Help Topic
### Help topics provide a structured way for users to classify their inquiries and for agents to manage tickets efficiently.
1. Return to the **Admin Panel**.
2. Navigate to the **Manage** tab.
3. Select **Help Topics**.
4. Click **Add New Help Topic**.
5. Name the help topic.
6. Optionally, add internal notes.
7. Click **Create** to save the help topic.
![helpTopic](https://github.com/user-attachments/assets/7e3b7a0e-00f8-42c7-98b4-cf2be0513c1e)

## Create SLA Plan
### In osTicket, an SLA, or Service Level Agreement, is a set of policies that define the expected response and resolution times for tickets based on their priority, help topic, or department
1. Under the **Manage** tab, select **SLA**.
2. Click **Add New SLA Plan**.
3. Provide a **Name** for the SLA plan.
4. Set the **Grace Period**.
5. Choose the **Schedule**.
6. Lastly, click **Add Plan** to save the SLA plan.
![SLA](https://github.com/user-attachments/assets/7368d8cd-3e3b-4998-9926-c93cc9c07b53)

Feel free to reach out if you need further details or clarification on any step! 😊
