# Data Architecture

Data architecture encompasses data persistence, documentation, and integration.

## Introduction

Data architecture defines how data moves from point A to point B - encompassing integration, pipelines, and data warehouses. It must address challenges related to scalability, documentation, and performance.

## Data Modeling

Includes schemas and data warehouses to ensure consistency, accessibility, and scalability of data systems to support future growth (e.g., new regions, features like live audio).. It should be secure-by-design, which is fundamental for protecting data integrity and access.

### ETL/ELT

ETL/ELT tools (Extract, Transform, Load / Extract, Load, Transform) automate data pipelines, ensuring efficient and secure data flow across systems. They also support:

- Database performance optimization

- Backup management

- Data recovery in case of incidents

The nefits of strong data architecture:

- Avoids bottlenecks

- Reduces error risk

- Ensures real-time data availability

## Spotify's Situation

Spotify's data infrastructure is highly sophisticated, combining data lakes, relational databases, and cloud storage systems. Data is ingested, processed, and analyzed in real time to provide up-to-date insights and support decision-making across the organization.

## Specific Problem: Data Silos

Spotify's rapid growth has led to the development of data silos within the organization. Departments such as marketing, product development, content curation, and engineering manage their own datasets independently, often ending up with inconsistent or incomplete views of the same user or content.
For example, the marketing team might have detailed insight into user engagement with ad-supported content, while product development focuses on user interactions with premium features - two partial pictures of the same user that never get reconciled.
This fragmentation makes it difficult to access the right data at the right time and limits the ability to perform cross-source analytical tasks (BI, dashboards), hindering a comprehensive view of user or content status.

Consequences of unresolved silos:

- Inefficiencies and duplication of effort across departments

- Missed opportunities for cross-departmental collaboration

- Difficulty reconstructing the full user journey (e.g., from content discovery to subscription conversion) since it requires pulling data from multiple disconnected sources

- Blind spots in decision-making caused by fragmented, non-holistic data

## Data Accessibility and Integration

As Spotify continues to innovate, integrated and accessible data becomes increasingly critical. For example, launching a new personalized playlist feature might require combining user listening habits with social media engagement data. If these datasets remain siloed, product development slows and new features lose effectiveness.

## Objectives for a Data Architecture Framework in the Data Governance Model

Focus Area

GoalKey ActionData Architecture & IntegrationOrganize and integrate data across systems and regionsBuild a unified data lake; implement master data management (MDM) for user and content dataGovernance OwnershipAssign clear architectural accountabilityAppoint a Head of Data Engineering / Architecture to own cross-team integration standards

Reference Data Management (RDM) complements MDM by ensuring rigor specifically for externally sourced reference data (e.g., exchange rates) that feeds internal databases and directly affects analysis quality. Metadata plays a self-documenting role — capturing data's origin, context, and quality — enabling discovery, understanding, and reuse across teams (operationalized by Data Stewards, see Roles section).

To achieve this:

- Implement a data governance framework ensuring consistent, comprehensive management of data across all teams

- Build a unified data lake to consolidate fragmented departmental datasets

- Implement master data management (MDM) for core entities (user, content) so all teams reference a single source of truth

- Define shared data access standards so employees across departments can reliably find and use high-quality data

- Establish cross-team integration protocols before launching new features that depend on multiple data sources (e.g., listening + social data for playlist personalization)

The unified data lake and MDM system must be designed to support the Privacy Team and DPO in fulfilling Data Subject Access Requests (DSARs) — a fragmented architecture makes it far harder to locate, export, or delete a single user's data across systems within regulatory deadlines.