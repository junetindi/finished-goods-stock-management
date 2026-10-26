# Finished Goods Stock Management System

**A database-driven inventory application for tracking finished goods receipts, stock issues, and inventory balances in a manufacturing environment.**

Built with **Appsmith, Supabase, PostgreSQL, and REST APIs**, this project demonstrates the application of database-driven software to finished goods inventory management.

## Application Preview

<p align="center">
  <img src="Screenshot%202026-10-17%20194541.png" alt="Finished Goods Stock Management System Preview" width="100%" style="border-radius: 8px;">
</p>

## Overview

Manufacturing businesses need reliable visibility into finished goods as products enter and leave the store. Accurate stock records help teams monitor inventory availability, review transactions, and reconcile stock balances.

The Finished Goods Stock Management System was developed to organize inventory transactions and provide a structured view of finished goods movement.

The project applies practical manufacturing knowledge to business application development, with a focus on stock visibility, profile identification, and inventory control.

## Business Problem

A manufacturing team needs to answer important inventory questions:

- Which finished goods have been received into the store?
- Which products have been issued out?
- What is the available stock balance for a given profile code?
- How can stock transactions be searched and reviewed?
- How can finished goods inventory information support production and order fulfilment?

This application provides a database-backed interface for reviewing finished goods transactions and monitoring stock balances.

## Key Capabilities

- **Receipt-in tracking** — record finished goods entering inventory.
- **Receipt-out tracking** — maintain records of finished goods issued from stock.
- **Stock balance monitoring** — calculate inventory balances from recorded stock movements.
- **Profile-code identification** — organize and match inventory using product profile codes.
- **Transaction search and filtering** — make relevant inventory records easier to locate.
- **Database-backed records** — store and retrieve inventory information using Supabase and PostgreSQL.
- **Structured business interface** — use Appsmith to present stock records and inventory information.
- **Manufacturing workflow support** — complement production tracking by providing visibility into finished goods movement.

## Technology Stack

| Technology | Role |
|---|---|
| Appsmith | Application interface, tables, and user interactions |
| Supabase | Backend platform and database access |
| PostgreSQL | Relational database for inventory records |
| REST APIs | Communication between the application and backend |
| JavaScript | Application logic and data handling |

## Application Architecture

The application follows a client-to-database architecture:

**User → Appsmith interface → Supabase REST API → PostgreSQL database**

1. Users interact with inventory records through the Appsmith interface.
2. Application queries retrieve or update data through the Supabase REST API.
3. PostgreSQL stores the underlying inventory records.
4. The application presents transaction data and stock balances for review.

This structure demonstrates the integration of a business application interface with a relational database and API-based data access.

## Skills Demonstrated

- Inventory workflow modelling
- Manufacturing process understanding
- Relational database concepts
- PostgreSQL fundamentals
- REST API integration
- Data-driven application development
- Stock movement and balance tracking
- Translating operational requirements into software workflows

## Project Context

This portfolio project complements my WIP Management & Production Control System. While the WIP project focuses on production progress and work-in-progress quantities, this application focuses on finished goods receipts, issues, and inventory balances.

Together, the projects demonstrate practical experience in modelling manufacturing workflows and developing database-driven business applications.

## Intended Applications

The concepts demonstrated in this project are relevant to:

- ERP and application support
- Inventory and warehouse management
- Manufacturing information systems
- ERP implementation and functional support
- Business application development
- Stock control and reconciliation

## Related Project

[WIP Management & Production Control System](https://github.com/junetindi/wip-management-production-control)

## Author

**June Tindi**  
Kenya

## Project Status

Developed as a practical portfolio project demonstrating inventory management workflows and business application development.
