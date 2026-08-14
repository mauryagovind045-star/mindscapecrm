# Mindscape CRM

A personal CRM for tracking leads — a single HTML file, no build step, no server.

**Features**

- Kanban pipeline: New → Contacted → Qualified → Won / Lost, with drag and drop
- Contact details (email, phone, source, deal value) and a timestamped notes log per lead
- Follow-up dates with a "Today" ribbon that surfaces overdue and due-today leads
- Search by name/company, filter by source
- Export to CSV, backup/restore via JSON

**Data**

All data is stored in your browser's localStorage. Use **Data → Export JSON backup** regularly; importing a backup merges leads without duplicating them.

**Sync across devices**

The **Sync** button connects the app to a private GitHub repository (e.g. `mindscape-data`), where leads are stored as `leads.json`. Every device configured with the same repo and token stays in sync — changes push automatically a couple of seconds after each edit, and merge by newest-edit-wins with deletion tombstones.

Setup on each device: create a fine-grained personal access token at github.com/settings/personal-access-tokens/new with access to only the data repo and **Contents: Read and write** permission, then paste it into Sync settings. Keep the data repo private — it holds your leads.

**Run it**

Open `index.html` in a browser, or visit the GitHub Pages URL for this repo.
