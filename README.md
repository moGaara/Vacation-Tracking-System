# Vacation-Tracking-System
## 🌐 Domain

The system operates within the **Human Resources and Workforce Management** domain, specifically addressing the challenges of vacation time and leave tracking in organizations where employees often work on **multiple projects** and have **distributed reporting structures**. It supports both managers and employees in planning and managing time off in a flexible and coordinated manner.

---

## 🎯 Vision

A **Vacation Tracking System (VTS)** will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.

---

## ✅ Functional Requirements

- Implements a flexible rules-based system.
- Validates and verifies leave time requests.
- Enables optional manager approval.
- Provides access to requests for the previous calendar year and allows requests to be made up to a year and a half in the future.
- Uses e-mail notifications to request manager approval and notify employees of request status changes.
- Enables HR and system administration personnel to override all actions restricted by rules, with override actions being logged.
- Allows managers to directly award personal leave time.
- Provides a Web service interface for internal systems to query any employee’s vacation request summary.
- Interfaces with legacy HR systems to retrieve necessary employee information and updates.

---

## 📋 Non-Functional Requirements

- **Usability** – User-friendly interface for both employees and managers.
- **Flexibility** – Adaptable to different leave policies and organizational structures.
- **Compliance** – Adheres to organizational policies and labor regulations.
- **Auditability** – Maintains complete logs of all actions for audit purposes.

---

## ⚠️ Constraints

- Must use existing hardware and middleware.
- Implemented as an extension to the existing intranet portal system.
- Utilizes the portal’s single-sign-on mechanisms for authentication.
- Logs all transactional activity.
- Overrides performed by HR must be logged.
- System must set limits when managers directly award personal leave time.

---

## 👥 Actors

- **Employee** – Requests and manages leave.
- **Manager** – Reviews and optionally approves leave requests, can award personal leave time.
- **Human Resources** – Oversees the system, manages overrides, ensures compliance.
