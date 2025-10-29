<div align="center">

# 💼 Streamlining Ticket Assignment for Efficient Support Operations  
### *A SmartInternz Project using ServiceNow Automation for Naan Mudhalvan*


<img src="https://brandfetch.com/naanmudhalvanmentors.com/logo.png" alt="Naan Mudhalvan Logo" width="200">

</div>

---

## 🧭 About the Project

This project focuses on **automating the ticket assignment process** within the ServiceNow platform.  
By leveraging **ServiceNow Flow Designer**, **custom tables**, and **role-based access**, the system intelligently assigns tickets to the appropriate support groups automatically.  

The goal is to eliminate manual ticket routing, reduce human errors, and enhance support efficiency in IT operations.

---

## 🎯 Objectives

- Automate ticket routing and assignment.  
- Minimize human intervention in support operations.  
- Improve ticket response and resolution times.  
- Ensure clear team-level responsibility via roles and groups.  

---

## ⚙️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| 🧩 **ServiceNow** | Ticket management and workflow automation |
| 💾 **GitHub** | Version control and documentation |

---

## 🪜 Implementation Steps

### 🔹 Step 1: Create Users  
Navigate to **System Security → Users** and create new users (e.g., agents, admins).

### 🔹 Step 2: Create Groups  
Go to **User Administration → Groups** and create groups such as:
- **Platform Team**
- **Certificates Team**

### 🔹 Step 3: Assign Roles  
Create custom roles for each group (e.g., `platform_admin`, `cert_team_user`) and assign them to respective users.

### 🔹 Step 4: Create a Custom Table  
Create a new table named **Operations Related** with fields:
- `Issue`
- `Priority`
- `Assigned Group`
- `Short Description`

### 🔹 Step 5: Configure Access Controls (ACLs)  
Grant permission to relevant groups and restrict unauthorized access.

### 🔹 Step 6: Build an Automated Flow  
Using **Flow Designer**, create a flow to:
- Trigger when a new record is inserted in *Operations Related*.  
- Check the “Issue” field.  
- Automatically assign the ticket to the correct group (e.g., *Certificates Team* or *Platform Team*).  

### 🔹 Step 7: Test and Validate  
Submit multiple tickets with different issue types and verify automatic group assignment.

---

## 🧩 System Workflow

```text
User Creates a Ticket
        ↓
ServiceNow Table (Operations Related)
        ↓
Flow Designer Trigger
        ↓
Auto-Assign to Relevant Group
        ↓
Ticket Visible to Group Members
        ↓
Faster Resolution & Improved Efficiency
