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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Google Calendar Sync](https://calendar.google.com/)**  
  Google's native calendar service with two-way sync across Android, iOS, web, and third-party apps; supports shared calendars, appointment scheduling pages, and Google Meet integration for virtual meetings.

- **[Microsoft Outlook Sync](https://www.microsoft.com/en-us/microsoft-365/outlook/)**  
  Microsoft's calendar and email client with Exchange ActiveSync, Microsoft 365 calendar sharing, Teams meeting integration, and booking pages via Microsoft Bookings for customer-facing scheduling.

- **[Calendly](https://calendly.com/)**  
  Scheduling automation platform that eliminates back-and-forth emails; integrates with Google, Microsoft Teams, Outlook, Zoom, Stripe, PayPal, HubSpot, Salesforce, and more. Paid tiers add team scheduling, routing, and SSO.

- **[Chili Piper](https://www.chilipiper.com/)**  
  Buyer-centric meeting scheduling for revenue teams; instant booking from web forms, routing to the right rep based on territory or round-robin rules, and CRM-native handoff for sales and marketing qualified leads.

- **[Cron](https://cron.com/)** (now Notion Calendar)  
  Calendar app designed for speed and keyboard-driven navigation, with multi-account support, time zone handling, and integration with Notion for meeting-linked notes.

- **[YouCanBookMe](https://youcanbook.me/)**  
  Customizable booking pages with buffer times, intake forms, team routing, and payment collection; integrates with Google Calendar, Outlook, and major video conferencing tools.

- **[Acuity Scheduling](https://acuityscheduling.com/)**  
  Appointment scheduling platform for service businesses with client self-booking, automated reminders, intake forms, package/subscription sales, and integration with Squarespace and Stripe.

- **[Doodle](https://doodle.com/)**  
  Group meeting poll tool for finding times that work across multiple participants without requiring account creation for voters; supports calendar integration for automatic availability detection.

- **[Cirrus Insight](https://www.cirrusinsight.com/)**  
  Sales productivity platform with calendar scheduling, email tracking, and CRM sync (Salesforce, HubSpot); enables meeting booking from within email and automatic activity logging.

- **[Freshworks Calendar Sync](https://www.freshworks.com/)**  
  Calendar synchronization within the Freshworks CRM ecosystem, connecting sales activities and meetings with Google Calendar and Outlook for unified customer timelines.

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
