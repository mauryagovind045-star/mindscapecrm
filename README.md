# Mindscape CRM

A personal CRM for tracking leads — a single HTML file, no build step, no server.

**Features**

- Kanban pipeline: New → Contacted → Qualified → Won / Lost, with drag and drop
- Contact details (email, phone, source, deal value) and a timestamped notes log per lead
- Follow-up dates with a "Today" ribbon that surfaces overdue and due-today leads
- Search by name/company, filter by source
- Export to CSV, backup/restore via JSON

**Data**

All data is stored in your browser's localStorage — nothing leaves your machine. Use **Data → Export JSON backup** regularly; importing a backup merges leads without duplicating them.

**Run it**

Open `index.html` in a browser, or visit the GitHub Pages URL for this repo.
