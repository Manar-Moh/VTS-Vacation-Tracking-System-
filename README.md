# 📘 VTS – Vacation Tracking System

---

## 🎯 Vision

VTS will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, **without needing to understand company policy or local facility rules**.

---

## 🧩 Domain (Problem Statement)

In the current manual process:

- Vacation requests must be approved by an immediate manager.
- Then, they are verified by an HR clerk before authorization.
- This process often takes **days** and causes delays and inefficiencies.

VTS solves this by streamlining the request and approval process.

---

## ✅ Functional Requirements

| # | Requirement |
|---|-------------|
| 1 | Implements a flexible rules-based system for validating and verifying leave time requests. |
| 2 | Enables manager approval. |
| 3 | Provides access to requests from the previous year and allows future requests up to 1.5 years ahead. |
| 4 | Uses e-mail notifications for manager approvals and status updates. |
| 5 | Keeps activity logs for all transactions. |
| 6 | Allows HR/admins to override rules with logging. |
| 7 | Allows managers to award personal leave time with limits. |
| 8 | Provides a web service interface for internal system queries. |
| 9 | Integrates with HR legacy systems to retrieve employee info and changes. |

---

## ⚙️ Non-Functional Requirements

| # | Requirement |
|---|-------------|
| 1 | Authentication relies on the portal's single sign-on mechanism. |
| 2 | The system must be user-friendly and intuitive. |
| 3 | The system must speed up vacation request management. |
| 4 | It should reduce time and cost by automating HR involvement. |

---

## ⛓️ Constraints

| # | Constraint |
|---|------------|
| 1 | Must use existing hardware and middleware. |
| 2 | Email notifications required |
| 3 | Must be implemented as an extension to the existing intranet portal. |

---

## 👥 Actors in the System

| Actor | Description |
|-------|-------------|
| 👤 Employee | Submits and tracks leave requests. |
| 👨‍💼 Manager | Approves or rejects requests, may award leave directly. |
| 🧑‍💻 HR Clerk | Can override system rules and audit logs. |
| 👨‍🔧 System Administrator | Manages rules, policies, system users, and configurations. |

---

## 📂 Use Cases

| 📌 Use Case | 🔗 Link |
|------------|---------|
| 🕒 Manage Time | [manage-time.md](./use-cases/manage-time/manage-time.md) |


