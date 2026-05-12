# Salesforce Summer Program – Day 2

# How Salesforce Platform Works Internally

##1 What is Salesforce Platform?

Salesforce is a cloud-based CRM platform that helps companies:

* Store customer data
* Automate business processes
* Manage sales and support
* Build custom applications

Salesforce works completely on the cloud.
Users access it through a web browser instead of installing software.

---

# How Salesforce Works Internally

## User Accesses Salesforce

A user logs in using:

* Username
* Password

The request goes to Salesforce cloud servers.

```text
User → Internet → Salesforce Cloud Servers
```

---

## 2 Salesforce Stores Data

Salesforce stores data in:

* Objects
* Records
* Fields

Example:

| Object      | Stores              |
| ----------- | ------------------- |
| Account     | Company information |
| Contact     | Customer details    |
| Opportunity | Sales deals         |

---

## 3️ Salesforce Processes Business Logic

Salesforce automatically handles:

* Security
* Workflows
* Automation
* Reports
* Data relationships

This helps companies avoid manual work.

---

## 4️ Salesforce Displays Data

The platform shows data using:

* Apps
* Tabs
* Dashboards
* Reports
* Record pages

Users interact with the UI using a browser.

---

# 📱 What is an App in Salesforce?

## Definition

An App is a collection of:

* Tabs
* Objects
* Features
* Tools

that work together for a specific business purpose.

---

## Example Apps

| App           | Purpose                    |
| ------------- | -------------------------- |
| Sales App     | Manage customers and sales |
| Service App   | Customer support           |
| Marketing App | Marketing campaigns        |

---

## Simple Understanding

```text
App = Complete workspace for users
```

Example:

* Sales team uses Sales App
* Support team uses Service App

---

#  What is an Object?

## Definition

Objects are database tables in Salesforce.

They store business data.

---

## Example

| Object  | Example Data        |
| ------- | ------------------- |
| Account | Company details     |
| Contact | Customer details    |
| Lead    | Potential customers |

---

## Types of Objects

### 1️⃣ Standard Objects

Created by Salesforce.

Examples:

* Account
* Contact
* Opportunity
* Lead

---

### 2️⃣ Custom Objects

Created by developers or admins.

Example:

* Student
* Hospital
* Employee

---

# 📑 What is a Tab?

## Definition

A Tab is a user interface link used to access:

* Objects
* Records
* Pages

Tabs help users open data easily.

---

## Example

```text
Account Tab → Opens Account records
```

---

## Simple Understanding

```text
Tab = Shortcut to access Salesforce data
```

---

# 🧠 Relationship Between App, Object, and Tab

```text
App
 ├── Tabs
 │     ├── Objects
 │           ├── Records
```

---

# 👨‍💻 How Developers Extend Salesforce

Developers extend Salesforce by adding:

* Custom objects
* Automation
* Custom UI
* APIs
* Integrations
* Business logic

---

# 🔹 Ways Developers Extend Salesforce

## 1️⃣ Custom Objects

Developers create new objects.

Example:

* Student object
* Library object

---

## 2️⃣ Custom Fields

Add extra fields.

Example:

| Field        | Type   |
| ------------ | ------ |
| Student Name | Text   |
| Marks        | Number |

---

## 3️⃣ Automation

Salesforce automates tasks using:

* Flow
* Process Builder
* Apex

Example:

* Send email automatically
* Auto-assign leads

---

## 4️⃣ Apex Programming

Apex is Salesforce’s programming language.

Used for:

* Complex logic
* Automation
* Backend development

---

## 5️⃣ Lightning Components

Used to build custom UI components.

Helps create:

* Interactive pages
* Dashboards
* Custom screens

---

## 6️⃣ APIs and Integrations

Salesforce connects with external systems.

Examples:

* Payment systems
* Gmail
* ERP software

---

# 🏗 Basic Salesforce Development Architecture

## Architecture Flow

```text
User
  ↓
Salesforce UI
  ↓
Business Logic
  ↓
Database Objects
  ↓
Cloud Storage
```

---

# 🔹 Layers of Salesforce Architecture

## 1️⃣ Presentation Layer

User Interface.

Includes:

* Apps
* Tabs
* Pages
* Dashboards

---

## 2️⃣ Logic Layer

Handles business rules.

Includes:

* Flows
* Apex
* Validation rules

---

## 3️⃣ Data Layer

Stores data.

Includes:

* Objects
* Fields
* Records

---

# ☁ Salesforce Multi-Tenant Architecture

## Definition

Many companies share the same Salesforce infrastructure securely.

Each company has:

* Separate data
* Separate security
* Separate customization

---

## Simple Understanding

```text
One Platform
   ↓
Multiple Companies Using It Securely
```

---

# 🔒 Security in Salesforce

Salesforce provides:

* User authentication
* Role hierarchy
* Profiles
* Permission sets
* Data sharing rules

This keeps company data secure.

---

# 📊 Real-World Example

## Hospital Management App

### Objects

* Patient
* Doctor
* Appointment

### Tabs

* Patient Tab
* Appointment Tab

### App

* Hospital Management App

### Automation

* Appointment reminder emails

---

# 🎯 Key Concepts Learned

✅ Salesforce is cloud-based
✅ Apps organize business features
✅ Objects store data
✅ Tabs help access data
✅ Developers extend Salesforce using customization and code
✅ Salesforce uses layered architecture
✅ Data is stored securely in the cloud

---

# 🧠 Final Understanding

Salesforce internally works as a cloud-based platform where users interact with Apps, Tabs, and Objects to manage business data. Developers extend Salesforce by creating custom objects, automation, integrations, and UI components using Salesforce development tools and architecture.
