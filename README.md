# post-install-config<p align="center">
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

**Goal**
The objective of this phase was to transition the osTicket system from a basic Alpha installation into a fully functional, production-ready support platform. This involved configuring the system to efficiently manage support tickets, user requests, and staff assignments.

---

### **Overview: Key Component Configuration**

In this phase, critical elements of osTicket were configured to ensure optimal functionality and streamlined support operations. The setup included:

* **Roles**: Defined access levels and permissions by assigning roles such as Admin and Support Staff.
* **Departments**: Created specialized departments (e.g., IT, Customer Support) to handle tickets by category.
* **Teams**: Established Level I and Level II support teams for tiered assistance.
* **Agents (Support Staff)**: Added support agents responsible for managing and resolving tickets.
* **Users (End Users)**: Registered users who will submit support tickets.
* **SLAs (Service Level Agreements)**: Set resolution timeframes based on issue severity.
* **Help Topics**: Categorized ticket types to streamline routing and resolution.

---

### **Configuration Breakdown**

#### **1. Roles**

* **Path**: *Admin Panel → Agents → Roles*
* Assigned the **Supreme Admin** role for full administrative access and control.
 
<img width="1332" height="627" alt="Screenshot 2025-10-09 134343" src="https://github.com/user-attachments/assets/91b04e73-47ee-4137-85d9-530c3824ff3d" />

#### **2. Departments**

* **Path**: *Admin Panel → Agents → Departments*
* Created a department called **Maintanance** to handle critical, system-level issues.
<img width="1307" height="543" alt="Screenshot 2025-10-09 134619" src="https://github.com/user-attachments/assets/a9fdbe51-0eac-43d8-93cb-acf6eacc5303" />

#### **3. Teams**

* **Path**: *Admin Panel → Agents → Teams*
* Configured **Level I** and **Level II** teams to support different levels of technical requests.
<img width="1301" height="501" alt="Screenshot 2025-10-09 135730" src="https://github.com/user-attachments/assets/1bdc9a7a-d229-477e-9e2a-49e6a508adb9" />

#### **4. Agents**

* **Path**: *Admin Panel → Agents → Add New*
* Added agents (e.g., *Jane*, *John*) to actively manage and respond to support tickets.
<img width="1270" height="507" alt="Screenshot 2025-10-09 140516" src="https://github.com/user-attachments/assets/d919e19c-c74c-41d3-9f08-493fabf7bd0f" />

#### **5. Users**

* **Path**: *Agent Panel → Users → Add New*
* Registered end users (e.g., *Karen*, *Ken*) who will be submitting support tickets.
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


### **Conclusion**

This phase successfully transformed the osTicket platform into a robust, operational help desk system. By meticulously configuring roles, departments, teams, users, SLAs, and help topics, the system is now optimized for effective ticket routing, prioritization, and resolution.

The final setup enables the support team to handle a wide range of requests with improved efficiency and responsiveness, ultimately enhancing the overall user experience and increasing customer satisfaction.

---

