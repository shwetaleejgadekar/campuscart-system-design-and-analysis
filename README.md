# CampusCart — System Design & Analysis

Designed the complete system architecture for **CampusCart**, a campus-exclusive
peer-to-peer marketplace enabling university students to securely buy, sell, and
exchange second-hand items. The project covers the full SDLC from requirements
gathering through financial feasibility analysis.

## Problem Solved

Campus students lack a structured, verified platform for exchanging second-hand goods.
Existing informal channels (group chats, bulletin boards) have no authentication,
no moderation, and no trust mechanisms. CampusCart addresses this with a
campus-email-verified, moderated, mobile-first marketplace.

## System Capabilities Designed

- **Verified Authentication** — Campus email-based login restricting access to
  enrolled students and staff
- **Item Listings** — Photo uploads, categorization, and keyword-based search
  with price and category filters
- **In-App Messaging** — Secure buyer-seller chat for negotiation and pickup
  coordination without exposing personal contact details
- **Drop-Off Zone System** — PIN-based item pickup from designated campus zones
  with seller confirmation and rescheduling flows
- **Item Alert System** — Buyers set alerts by keyword or category; system
  notifies both buyer and seller when a match is posted
- **Admin Dashboard** — Content moderation, dispute resolution, and listing
  management
- **Advertisement Space** — Campus clubs and departments can promote events
  within the platform

## Deliverables

| Artifact | Description |
|---|---|
| Requirements & Stakeholder Analysis | Functional requirements, interview objectives for students, facilities team, and club representatives |
| Use Case Diagram | 12 use cases across Buyer, Seller, and Facilities Team actors |
| Use Case Descriptions | Detailed flow of activities, pre/postconditions, and exception handling |
| Activity Diagrams | Step-by-step swimlane flows for pickup request and item alert workflows |
| Domain Class Diagram | 14 entities including User, Listing, Transaction, Alert, DropOffZone, Pin, and EmailNotification |
| System Sequence Diagrams | Interaction traces with loop and alt fragments for core use cases |
| State Diagram | Item lifecycle from Listed → Selected → Booked → Awaiting Pickup → Picked Up / Cancelled / Deal Completed |
| Network Diagram | Deployment architecture across system nodes |
| UI Design | Buyer and Seller interface mockups built in Figma |
| Cost-Benefit Analysis | 5-year financial model with NPV of $20,484, IRR of 36.11%, and payback period of 2.5 years |
| Gantt Chart | 14-task project timeline from requirements gathering to campus launch |

## Financial Feasibility

| Metric | Value |
|---|---|
| Initial Investment | $24,000 |
| Payback Period | 2.5 years |
| NPV (10% discount) | $20,484 |
| IRR | 36.11% |
| Profitability Index | 1.85 |

## Tech Stack & Tools
`Draw.io` · `Figma` · `UML` · `Systems Analysis` · `SDLC` · `Cost-Benefit Analysis`

## Files
- `docs/` — Full technical report
- `system-design-diagrams/` — All UML and UI diagrams in editable formats

*Collaborative project — MS Information Systems, Santa Clara University*