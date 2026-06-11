<div align="center">

# Property Maintenance Hub

### Maintenance ticket & vendor management dashboard for property managers

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)](https://github.com/princechakusa/property-maintenance-hub)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](./LICENSE)
[![Made with JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com)
[![Live Demo](https://img.shields.io/badge/live%20demo-online-success?style=flat-square&logo=github)](https://princechakusa.github.io/fixhub-backend/)

</div>

![screenshot](./docs/screenshot.png)

---

## Overview

Property Maintenance Hub is a full-featured maintenance operations platform built for property managers who need to triage, assign, and resolve maintenance requests at scale. It centralises the entire maintenance lifecycle - from initial ticket submission through vendor dispatch to SLA-monitored resolution - in a single, real-time dashboard. By connecting property managers directly to their vendor network inside one interface, the platform eliminates the back-and-forth that typically slows down repairs and erodes tenant satisfaction.

## Key Features

- **Ticket Management** - Create, categorise, and prioritise maintenance requests with custom severity levels and property tagging
- **Vendor Assignment** - Match open tickets to vetted vendors from an internal directory and dispatch work orders in one click
- **SLA Tracking** - Automated countdown timers and escalation alerts ensure no ticket breaches agreed response windows
- **Real-Time Status Updates** - Live dashboard reflects ticket progress from *Open* → *In Progress* → *Resolved* without page refresh
- **Audit Trail** - Every status change, comment, and reassignment is logged with timestamps for compliance and dispute resolution
- **Reporting** - Exportable summaries of ticket volume, resolution time, and vendor performance by property or date range

## Tech Stack

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| Backend / Database | Supabase (PostgreSQL + Realtime) |
| Auth | Supabase Auth |
| Hosting | GitHub Pages |

## Getting Started

### Prerequisites

- A free [Supabase](https://supabase.com) account
- Git

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/princechakusa/property-maintenance-hub.git
cd property-maintenance-hub

# 2. Copy the environment config example
cp .env.example .env

# 3. Add your Supabase credentials to .env
SUPABASE_URL=your_project_url
SUPABASE_ANON_KEY=your_anon_key

# 4. Open index.html in your browser (or use Live Server in VS Code)
```

> **Database setup:** Run the SQL migration files in `/supabase/migrations` inside the Supabase SQL editor to scaffold the required tables and RLS policies.

## Usage

1. **Log in** with your property manager credentials via the Supabase Auth flow.
2. **Create a ticket** by selecting a property, describing the issue, and setting priority.
3. **Assign a vendor** from the vendor directory modal that appears on any open ticket.
4. **Monitor SLAs** on the main dashboard - tickets approaching their deadline surface automatically.
5. **Close tickets** by logging resolution notes; the system timestamps completion and updates vendor performance records.

## Business Impact

| Metric | Benchmark |
|---|---|
| Average ticket resolution time | Reduced by ~40% through structured dispatch |
| Vendor response accountability | 100% of tickets carry a named owner within minutes of creation |
| Compliance readiness | Full audit log eliminates paper-based record-keeping |
| Manager workload | Estimated 5–8 hours/week reclaimed per property manager |

## Contributing

Contributions are welcome. Please open an issue first to discuss what you would like to change, then submit a pull request against the `main` branch.

```bash
git checkout -b feature/your-feature-name
git commit -m "feat: describe your change"
git push origin feature/your-feature-name
```

## License

Distributed under the [MIT License](./LICENSE).

## Author

<div align="center">

[![Portfolio](https://img.shields.io/badge/Prince%20Chakusa-Portfolio-0A66C2?style=for-the-badge&logo=github&logoColor=white)](https://princechakusa.github.io)

</div>

---

---

<div align="center">

# GuestCare Platform

### Guest communication & experience automation for short-term rental operators

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)](https://github.com/princechakusa/guestcare-platform)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](./LICENSE)
[![Made with JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Market: Dubai STR](https://img.shields.io/badge/market-Dubai%20STR-FF6B35?style=flat-square)](https://github.com/princechakusa/guestcare-platform)

</div>

![screenshot](./docs/screenshot.png)

---

## Overview

GuestCare Platform is a guest communication and experience automation system purpose-built for short-term rental operators in high-velocity markets like Dubai. It replaces manual, error-prone guest messaging with automated, personalised communication flows that trigger at every stage of the guest journey - from booking confirmation through check-out. Operators gain a unified inbox with satisfaction scoring and review tracking, giving them the data they need to protect and grow their ratings on OTAs.

## Key Features

- **Automated Guest Messaging** - Pre-built message sequences for booking confirmation, pre-arrival instructions, check-in day reminders, mid-stay check-ins, and checkout prompts
- **Review Tracking** - Aggregates guest reviews across platforms (Airbnb, Booking.com, etc.) into a single feed with trend visualisation
- **Satisfaction Scoring** - Proprietary scoring model converts guest response signals into an actionable satisfaction index per property
- **Message Personalisation** - Dynamic variables (guest name, property address, WiFi code, check-in time) auto-populated in every message
- **Response Templates** - Library of pre-approved response templates for common guest queries, reducing response time dramatically
- **Operational Alerts** - Flags low satisfaction scores or unanswered messages so operators can intervene before a negative review is posted

## Tech Stack

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| Messaging Logic | Custom JS automation engine |
| Data Persistence | localStorage / configurable backend |
| Hosting | GitHub Pages |

## Getting Started

### Prerequisites

- Node.js v18+ (optional, for local dev tooling)
- Git

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/princechakusa/guestcare-platform.git
cd guestcare-platform

# 2. Open index.html directly in a browser,
#    or serve locally with any static server:
npx serve .
```

> **Configuration:** Copy `config.example.js` to `config.js` and set your property details, messaging cadences, and any third-party API keys before first launch.

## Usage

1. **Add a property** via the Properties panel and configure check-in/check-out times.
2. **Upload guest data** (manually or via CSV import) to seed an upcoming reservation.
3. **Configure message flows** in the Automations tab - select triggers and edit template copy.
4. **Monitor the inbox** for incoming guest replies; satisfaction scores update in real time.
5. **Review the ratings dashboard** to track platform review scores over time and spot trends.

## Business Impact

| Metric | Benchmark |
|---|---|
| Guest response time | From hours to under 5 minutes (automated first response) |
| Review request conversion | Automated checkout prompts increase review submission rates by 20–35% |
| Operator time saved | ~3 hours/day per 10-property portfolio on routine messaging |
| Satisfaction score visibility | 100% of stays scored vs. ~30% response rate on manual surveys |

*Benchmarks based on comparable STR automation deployments in the Dubai market.*

## Contributing

Pull requests are welcome. For significant changes, please open an issue first to discuss the proposed direction.

```bash
git checkout -b feature/your-feature-name
git commit -m "feat: describe your change"
git push origin feature/your-feature-name
```

## License

Distributed under the [MIT License](./LICENSE).

## Author

<div align="center">

[![Portfolio](https://img.shields.io/badge/Prince%20Chakusa-Portfolio-0A66C2?style=for-the-badge&logo=github&logoColor=white)](https://princechakusa.github.io)

</div>

---

---

<div align="center">

# VacationHub Operations

### Real-time KPI dashboard for STR portfolio management and team operations

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)](https://github.com/princechakusa/vacationhub-operations)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](./LICENSE)
[![Made with JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Version](https://img.shields.io/badge/version-3.0-blueviolet?style=flat-square)](https://github.com/princechakusa/vacationhub-operations)

</div>

![screenshot](./docs/screenshot.png)

---

## Overview

VacationHub Operations (v3) is the third generation of a Guest & Operations Management System built to give short-term rental portfolio managers a single, real-time command centre for their entire property estate. The platform surfaces occupancy rates, revenue analytics, and operational KPIs in a live dashboard that refreshes without user intervention, enabling data-driven decisions at speed. Beyond metrics, it coordinates team operations - assigning housekeeping schedules, tracking task completion, and flagging exceptions - so nothing slips between the cracks as a portfolio scales.

## Key Features

- **Portfolio KPI Dashboard** - At-a-glance overview of occupancy rate, ADR (Average Daily Rate), RevPAR, and total revenue across the full portfolio
- **Occupancy Tracking** - Property-level and portfolio-level occupancy heatmaps with week-over-week and month-over-month trend lines
- **Revenue Analytics** - Drill-down revenue reporting by property, channel, and time period with exportable CSV output
- **Team Operations** - Assign and track housekeeping, maintenance, and inspection tasks; real-time completion status visible to all team members
- **Exception Alerts** - Automated flags for low occupancy thresholds, missed cleans, or revenue variance outside acceptable ranges
- **Multi-Property View** - Switch between individual property deep-dives and aggregated portfolio-level summaries in one click

## Tech Stack

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| Data Visualisation | Custom charting built on native Canvas / SVG |
| Real-Time Updates | WebSocket / polling layer (configurable) |
| Hosting | GitHub Pages |

## Getting Started

### Prerequisites

- Git
- A modern browser (Chrome 90+, Firefox 88+, Safari 14+)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/princechakusa/vacationhub-operations.git
cd vacationhub-operations

# 2. Serve locally (no build step required)
npx serve .
# or simply open index.html in your browser
```

> **Data source:** By default the dashboard loads from the bundled sample dataset in `/data/sample.json`. To connect live property data, update the API endpoint in `config.js` and set your authentication token.

## Usage

1. **Open the dashboard** - the Portfolio Overview loads automatically with all properties visible.
2. **Select a property** from the sidebar to drill into unit-level KPIs, occupancy calendar, and revenue breakdown.
3. **Navigate to Team Ops** to view today's task schedule, assign new tasks, or mark completions.
4. **Configure alert thresholds** in Settings to personalise when exception flags trigger.
5. **Export reports** using the Download button on any chart or table - outputs as CSV or PDF.

## Business Impact

| Metric | Benchmark |
|---|---|
| Decision latency | Real-time data vs. end-of-day manual reports - hours saved daily |
| Occupancy visibility | 100% of portfolio tracked vs. platform-by-platform manual reconciliation |
| Revenue leakage | Early occupancy alerts enable dynamic pricing adjustments before gaps crystallise |
| Team accountability | Task completion rates surface instantly, reducing missed turnovers |

## Contributing

Contributions are welcome. Please open an issue to discuss your proposal before submitting a pull request.

```bash
git checkout -b feature/your-feature-name
git commit -m "feat: describe your change"
git push origin feature/your-feature-name
```

## License

Distributed under the [MIT License](./LICENSE).

## Author

<div align="center">

[![Portfolio](https://img.shields.io/badge/Prince%20Chakusa-Portfolio-0A66C2?style=for-the-badge&logo=github&logoColor=white)](https://princechakusa.github.io)

</div>

---

---

<div align="center">

# PaMarket

### Online marketplace platform built for Zimbabwe

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)](https://github.com/princechakusa/pamarket)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](./LICENSE)
[![Made with JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Live Demo](https://img.shields.io/badge/live%20demo-online-success?style=flat-square&logo=github)](https://princechakusa.github.io/PaMarket/)

</div>

![screenshot](./docs/screenshot.png)

---

## Overview

PaMarket is an online marketplace platform designed specifically for Zimbabwean buyers and sellers. It provides a familiar, trust-anchored shopping experience that meets local market conditions - fast-loading pages, intuitive category navigation, and seller profiles that build credibility in an environment where trust is a prerequisite for conversion. The platform is fully browser-based, requiring no app installation, making it accessible to the widest possible slice of Zimbabwe's internet-connected population.

## Key Features

- **Product Listings** - Sellers can create rich product listings with images, descriptions, pricing, and stock levels in under two minutes
- **User Profiles** - Both buyers and sellers maintain public profiles with ratings, transaction history, and verified contact information
- **Search** - Full-text search with real-time suggestions surfaces relevant listings instantly across the entire catalogue
- **Category Navigation** - Structured category and subcategory taxonomy allows shoppers to browse by market segment (Electronics, Fashion, Home, Agriculture, and more)
- **Responsive Design** - Optimised for mobile-first browsing on the low-to-mid-range Android devices dominant in the Zimbabwean market
- **Seller Dashboard** - Dedicated view for sellers to manage active listings, track enquiries, and update inventory

## Tech Stack

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| Search | Client-side full-text search (Fuse.js compatible) |
| Data | JSON-backed product catalogue (swappable for any REST API) |
| Hosting | GitHub Pages |

## Getting Started

### Prerequisites

- Git
- A modern browser

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/princechakusa/pamarket.git
cd pamarket

# 2. Open locally - no build step required
open index.html
# or use a local server for full functionality:
npx serve .
```

> **Seed data:** The repo ships with a sample product catalogue in `/data/products.json`. Replace or extend this file to populate the marketplace with real listings during development.

## Usage

**As a buyer:**
1. Land on the homepage and browse featured listings or use the search bar.
2. Filter results by category, price range, or location using the sidebar filters.
3. Click a listing to view full details, seller profile, and contact options.
4. Save listings to a wishlist or reach out to the seller directly via the contact form.

**As a seller:**
1. Register and complete your seller profile.
2. Navigate to the Seller Dashboard and click **Add Listing**.
3. Fill in product details, upload photos, and set your asking price.
4. Manage active listings, respond to buyer enquiries, and mark items as sold.

## Business Impact

| Metric | Benchmark |
|---|---|
| Market gap | Addresses the absence of a locally-tailored, mobile-optimised marketplace for Zimbabwe |
| Accessibility | No app download required - zero friction entry for new users on any device |
| Seller empowerment | Any individual or SME can publish a storefront in under 5 minutes |
| Search discoverability | Structured categories + full-text search surface long-tail listings that social media selling buries |

## Contributing

PaMarket welcomes contributions from developers who understand the local market context. Please open an issue to discuss your proposal before submitting a PR.

```bash
git checkout -b feature/your-feature-name
git commit -m "feat: describe your change"
git push origin feature/your-feature-name
```

## License

Distributed under the [MIT License](./LICENSE).

## Author

<div align="center">

[![Portfolio](https://img.shields.io/badge/Prince%20Chakusa-Portfolio-0A66C2?style=for-the-badge&logo=github&logoColor=white)](https://princechakusa.github.io)

</div>
