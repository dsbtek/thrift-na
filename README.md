# Thriftna: Contribution Management App

## Overview

Thriftna is a digital platform that automates and manages traditional rotating savings and contribution schemes, known locally as "Adashi", "Esusu", or "Ajo". Users contribute periodically (daily, weekly, monthly, etc.), and the pooled funds are disbursed to a designated member in each round. The app provides real-time updates via WhatsApp and supports in-app payments.

---

## Key Objectives

* Digitize traditional Adashi groups.
* Provide real-time updates via WhatsApp.
* Automate disbursements and reminders.
* Track contributions securely with in-app payments.

---

## User Roles

| Role             | Description                               |
| ---------------- | ----------------------------------------- |
| **Admin**        | Manages the entire system and all groups. |
| **Group Leader** | Oversees specific contribution groups.    |
| **Member**       | Participates in contribution cycles.      |

---

## Core Features

### Contribution Management

* Support for daily, weekly, monthly groups.
* Automatic/manual turn rotation.
* Set group size, contribution amount, and schedule.
* Rolling or fixed cycles.

### Member Management

* Invite via phone or WhatsApp.
* Assign turn order.
* Manage defaulters.

### Payment System

* Integration with local payment gateways (Flutterwave, Paystack).
* In-app wallet and balance tracking.
* Automatic deduction of service fees.
* Payment history and downloadable receipts.

### Notifications

* **WhatsApp** updates via Twilio/WhatsApp Business API.

  * Payment confirmations
  * Due reminders
  * Turn notifications
* In-app and email alerts as alternatives.

### Disbursement & Fee Logic

* Configurable fee (percentage or fixed).
* Scheduled disbursement with logs.

### Group Rules

* Agreement to terms before joining.
* Upload identity for KYC compliance.

### Dashboard & Reports

* Visual dashboards for admin/group leaders.
* Downloadable reports (PDF, Excel).

---

## Additional Features

* Dispute resolution and escalation system.
* Loan feature for trusted members.
* Trust scores based on contribution history.
* Referral/invitation incentives.
* Offline mode with sync.
* Voice note tutorials in local dialects.

---

## Tech Stack

### Backend

* Node.js
* PostgreSQL
* Redis for queue management

### Frontend

* React Native (Mobile app)
* Next.js (Admin dashboard)

### Integrations

* Payments: Paystack / Flutterwave
* Messaging: Twilio / WhatsApp API
* Notifications: Firebase Cloud Messaging (FCM)

### DevOps

* Docker + CI/CD
* AWS / DigitalOcean
* PostgreSQL backups

---

## Security & Compliance

* End-to-end encryption
* Role-based access control (RBAC)
* KYC & NDPR compliance

---

## Monetization

* Commission/service fees
* Premium features
* Non-intrusive ads

---

## Timeline (Example)

| Milestone             | Duration  |
| --------------------- | --------- |
| Requirements & Design | 1 week    |
| MVP Development       | 4–6 weeks |
| Testing & Feedback    | 1 week    |
| Launch                | 1 week    |

---

## Future Roadmap

* Blockchain-backed thrift validation.
* AI risk scoring for defaults.
* Currency conversion for international users.

---

## License

MIT License
