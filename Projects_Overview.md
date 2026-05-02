# Projects Overview
**Delivery Plus — Business Tools & Systems**
*Last updated: May 2, 2026*

---

## 1. 🚚 Delivery Plus Tool (`deliveryplus-tool`)

**The core operational platform for the business.**

This is a full-stack internal tool split into a backend API and a web dashboard. It handles the day-to-day operations of the delivery business.

**Backend** (Node.js / TypeScript)
- Employee authentication & module-level permissions
- COD (Cash on Delivery) management
- Lorry Receipt (LR) form processing
- Trip & transaction tracking
- Expense management with OCR (auto-reads receipts)
- Petty cash & reconciliation
- Recovery tracking
- Vendor & vehicle management
- Hub management
- WhatsApp bot integration
- Data exports

**Dashboard** (React / Vite / TypeScript)
- COD module
- Expense module
- Lorry Receipt module
- Losses & Recovery module
- Vendor & Vehicle management
- User management

---

## 2. 📧 Delivery Plus Automailer (`deliveryplus-automailer`)

**Automated email reporting and alert system.**

A Next.js application that handles scheduled email automation for various business reports and operational alerts.

**Key modules:**
- **Mail Automation Dashboard** — Send business reports via email
- **Brazoo Delivery Tracker** — Monitor shortage mails, SLA responses, and follow-ups
- **COD Automailer** — Automated COD-related emails
- **HR Automailer** — HR communication automation
- **Operations Performance** — Automated performance reports
- **Recovery & Losses** — Automated alerts for losses/recovery
- **Cron Jobs** — Scheduled tasks for all automation

---

## 3. 📦 Delivery Plus Inventory (`deliveryplus-inventory`)

**Inventory and warehouse management system.**

A Next.js application to track stock, products, suppliers, and assets across the business.

**Key modules:**
- Dashboard with analytics
- Inventory management
- Categories & stock tracking
- Barcode scanning support
- Supplier management
- Asset tracking
- Reports generation
- Maintenance logs

---

## 4. 🌐 Delivery Plus Website (`deliveryplus-website`)

**Company's public-facing website.**

Built with Next.js. A marketing and information website for the Delivery Plus brand.

**Pages:**
- Home
- About Us
- Careers
- Contact Us
- Tech Stack showcase

---

## 5. 🏢 ERP System (`erp`)

**Enterprise Resource Planning — early stage / in development.**

A full-stack ERP system with a React frontend and Node.js/TypeScript backend using Prisma ORM.

**Frontend** (React / Vite)
- Login page
- Main dashboard
- Settings panel

**Backend** (Node.js / TypeScript / Prisma)
- Auth routes
- Settings routes
- Database via Prisma ORM


---

## 6. 🤖 LinkedIn Bot (`linkedin-bot`)

**Recruitment & outreach automation bot.**

A TypeScript bot using Puppeteer (headless browser) to automate recruitment workflows across multiple platforms.

**Platforms automated:**
- LinkedIn — Candidate outreach & messaging
- Naukri — Job postings & candidate search
- Gmail — Email communication
- Upwork — Freelancer sourcing
- Apollo — Lead generation
- Bank — (banking task automation)
- ChatGPT — AI-assisted responses
- Website parsing — Data extraction from external sites

**Integrations:** Sentry (error tracking), MongoDB, Supabase, Slack (output notifications), Langfuse (LLM observability)

---

## 7. 📡 RFID Inventory System (`rfid`)

**RFID-based warehouse & inventory management.**

A PHP application (CodeIgniter 4 framework) for managing physical inventory using RFID technology.

**Key modules:**
- Dashboard
- Warehouse management
- Inventory tracking
- Product & item management
- Inspection workflows
- Reports & audit logs
- User management with granular permissions

---

## Quick Summary Table

| Project | Type | Tech Stack | Purpose |
|---|---|---|---|
| Delivery Plus Tool | Full-stack (Internal) | Node.js, React, Vite | Core ops: COD, trips, expenses, vendors |
| Automailer | Web App | Next.js | Automated email reports & alerts |
| Inventory | Web App | Next.js | Stock, barcode, suppliers, assets |
| Website | Marketing Site | Next.js | Public company website |
| ERP | Full-stack | React, Node.js, Prisma | Enterprise resource planning (WIP) |
| Face Attendance | AI System | Python, FastAPI, Next.js | Facial recognition attendance |
| LinkedIn Bot | Automation Bot | TypeScript, Puppeteer | Recruitment & outreach automation |
| RFID | Web App | PHP, CodeIgniter 4 | RFID-based warehouse management |
| Portfolio | Website | React, Sanity CMS | Portfolio showcase |
| Everything Claude Code | OSS Resource | Multi-language | Claude AI tools & prompts (community) |
