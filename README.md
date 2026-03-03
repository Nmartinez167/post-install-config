
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
<h2>This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.</h2>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

---

### **Project Phase: osTicket System Configuration**

---

### **Configuration Breakdown**

#### **1. Roles**

* **Path**: *Admin Panel → Agents → Roles*
* Assigned the **Supreme Admin** role for full administrative access and control.
* 
 <img width="1422" height="547" alt="Screenshot 2026-02-19 164822" src="https://github.com/user-attachments/assets/3e8a9ebb-19fc-4670-9e79-37e6f7c99ca8" />

<img width="1327" height="551" alt="Screenshot 2026-02-19 165136" src="https://github.com/user-attachments/assets/fac8e788-74b7-4d8b-be51-2a38849866b3" />

<img width="1442" height="677" alt="Screenshot 2026-02-19 165747" src="https://github.com/user-attachments/assets/9fe22e92-bc1b-4d2d-940c-5fdcb036e04d" />

<img width="1240" height="787" alt="Screenshot 2026-02-19 165856" src="https://github.com/user-attachments/assets/235b3afd-ad3a-4e2f-8f6c-511fc6f5f693" />

<img width="1406" height="916" alt="Screenshot 2026-02-19 170026" src="https://github.com/user-attachments/assets/bfccdd01-597a-43a8-a6b6-0393ac2a689f" />

<img width="1327" height="787" alt="Screenshot 2026-02-19 170138" src="https://github.com/user-attachments/assets/f76958fc-2291-4a07-9f23-c5bfd77948e3" />

<img width="1367" height="672" alt="Screenshot 2026-02-19 170226" src="https://github.com/user-attachments/assets/8babc703-dc37-47d1-9a44-ccf63dd125b5" />


<img width="1320" height="616" alt="Screenshot 2026-02-19 170330" src="https://github.com/user-attachments/assets/dd36a1eb-5742-4f55-81ea-d6629996a96e" />


#### **2. Departments**

* **Path**: *Admin Panel → Agents → Departments*
* Created a department called **Maintanance** to handle critical, system-level issues.

  <img width="1328" height="497" alt="Screenshot 2026-02-19 170651" src="https://github.com/user-attachments/assets/fd2bc4c3-28ce-485c-99f8-c57d1e04fb04" />

  <img width="1575" height="956" alt="Screenshot 2026-02-19 171139" src="https://github.com/user-attachments/assets/5dc6fc4e-8ce6-4162-a675-6f15836bdf44" />

<img width="1332" height="588" alt="Screenshot 2026-02-19 171313" src="https://github.com/user-attachments/assets/86b4b752-c0cd-4ec3-85e3-27d2bdd565d6" />


* **Path**: *Admin Panel → Agents → Teams*
* Configured **Level I** and *online banking* teams to support different levels of technical requests.
<img width="1301" height="501" alt="Screenshot 2025-10-09 135730" src="https://github.com/user-attachments/assets/1bdc9a7a-d229-477e-9e2a-49e6a508adb9" />

#### **4. Agents**

* **Path**: *Admin Panel → Agents → Add New*
* Added agents (e.g., *Jane*, *John*) to actively manage and respond to support tickets.
<img width="1301" height="503" alt="4444444" src="https://github.com/user-attachments/assets/6f3b5c44-9dad-45bf-8530-86d6d7abcc09" />

<img width="1363" height="788" alt="5555555" src="https://github.com/user-attachments/assets/d6cf3dd0-3015-4dff-b725-c31f0fc30d6b" />

<img width="1315" height="707" alt="66666666" src="https://github.com/user-attachments/assets/b793654f-2d6d-4b8a-b509-0b6bdde288e4" />

<img width="1295" height="602" alt="77777" src="https://github.com/user-attachments/assets/9376bc4a-f9e2-4578-8249-e7c96001972c" />


<img width="1106" height="363" alt="8888888" src="https://github.com/user-attachments/assets/c4b48f42-7a6e-4da6-9987-6e080386a247" />

* **Path**: *Agent Panel → Users → Add New*
* Registered end users (e.g., *Karen*, *Ken*) who will be submitting support tickets. We can also have people who arent part of the organization submit tickets by making sure these settings are chosen.
*<img width="1319" height="911" alt="12345" src="https://github.com/user-attachments/assets/972887b7-c8aa-4167-9e37-3675fa65db58" />
 
<img width="1326" height="552" alt="Screenshot 2025-10-09 142407" src="https://github.com/user-attachments/assets/9d91b9c2-1a62-4822-a138-28fac67f5b35" />

#### **6. SLAs (Service Level Agreements)**

* **Path**: *Admin Panel → Manage → SLA*
* Defined resolution policies for ticket prioritization:

  * **Sev-A**: 1-hour response, 24/7 coverage for critical outages.
  * **Sev-B**: 4-hour response, 24/7 coverage for high-priority issues.
  * **Sev-C**: 8-hour response, business hours only, for non-critical issues.
<img width="1277" height="570" alt="Screenshot 2025-10-09 143438" src="https://github.com/user-attachments/assets/764a8d79-e633-4dc4-b51d-720b4efb424c" />


#### **7. Help Topics**

* **Path**: *Admin Panel → Manage → Help Topics*
* Created structured categories to streamline support requests:

  * Business-Critical Outage
  * Personal Computer Issues
  * Equipment Requests
  * Password Resets

---<img width="1213" height="702" alt="Screenshot 2025-10-09 144116" src="https://github.com/user-attachments/assets/480f5c2e-4432-47ba-9093-bfc16ddaf014" />



The final setup enables the support team to handle a wide range of requests with improved efficiency and responsiveness, ultimately enhancing the overall user experience and increasing customer satisfaction.

---

