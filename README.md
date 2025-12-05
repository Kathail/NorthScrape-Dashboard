NorthScrape Leads Dashboard

A lightweight, single-file browser application for managing sales leads, planning canvassing routes, and organizing cold calling lists.

No server required. Just open the file in your browser.

🚀 Features

Zero Setup: Runs entirely in the browser using a single HTML file.

Offline Capable: Data is processed locally. No data is sent to external servers (except when you click to open Google Maps).

Persistent Session: Your leads, notes, and contact status are saved automatically to your browser's local storage, so you can refresh or close the tab without losing progress.

Smart Routing: Select multiple leads to generate an optimized multi-stop route in Google Maps.

Lead Management:

Mark leads as "Contacted" to fade them out.

Add custom notes to specific leads.

Filter by "Phones Only" or "Pending Leads".

Utilities:

One-click PDF Export.

"Copy All Phones" button for bulk dialing.

Dark Mode support.

📦 Installation & Usage

Download the index.html file.

Open the file in any modern web browser (Chrome, Edge, Firefox, Safari).

Drag and drop your CSV file onto the upload zone, or click "Load Demo Data" to test the interface.

📊 CSV Format Requirements

To import your own leads, your .csv file must contain a header row with at least a "Name" column.

Recommended columns:

Name (Required)

Address (Highly Recommended for routing)

Phone (Optional - auto-formatted by the dashboard)

Example CSV:

Name,Address,Phone
"Joe's Plumbing","123 Main St, Sudbury, ON","555-0199"
"Sudbury Electric","456 Elm St, Sudbury, ON","555-0123"


🛠️ Technology Stack

Core: HTML5, JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

Icons: Lucide Icons

Libraries:

PapaParse: Fast CSV parsing.

jsPDF & jspdf-autotable: PDF generation.

🔒 Data Privacy Note

This application is Client-Side Only.

Your CSV data is parsed directly in your browser memory.

Lead data, notes, and status are stored in your browser's localStorage.

Clearing your browser cache or clicking "Clear Data" in the app will remove this data permanently.

⌨️ Keyboard Shortcuts

Key

Action

/

Focus Search Bar

Esc

Clear Search / Close Modals

Generated for NorthScrape Leads Dashboard
