

<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>

# osTicket — Post-Installation Configuration

## Project Overview

This project documents the post-installation configuration of **osTicket**, an open-source help desk ticketing system. After installing the application, the lab focuses on setting up roles, departments, teams, agents, end users, user access settings, service-level agreements (SLAs), and help topics.

The goal is to organize the help desk so that support requests can be managed by the appropriate people and categorized according to their needs.

## Environment and Technologies

- **Cloud platform:** Microsoft Azure (Virtual Machines)
- **Remote access:** Remote Desktop Protocol (RDP)
- **Web server:** Internet Information Services (IIS)
- **Operating system:** Windows 10 (21H2)
- **Application:** osTicket

## Project Objectives

- Configure roles and permissions for agents.
- Organize agents into departments and teams.
- Set up end-user accounts and ticket submission settings.
- Define SLA plans for different ticket priorities.
- Create help topics to organize incoming support requests.
- Review access and security settings.

## Configuration Walkthrough

### 1. Configure Roles

**Navigation:** Admin Panel → Agents → Roles

1. Open the **Roles** section in the Admin Panel.
2. Review the available roles and their permissions.
3. Assign the **Supreme Admin** role as an example of a role with broad administrative access.

In a real support organization, this level of access should be limited to authorized personnel, such as the IT manager or designated system administrators. Agents should receive only the permissions required for their responsibilities.

<img width="50%" height="50%" alt="Screenshot 2026-02-19 164822" src="https://github.com/user-attachments/assets/3e8a9ebb-19fc-4670-9e79-37e6f7c99ca8" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 165136" src="https://github.com/user-attachments/assets/fac8e788-74b7-4d8b-be51-2a38849866b3" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 165747" src="https://github.com/user-attachments/assets/9fe22e92-bc1b-4d2d-940c-5fdcb036e04d" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 165856" src="https://github.com/user-attachments/assets/235b3afd-ad3a-4e2f-8f6c-511fc6f5f693" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 170026" src="https://github.com/user-attachments/assets/bfccdd01-597a-43a8-a6b6-0393ac2a689f" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 170138" src="https://github.com/user-attachments/assets/f76958fc-2291-4a07-9f23-c5bfd77948e3" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 170226" src="https://github.com/user-attachments/assets/8babc703-dc37-47d1-9a44-ccf63dd125b5" />

### 2. Configure Departments

**Navigation:** Admin Panel → Agents → Departments

1. Open **Departments**.
2. Create departments to organize ticket ownership and visibility.
3. In this lab, example departments include **SysAdmins** and **Maintenance**.
4. Use departments to route issues to the appropriate support group.

The Maintenance department is used as an example for handling maintenance-related or system-level issues.

<img width="50%" height="50%" alt="Screenshot 2026-02-19 170330" src="https://github.com/user-attachments/assets/dd36a1eb-5742-4f55-81ea-d6629996a96e" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 170651" src="https://github.com/user-attachments/assets/fd2bc4c3-28ce-485c-99f8-c57d1e04fb04" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 171139" src="https://github.com/user-attachments/assets/5dc6fc4e-8ce6-4162-a675-6f15836bdf44" />

<img width="50%" height="50%" alt="Screenshot 2026-02-19 171313" src="https://github.com/user-attachments/assets/86b4b752-c0cd-4ec3-85e3-27d2bdd565d6" />

### 3. Configure Teams

**Navigation:** Admin Panel → Agents → Teams

1. Open **Teams**.
2. Create a team.
3. Add agents from the relevant departments.
4. In this lab, **Online Banking** is used as an example team name.

Teams can help coordinate work that involves agents from different departments.

<img width="50%" height="50%" alt="Screenshot 2025-10-09 135730" src="https://github.com/user-attachments/assets/1bdc9a7a-d229-477e-9e2a-49e6a508adb9" />

### 4. Add Agents

**Navigation:** Admin Panel → Agents → Add New

1. Open **Add New** under the Agents section.
2. Enter the agent's account information.
3. Assign the agent to the appropriate department.
4. Add the agent to a team when applicable.

The lab uses **Jane** (SysAdmins) and **John** (Support) as example agent accounts.

<img width="50%" height="503" alt="50%" src="https://github.com/user-attachments/assets/6f3b5c44-9dad-45bf-8530-86d6d7abcc09" />

<img width="50%" height="50%" alt="5555555" src="https://github.com/user-attachments/assets/d6cf3dd0-3015-4dff-b725-c31f0fc30d6b" />

<img width="50%" height="50%" alt="66666666" src="https://github.com/user-attachments/assets/b793654f-2d6d-4b8a-b509-0b6bdde288e4" />

<img width="50%" height="50%" alt="77777" src="https://github.com/user-attachments/assets/9376bc4a-f9e2-4578-8249-e7c96001972c" />

<img width="50%" height="50%" alt="8888888" src="https://github.com/user-attachments/assets/c4b48f42-7a6e-4da6-9987-6e080386a247" />





### 5. Add End Users

**Navigation:** Agent Panel → Users → Add New

1. Open **Users** in the Agent Panel.
2. Select **Add New**.
3. Enter the end user's information and create the account.

The lab uses **Karen** and **Ken** as example end users. End users are the people who submit support requests through the ticketing portal.

<img width="50%" height="50%" alt="user" src="https://github.com/user-attachments/assets/c09cae73-0c57-4b96-9062-ab6ba987259c" />

<img width="50%" height="50%" alt="user2" src="https://github.com/user-attachments/assets/ac424540-1772-4a99-8f40-dcc5ef925656" />



### 6. Configure User Settings

**Navigation:** Admin Panel → Settings → User Settings

1. Open **User Settings**.
2. Review the options that control ticket creation.
3. In this lab, the setting **Unregistered users can create tickets** is unchecked.
4. This configuration requires users to register and sign in before creating tickets.

Requiring accounts can help an organization manage who submits requests. The appropriate setting depends on the organization's support process.

<img width="50%" height="50%" alt="12345" src="https://github.com/user-attachments/assets/972887b7-c8aa-4167-9e37-3675fa65db58" />

<img width="50%" height="50%" alt="Screenshot 2025-10-09 142407" src="https://github.com/user-attachments/assets/9d91b9c2-1a62-4822-a138-28fac67f5b35" />

### 7. Configure Service-Level Agreements (SLAs)

**Navigation:** Admin Panel → Manage → SLA

Create SLA plans to define target response or resolution times for different levels of ticket urgency.

The lab uses the following example policies:

| SLA plan | Target shown in this lab | Coverage |
|---|---|---|
| **Sev-A** | 1-hour response | 24/7 |
| **Sev-B** | 4-hour response | 24/7 |
| **Sev-C** | 8-hour response | Business hours |

These are example lab settings, not universal service commitments. In a production environment, SLA targets should be agreed upon by the organization and configured to match its actual support policies.

<img width="50%" height="50%" alt="sla" src="https://github.com/user-attachments/assets/abb6a87f-6f13-4703-a474-35af373a3e63" />

<img width="50%" height="50%" alt="Screenshot 2025-10-09 143438" src="https://github.com/user-attachments/assets/764a8d79-e633-4dc4-b51d-720b4efb424c" />

### 8. Configure Help Topics

**Navigation:** Admin Panel → Manage → Help Topics

Create categories that help users classify their support requests. The lab includes these examples:

- **Business-Critical Outage**
- **Personal Computer Issues**
- **Equipment Requests**
- **Password Resets**

Organized help topics make it easier to categorize incoming tickets and direct them to the appropriate support workflow.

<img width="50%" height="50%" alt="tp" src="https://github.com/user-attachments/assets/3aa722e7-6860-4790-93c3-3452d1b496c8" />

<img width="50%" height="50%" alt="Screenshot 2025-10-09 144116" src="https://github.com/user-attachments/assets/480f5c2e-4432-47ba-9093-bfc16ddaf014" />

## Outcome

This post-installation configuration organizes the osTicket help desk into roles, departments, teams, agents, and end users. It also establishes example ticket access settings, SLA plans, and help topics.

Together, these configurations provide a foundation for managing and routing support requests in a structured ticketing environment.

## Skills Demonstrated

- Configuring roles and access permissions
- Creating and organizing departments
- Creating teams and assigning agents
- Creating agent and end-user accounts
- Configuring ticket submission settings
- Defining example SLA targets
- Creating help topics for ticket categorization
- Documenting a help desk configuration process

