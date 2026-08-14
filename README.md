# Mindscape CRM

A real-estate lead CRM for Mindscape Properties (Goa) — a single HTML file, no build step, no server. Live at https://mauryagovind045-star.github.io/mindscapecrm/ and installable on a phone as an app.

**Built for the daily calling workflow**

- Work queues: **Due** (follow-ups due today or overdue), **To Contact** (new leads never called), and All Leads
- One-tap **WhatsApp** with a prefilled intro message built from the lead's enquiry (config, property type, location, budget) and **Call**
- Inline tracking on every card: status (New → Contacted → Follow-Up → Site Visit Scheduled/Done → Negotiation → Closed Won/Lost, Not Reachable, Junk), outcome, urgency, last called, next follow-up
- Quick-set chips: Called today, +3d / +1w / +1mo follow-up
- Rental vs Sale with Indian budget formatting (₹/month, ₹ Lac, ₹ Cr), BHK config, property type, location and Goa zone
- Dashboard: due/to-contact/scheduled/won tiles, pipeline-by-status and leads-by-zone charts
- Google Calendar button on every follow-up date

**Data**

Leads live in localStorage and sync to a **private** GitHub repo (`leads.json`) via a fine-grained token — every device with the token stays in sync, merging by newest edit with deletion tombstones. Data menu offers CSV export, JSON backup/restore, and importers for the old standalone CRM HTML file and its tracking backups.
