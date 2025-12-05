# NorthScrape Dashboard

**NorthScrape Dashboard** is a lightweight, single-file browser application for managing sales leads, planning canvassing routes, and organizing cold calling lists.

It leverages **HTML5**, **JavaScript (ES6+)**, and **Tailwind CSS** for a responsive interface, with client-side processing to ensure data privacy and offline capability.

Live Demo: https://kathail.github.io/NorthScrape-Dashboard/

## Features

- **Offline Lead Management** — Load, search, filter, and edit leads entirely in-browser using localStorage for persistence  
- **Smart Routing** — Select multiple leads to generate optimized multi-stop routes via Google Maps integration  
- **Data Enrichment Utilities**  
  - One-click dialing with auto-formatted phone numbers  
  - Persistent notes and status tracking (e.g., "Contacted")  
  - Bulk actions like copy phones or export to PDF  
- **Quality of Life**  
  - Dark mode toggle  
  - Keyboard shortcuts (e.g., `/` for search, `Esc` to clear)  
  - Drag-and-drop CSV import with demo data option  
- **Privacy-Focused** — No server required; all data stays local—no transmission to external services  

## Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/Kathail/NorthScrape-Dashboard.git
   cd NorthScrape-Dashboard

   No dependencies needed—it's a single index.html file.

## Usage

- Open index.html in any modern browser (Chrome, Firefox, Edge, Safari)
- Load Data: Drag-and-drop a CSV file or click "Load Demo Data"
- Manage Leads: Search/filter, add notes, mark statuses, or select leads for routing
- Export: Use built-in PDF export or copy bulk data

## CSV Format

- Column Header,Description
- Name,Business/contact name (required)
- Address,Full street address (required for mapping)
- Phone,Contact number (auto-formatted on load)

## Configuration

- Google Maps API (optional): Add your API key in the script section for routing
- Dark Mode: Automatically follows system preference or use the toggle

## Tech Stack

- HTML5 + JavaScript (ES6+)
- Tailwind CSS (CDN)
- Lucide Icons
- PapaParse (CSV parsing)
- jsPDF (PDF export)


## Disclaimer
- This tool is for personal/educational use. Ensure compliance with applicable data privacy laws (e.g., PIPEDA, GDPR) when handling leads.

## Privacy Notice
- 100% client-side: All data is processed and stored in your browser's localStorage. Nothing is sent to any server.

## About
- NorthScrape Dashboard is the companion tool to NorthScrape, providing a simple, private way to manage and action enriched leads after scraping.

## Resources

- Live Demo → https://kathail.github.io/NorthScrape-Dashboard/
- Original Scraper → https://github.com/Kathail/NorthScrape

## License
- MIT License — see LICENSE for details.



