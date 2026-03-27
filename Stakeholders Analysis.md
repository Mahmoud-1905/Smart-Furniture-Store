# 2. Stakeholder Analysis

## 2.1 Stakeholder Register

| # | Stakeholder | Role | Interest | Influence | Key Concern |
|---|-------------|------|----------|-----------|-------------|
| 1 | Project Supervisor | Academic Oversight | High | High | Technical standards, deadlines, documentation |
| 2 | System Administrator | Platform Governance | High | High | Security, uptime, analytics, fraud prevention |
| 3 | Vendors (Sellers) | Business Operations | High | Medium | Ease of product listing, sales reports, inventory |
| 4 | Customers (Buyers) | End Users | High | Low | Payment security, UI/UX, order tracking accuracy |
| 5 | Development Team | Technical Implementation | High | High | System scalability, API stability, clean code |
| 6 | Payment Providers | Financial Integration | Medium | Medium | Transaction success rates, API uptime |

## 2.2 Stakeholder Map

```mermaid
quadrantChart
    title Stakeholder Influence vs. Interest
    x-axis Low Interest --> High Interest
    y-axis Low Influence --> High Influence
    quadrant-1 Manage Closely
    quadrant-2 Keep Satisfied
    quadrant-3 Monitor
    quadrant-4 Keep Informed
    "Project Supervisor": [0.90, 0.95]
    "System Administrator": [0.85, 0.90]
    "Development Team": [0.80, 0.85]
    "Vendors": [0.75, 0.60]
    "Customers": [0.70, 0.30]
    "Payment Providers": [0.50, 0.45]

   ```

## 2.3 Stakeholder Needs Summary

**Project Supervisor** — Needs to ensure the project correctly follows the Agile methodology and that the code and documentation meet the required academic standards for graduation.

**System Administrator** — Needs a robust admin dashboard to monitor vendor activity, review orders, manage user accounts, and generate overall performance reports.

**Vendors (Sellers)** — Need an easy-to-use interface to manage their inventory, update product prices, and receive instant notifications when purchasing any product from their store.

**Customers (Buyers)** — Need a fast-loading shopping experience, a secure payment system, an accurate product search engine, and a clear page to track the status of their orders.

**Development Team** — Needs a stable development environment and an organized database (ERD) that prevents vendor data overlap and ensures fast API response times.

---
[← Back to Introduction](Introduction.md) | [Next: Requirements Analysis →](./02-Requirements-analysis.md)
