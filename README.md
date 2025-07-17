# post-install-config<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>
Here’s a refined and professional rephrasing of your content for inclusion in your portfolio. It keeps the structure and detail while improving clarity, flow, and tone:

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

#### **2. Departments**

* **Path**: *Admin Panel → Agents → Departments*
* Created a department called **System Administrators** to handle critical, system-level issues.

#### **3. Teams**

* **Path**: *Admin Panel → Agents → Teams*
* Configured **Level I** and **Level II** teams to support different levels of technical requests.

#### **4. Agents**

* **Path**: *Admin Panel → Agents → Add New*
* Added agents (e.g., *Jane*, *John*) to actively manage and respond to support tickets.

#### **5. Users**

* **Path**: *Agent Panel → Users → Add New*
* Registered end users (e.g., *Karen*, *Ken*) who will be submitting support tickets.

#### **6. SLAs (Service Level Agreements)**

* **Path**: *Admin Panel → Manage → SLA*
* Defined resolution policies for ticket prioritization:

  * **Sev-A**: 1-hour response, 24/7 coverage for critical outages.
  * **Sev-B**: 4-hour response, 24/7 coverage for high-priority issues.
  * **Sev-C**: 8-hour response, business hours only, for non-critical issues.

#### **7. Help Topics**

* **Path**: *Admin Panel → Manage → Help Topics*
* Created structured categories to streamline support requests:

  * Business-Critical Outage
  * Personal Computer Issues
  * Equipment Requests
  * Password Resets

---

### **Conclusion**

This phase successfully transformed the osTicket platform into a robust, operational help desk system. By meticulously configuring roles, departments, teams, users, SLAs, and help topics, the system is now optimized for effective ticket routing, prioritization, and resolution.

The final setup enables the support team to handle a wide range of requests with improved efficiency and responsiveness, ultimately enhancing the overall user experience and increasing customer satisfaction.

---

