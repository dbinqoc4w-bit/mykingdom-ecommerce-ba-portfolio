# MyKingdom E-Commerce — Business Analyst Portfolio

> **Business Analysis project** for the e-commerce website of MyKingdom (mykingdom.com.vn) — Vietnam's largest toy retail chain with 200+ stores nationwide.  


---

## Project Overview

| Field | Details |
|---|---|
| **Project Name** | MyKingdom E-Commerce Website — BA Portfolio |
| **Domain** | Retail / E-Commerce |
| **Platform** | Web (Shopify custom theme) |
| **Scope** | 9 functional modules (Authentication, Search, Product List, User Profile, Product Detail, Cart, Store Locator, Checkout, Wishlist) |
| **My Role** | Business Analyst — Requirements Gathering, Process Modeling, Documentation |
| **Tools Used** | draw.io, Figma, Google Sheets, Microsoft Word, GitHub |
| **Timeline** | 2026 |

---

## Problem Statement

MyKingdom operates 200+ physical stores across all 63 provinces in Vietnam but lacked a proper online sales channel. Key pain points identified:

- Customers in provinces without a physical store had no access to products
- No 24/7 shopping capability — limited to store opening hours
- Customers could not check stock availability or prices before visiting
- My Points loyalty program had no online integration
- Competitors (Lazada, Shopee) already had strong online presence

**Goal:** Design and document a complete e-commerce platform that extends MyKingdom's reach online, supports 5 payment methods, and integrates seamlessly with the existing loyalty program.

---

## Repository Structure

```
mykingdom-ecommerce-ba-portfolio/
│
├── 01-BRD/
│   └── BRD_MyKingdom_v1.0.docx          # Business Requirements Document
│
├── 02-SRS/
│   └── SRS_MyKingdom_Nhom3.pdf          # Software Requirements Specification
│
├── 03-BPMN/
│   ├── BPMN_AsIs_Offline_Purchase.png   # As-Is process (offline shopping)
│   └── BPMN_ToBe_Online_Checkout.png    # To-Be process (online checkout)
│
├── 04-Wireframes/
│   └── [Figma link or screenshots]      # Low-fi wireframes for 4 key screens
│
├── 05-RTM/
│   └── RTM_MyKingdom.xlsx               # Requirement Traceability Matrix
│
├── 06-TestCases/
│   └── TestCases_MyKingdom.xlsx         # Test cases (Google Sheets export)
│
└── README.md
```

---

## Key Deliverables

### 1. Business Requirements Document (BRD)
- Executive Summary & business context
- Stakeholder Register (8 stakeholders)
- As-Is state analysis with 5 identified pain points
- To-Be solution mapping
- 10 Business Requirements linked to Business Goals
- **Success Criteria:** 8 technical KPIs + 7 business KPIs (SMART format)
- Requirement Traceability Matrix overview

### 2. Software Requirements Specification (SRS)
Full functional specification for 9 modules:

| Module | Description |
|---|---|
| M-01 Authentication | Register, login, forgot password, email subscription |
| M-02 Search | Keyword search, autocomplete, filters, sort |
| M-03 Product List | Category listing, badges (NEW/SALE/OUT OF STOCK), filters |
| M-04 User Profile | Personal info, order history, My Points, address management |
| M-05 Product Detail | Image gallery, specs, add to cart, wishlist, installment info |
| M-06 Cart | Add/remove/update items, terms confirmation, checkout |
| M-07 Store Locator | Search by province, Google Maps integration, directions |
| M-08 Checkout | Address, shipping, COD/ZaloPay, VAT invoice, discount code |
| M-09 Wishlist | Save products, multi-device sync, add to cart from wishlist |

### 3. BPMN Process Diagrams
- **As-Is:** Offline purchase flow with 4 swim lanes (Customer / Sales Staff / Cashier / POS System) — annotated with pain points
- **To-Be:** Online checkout flow with 4 swim lanes (Customer / Website / ZaloPay / Backend) — annotated with improvements

### 4. Requirement Traceability Matrix (RTM)
Links Business Goals → Business Requirements → SRS Requirement IDs → Test Cases

---

## Key Business Requirements

| BR ID | Business Requirement | Priority |
|---|---|---|
| BR-01 | System must allow customers to place and pay orders fully online | Must Have |
| BR-02 | System must support at least 5 payment methods (COD, ZaloPay, MoMo, VNPAY, installment) | Must Have |
| BR-03 | System must display full product info (images, price, stock, age range) | Must Have |
| BR-04 | My Points must be auto-credited after each completed order | Must Have |
| BR-05 | System must support smart search by keyword, brand, age, and price range | Must Have |
| BR-07 | System must offer express delivery (4hrs inner city) and nationwide shipping | Must Have |
| BR-08 | Payment data must comply with PCI-DSS security standards | Must Have |

---

##Success Criteria (KPIs)

### Technical KPIs (measured at go-live)
| KPI | Target |
|---|---|
| Homepage load time | ≤ 3 seconds |
| Search response time | ≤ 2 seconds |
| System uptime | ≥ 99.9% |
| Payment error rate | < 0.1% of transactions |
| Responsive display | 320px – 1920px, all major browsers |

### Business KPIs (measured after 3–6 months)
| KPI | Target |
|---|---|
| Online conversion rate | ≥ 1.5% |
| Checkout completion rate | ≥ 65% |
| Monthly online orders | ≥ 500 orders/month (by month 3) |
| Cart abandonment rate | ≤ 70% |
| Net Promoter Score (NPS) | ≥ 40 |

---

##Tools & Techniques

| Category | Tools / Methods |
|---|---|
| Process Modeling | draw.io (BPMN 2.0) |
| Wireframing | Figma |
| Documentation | Microsoft Word, PDF |
| Test Management | Google Sheets |
| Requirements | Use Case Specification, User Stories, Business Rules |
| Elicitation | Document Analysis, Website Walkthrough, Benchmarking, Stakeholder Interview (simulated) |
| Version Control | GitHub |

---

##Author & Contact

| Name | Contact |
|---|---|
| Dang Bich Ngoc| 0961084577 - dbinqoc4w@gmail.com |



---

#Notes

> This project is a **BA portfolio simulation** based on analysis of the live website [mykingdom.com.vn](https://www.mykingdom.com.vn). Stakeholder interviews and sign-offs are simulated based on document analysis and website walkthrough. All business data referenced is publicly available.

---

## Contact

If you have any questions about this project, feel free to reach out via GitHub Issues.

