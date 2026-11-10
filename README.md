# Awesome-Calendar-Synchronization-Scheduling

## Top Calendar Synchronization & Scheduling Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on CalDAV Sync, Appointment Booking & Meeting Poll Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Calendar Synchronization & Scheduling**. These tools help individuals and teams connect calendars across providers, eliminate booking friction, and automate meeting coordination—covering CalDAV/CardDAV servers, self-hosted booking pages, and group polling tools.

**Examples** include Google Calendar Sync, Microsoft Outlook Sync, Calendly, Chili Piper, Cron, YouCanBookMe, Acuity Scheduling, Doodle, Cirrus Insight, and Freshworks Calendar Sync (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted CalDAV servers, open-source Calendly alternatives, and Doodle-style polling tools—ideal for privacy-conscious users, system administrators, and teams seeking full control over their scheduling data without vendor lock-in.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global appointment scheduling and calendar synchronization software market is valued at approximately $0.6B–$1.5B (scaling beyond $3.5B+ when including broader workforce/field scheduling) and is expanding at a CAGR of 10%–14%. The sector exhibits moderate-to-high fragmentation: while core enterprise email/calendar infrastructure is dominated by tech giants (Microsoft and Google), the booking and synchronization layer remains highly distributed across hundreds of point solutions and specialized vertical tools with no single winner-take-all monopoly.

## SaaS/Hosted Platforms

| Company / Product | Company Size (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Outlook Sync](https://www.microsoft.com/en-us/microsoft-365/outlook/)** | ~$3.1T Market Cap (~$245B ARR / Revenue) | $6.00/user/month (Microsoft 365 Business Basic, annual commitment) | Free forever personal account via Outlook.com (free web/mobile app, 15 GB mailbox storage, 5 GB OneDrive cloud storage; Microsoft Bookings & custom domains require paid 365 license) | Microsoft's enterprise calendar & email client with Exchange ActiveSync, Microsoft 365 shared calendars, Teams integration, and customer-facing scheduling pages via Microsoft Bookings. |
| **[Google Calendar Sync](https://calendar.google.com/)** | ~$2.1T Market Cap (~$350B Revenue) | $6.00/user/month (Google Workspace Business Starter, annual commitment) | Free forever personal Google account (includes 15 GB shared Google Drive/Gmail storage, unlimited events/calendars, basic single booking page; multi-appointment schedules & payment collection require Workspace) | Native calendar service with two-way sync across Android, iOS, web, and third-party apps; supports shared team calendars, appointment booking slots, and Google Meet integration. |
| **[Cron (now Notion Calendar)](https://cron.com/)** | ~$11B Valuation (~$600M ARR) | $10.00/seat/month (Notion Plus plan, billed annually) | Free forever standalone calendar app (connects multiple Google Calendars, unlimited 1:1 scheduling links; workspace database limits follow Notion Free plan: unlimited blocks for solo users, 1,000 blocks cap for teams of 2+ members, 5 MB file upload limit) | Keyboard-driven calendar application designed for speed, multi-account overlay, global time zone coordination, and bidirectional sync with Notion databases. |
| **[Freshworks Calendar Sync](https://www.freshworks.com/)** | ~$3.5B Market Cap (~$965M ARR) | $9.00/user/month (Freshsales Growth tier, billed annually) | Free forever plan for up to 3 users (includes 2-way Google Calendar and Outlook/Microsoft 365 sync, contact management, capped at 1,000 API requests/hour; 21-day full-feature trial for paid tiers) | Unified CRM calendar integration linking sales and service pipelines directly to Google and Microsoft Outlook schedules for automated activity logging. |
| **[Calendly](https://calendly.com/)** | ~$3.0B Valuation (~$350M ARR) | $10.00/seat/month (Standard tier, billed annually) | Free forever plan: 1 user, 1 connected calendar account, 1 active event type rule, unlimited 1-on-1 bookings, basic automated notifications (no automated SMS, group/round-robin events, or payment gateways; 14-day free trial of Teams tier) | Category-leading scheduling automation platform eliminating back-and-forth emails; automates routing, multi-person availability, and cross-platform integrations. |
| **[Acuity Scheduling](https://acuityscheduling.com/)** | Subsidiary of Squarespace (Acquired for ~$100M+; Squarespace taken private at ~$7.2B) | $16.00/month (Starter tier, billed annually) | No free forever plan; 7-day free trial (extended to 14 days when bundled with a Squarespace website trial; includes 1 calendar and full scheduling features without requiring a credit card) | Appointment scheduling platform optimized for service businesses, client self-scheduling, intake questionnaires, recurring memberships/subscriptions, and payment processing. |
| **[Chili Piper](https://www.chilipiper.com/)** | ~$625M Valuation (~$45M–$50M ARR) | $15.00/user/month (ChiliCal Standalone, billed annually; Growth tier starts at $15,000/year base) | No free forever plan and no public self-serve free trial; access requires a live enterprise sales demo and annual contract agreement | Inbound conversion and routing scheduling software for B2B revenue teams; features automated instant booking directly from web forms and round-robin CRM assignment. |
| **[Cirrus Insight](https://www.cirrusinsight.com/)** | ~$15M–$25M Estimated Valuation (~$8M–$12M ARR; Private Equity owned) | $11.00/user/month (Salesforce Sidebar & Calendar Sync module, billed annually) | No free forever plan; 14-day free trial with full access to sidebar CRM tracking, calendar sync, and email sequence testing | Sales enablement and calendar sync platform natively integrating Microsoft 365 and Google Calendar with Salesforce and CRM records. |
| **[Doodle](https://doodle.com/)** | Subsidiary of TX Group (~$1.1B Market Cap; Doodle standalone ARR ~$15M–$25M) | $6.95/user/month (Pro tier, billed annually) | Free forever plan: 1 user, 1 active group poll, 1 booking page, 1 sign-up sheet, ad-supported interface (no custom branding, automated reminders, or calendar-sync detection; 14-day Pro free trial) | Popular group meeting poll and consensus scheduling tool enabling participants to vote on ideal time windows across different calendars without an account. |
| **[YouCanBookMe](https://youcanbook.me/)** | ~$15M–$25M Estimated Valuation (Bootstrapped, ~$5M ARR) | $9.00/month (Individual tier, billed annually) | Free forever plan: 1 calendar connection, 1 booking page, capped at 30 bookings per month, includes YouCanBookMe branding (14-day unlimited free trial of paid features) | Intuitive booking system with buffer times, configurable question forms, time zone conversion, and video conferencing sync. |

## Open-Source GitHub Projects

- **[Radicale](https://github.com/Kozea/Radicale)**  
  Simple CalDAV (calendar) and CardDAV (contacts) server with extremely low administrative overhead; stores data as plain files on disk, works out-of-the-box with Evolution, Lightning, iPhone, and Android clients. GPL-3.0 licensed with ~5.2k GitHub stars and active development [citation:1].

- **[Baïkal](https://github.com/sabre-io/Baikal)**  
  Lightweight CalDAV and CardDAV server based on sabre/dav, providing a web admin interface for managing users and calendars; ~3.4k GitHub stars under GPL-3.0 [citation:1].

- **[Xandikos](https://github.com/jelmer/xandikos)**  
  Open-source CardDAV and CalDAV server with minimal administrative overhead, backed by a Git repository for versioned storage; GPL-3.0 licensed with ~613 stars [citation:1].

- **[Davis](https://github.com/tchapi/davis)**  
  Simple, Dockerizable admin interface for sabre/dav built on Symfony and Bootstrap, inspired by Baïkal; provides a clean web UI for managing CalDAV/CardDAV resources [citation:1].

- **[Keeper.sh](https://github.com/keeper-sh/keeper)**  
  Calendar syncing tool that pulls and pushes events between calendar sources and destinations via iCal/ICS or OAuth, with support for anonymized busy/free events; AGPL-3.0 licensed [citation:1].

- **[Tymeslot](https://github.com/Tymeslot/tymeslot)**  
  Open-source meeting scheduling platform built with Elixir/Phoenix LiveView; supports Google, Apple iCloud, Nextcloud, Radicale, and Zimbra calendar sync, video meeting creation (Google Meet, Teams, Jitsi, Nextcloud Talk), Stripe payments, and multi-language booking pages [citation:10].

- **[Rallly](https://github.com/lukevella/rallly)**  
  Open-source Doodle alternative for group meeting polls; participants vote on proposed dates without creating accounts. Built with Next.js, Prisma, and tRPC; supports SSO, ICS calendar attachments, and self-hosting via Docker with PostgreSQL and MinIO [citation:11].

- **[nexcal](https://github.com/ribato22/nexcal)**  
  Self-hosted Calendly alternative for service businesses with Google Calendar sync, anti-double-booking guarantees, patient self-service portal, WhatsApp notifications, and Stripe/Midtrans payment integration; built with Next.js 16 and PostgreSQL [citation:3].

### Additional Strong Open-Source Options

- **[jawanndenn](https://github.com/hartwork/jawanndenn)** — Self-hosted Doodle alternative for simple group polls with Docker deployment and JSON backup/restore .
- **[Nextcloud Calendar](https://github.com/nextcloud/calendar)** — Full-featured calendar app for Nextcloud with CalDAV backend, attendee invitations, free/busy visibility, appointment booking pages, and integration with Contacts, Talk, and Tasks [citation:7].
- **[DavMail](https://github.com/mguessan/davmail)** — POP/IMAP/SMTP/CalDAV/CardDAV/LDAP gateway enabling any calendar client to work with Exchange servers, even behind firewalls [citation:1].
- **[potatotime](https://pypi.org/project/potatotime/)** — Python library for synchronizing events between Google, Outlook, and iCal calendars programmatically [citation:5].
- **Musubi** — Open-source shared calendar with two-way sync for Google Calendar, Apple iCloud, Outlook, and CalDAV, with web, Android, and self-hosted options [citation:8].

**Frameworks for building custom systems**: Combine **Radicale** or **Baïkal** for CalDAV storage, **Tymeslot** or **Rallly** for booking and polling interfaces, and **Nextcloud Calendar** for a full groupware experience—all deployable via Docker Compose for complete data sovereignty.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Calendar and scheduling tools handle personal and business availability data; ensure compliance with applicable privacy regulations (GDPR, CCPA) and organizational policies.
- Self-hosted CalDAV servers require proper TLS configuration, authentication, and backup strategies; booking tools integrated with external calendars should be reviewed for OAuth scope minimality.

---

**Made for privacy-conscious users, system administrators, sales teams, and developers building scheduling infrastructure.**  
Let's make calendar sync and scheduling more open, interoperable, and user-controlled.
