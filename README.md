# SafeLab UML Class Diagram Design

Professional UML class diagram repository for **SafeLab**, a smart laboratory monitoring platform focused on assets, sensors, alerts, compliance, incidents, reporting, analytics, and traceability.

This repository contains the **Object-Oriented Design Software** artifacts for SafeLab, using UML class diagrams organized by bounded context.

---

## Project Overview

SafeLab is designed for hospital laboratories and pharmaceutical companies that need to monitor critical equipment, storage conditions, supplies, and incidents in real time.

The UML class diagrams in this repository describe the main domain entities, relationships, enumerations, and responsibilities required to support the SafeLab business model.

---

## Repository Structure

```text
.
├── diagrams
│   ├── AlertsNotificationsClassDiagram.puml
│   ├── AssetInventoryMonitoringClassDiagram.puml
│   ├── AuditTraceabilityClassDiagram.puml
│   ├── DashboardOverviewClassDiagram.puml
│   ├── EnvironmentalComplianceClassDiagram.puml
│   ├── IdentityAccessClassDiagram.puml
│   ├── IncidentManagementClassDiagram.puml
│   ├── RemoteControlActuationClassDiagram.puml
│   ├── ReportsAnalyticsClassDiagram.puml
│   ├── SensorMonitoringClassDiagram.puml
│   ├── SubscriptionBillingClassDiagram.puml
│   └── UserProfilesClassDiagram.puml
├── safelab-uml-diagrams.csproj
├── safelab-uml-diagrams.sln
└── src
    └── images/
```

---

## Bounded Contexts Included

### Generic / Supporting

1. **Identity & Access Management**  
   Manages authentication, authorization, users, roles, sessions, credentials, and access permissions.

2. **User Profiles**  
   Manages user profile information, organization profiles, contact data, preferences, and notification settings.

3. **Subscription & Billing**  
   Manages plans, subscriptions, invoices, payments, and billing accounts.

4. **Dashboard & Overview**  
   Provides dashboard widgets, KPIs, summaries, filters, and operational overview information.

### Core Domain

5. **Asset & Inventory Monitoring**  
   Models assets, equipment, storage units, inventory items, and stock movements.

6. **Sensor Monitoring**  
   Models sensors, readings, threshold rules, telemetry batches, and calibration records.

7. **Environmental Compliance**  
   Models compliance rules, storage conditions, evaluations, violations, and compliance evidence.

8. **Alerts & Notifications**  
   Models alerts, notifications, recipients, delivery rules, and escalation policies.

9. **Remote Control & Actuation**  
   Models remote commands, actuators, command executions, safety rules, and device control policies.

10. **Reports & Analytics**  
    Models reports, templates, analytics metrics, trend analysis, and export files.

11. **Incident Management**  
    Models incidents, assignments, corrective actions, resolution records, and incident evidence.

12. **Audit & Traceability**  
    Models audit logs, activity events, traceability records, change records, and traceability timelines.

---

## Technologies

- PlantUML
- UML Class Diagrams
- C#
- .NET Solution Structure
- Domain-Driven Design (DDD)

---

## How to Generate Diagrams

Install PlantUML and run:

```bash
plantuml diagrams/*.puml
```

Generated images can be stored in:

```text
src/images/
```

---

## Purpose

This repository supports the following project section:

```text
4.7. Object-Oriented Design Software
4.7.1. Class Diagrams
```

It provides the object-oriented model used to connect SafeLab's bounded contexts with future database design and implementation artifacts.

---

## Recommended Workflow

1. Update or create `.puml` files inside `diagrams/`.
2. Generate diagram images with PlantUML.
3. Store exported images in `src/images/`.
4. Reference the diagrams in the final project report.
5. Keep class names, relationships, and enumerations aligned with SafeLab's bounded contexts.

---

## License

Academic and educational use only.
