# Faculty-Consultation-log
The Faculty Consultation Log is a digital record-keeping system designed to track, document, and manage academic advising sessions between faculty members and students. It streamlines the documentation process, ensuring clear communication and continuity in student mentorship.

Git Hub description
Copy-paste this as your GitHub repo description:
📋 An elegant academic ledger for logging, tracking & visualizing student–faculty consultations — featuring live statistics, distribution charts, search & filters, CRUD operations, print-ready reports, and JSON export/import. Built with vanilla HTML, CSS & JavaScript.
Topics / Tags to add:

consultation-log student-faculty academic-tool vanilla-javascript crud-app localstorage single-page-app university education ledger data-visualization

✨ Features
📊 Live Dashboard Sidebar
Real-time statistics — Total records, Pending, Completed, and This Week counts update instantly
Purpose breakdown chart — Horizontal bar visualization showing distribution across advising categories (Academic Advising, Thesis/Project Guidance, Grade Concerns, Career Guidance, Personal Concern, Other)
📝 Full CRUD Operations
Log new consultations via a slide-in drawer panel with form validation
Edit existing records — pre-populated form for quick updates
Delete records with a confirmation modal to prevent accidental data loss
View record details in a dedicated modal with all consultation information
🔍 Advanced Search & Filtering
Full-text search across student name, student ID, faculty name, purpose, department, and notes
Multi-filter dropdowns — filter by Faculty, Status (Pending / Completed / Cancelled), and Purpose simultaneously
Active filters banner with a one-click "Clear all filters" option
Dynamic record count showing filtered vs. total entries
💾 Data Persistence & Portability
Auto-save to LocalStorage — data persists across browser sessions without any server
Export to JSON — download all consultation records as a structured .json backup file
Import from JSON — restore records from a previously exported backup file
Reset to sample data — one-click restore to built-in demo records
🖨️ Print-Ready Reports
Dedicated print stylesheet — hides sidebar, toolbar, and action buttons for clean, formal department reports
Produces a professional table layout suitable for submission or archival
🎨 Premium Academic Design
Parchment-inspired color palette — warm, scholarly aesthetic with gold accents
Typography system — Fraunces (serif headings), Inter (sans body), JetBrains Mono (IDs/code)
Editable header fields — click to customize Department Name and Academic Term directly in the UI
Status badges with color-coded indicators (Pending = amber, Completed = green, Cancelled = red)
Toast notifications for user feedback on all actions
Smooth micro-animations — slide-in panels, modal scale transitions, toast entrance effects
📱 Responsive Design
Fully responsive layout from desktop (1600px) down to mobile (< 640px)
Sidebar collapses to horizontal layout on tablets
Form and modals adapt to smaller screens
♿ Accessibility
Semantic HTML5 with proper ARIA attributes (role="dialog", aria-modal, aria-label)
Keyboard navigation support (Escape key closes all dialogs)
Screen-reader friendly labels on all interactive elements
🛠️ Tech Stack
Layer	Technology
Structure	HTML5 (Semantic)
Styling	Vanilla CSS (Custom Properties / CSS Variables)
Logic	Vanilla JavaScript (ES6)
Fonts	Google Fonts (Fraunces, Inter, JetBrains Mono)
Storage	Browser LocalStorage
Icons	Inline SVG (Feather-style)
Zero dependencies. No frameworks, no build tools, no npm packages. Just open index.html in any modern browser.

🚀 Getting Started
Quick Start
Clone the repository

git clone https://github.com/<your-username>/faculty-consultation-log.git
cd faculty-consultation-log
Open in browser

# Simply open the file — no server required
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
Start logging consultations!

Click "Log Consultation" to add a new record
Use the search bar and filter dropdowns to find specific entries
Export your data anytime with the "Export" button
Using a Local Server (Optional)
If you prefer serving over HTTP:

# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .

# Then visit http://localhost:8000
📂 Project Structure
faculty-consultation-log/
├── index.html          # Single-file application (HTML + CSS + JS)
└── README.md           # Project documentation
📖 Usage Guide
Adding a Consultation Record
Click the "Log Consultation" button (gold button in the header)
Fill in the required fields: Date, Time, Student Name, and Faculty Name
Optionally add Student ID, Year & Section, Department, Purpose, Status, and Notes
Click "Save Entry"
Editing a Record
Click the pencil icon (✏️) in the Actions column of any row
Modify the pre-filled form fields
Click "Save Entry" to update
Viewing Record Details
Click the eye icon (👁️) in the Actions column
A modal displays all fields including the full discussion notes
Deleting a Record
Click the trash icon (🗑️) in the Actions column
Confirm deletion in the modal dialog
Exporting & Importing Data
Export: Click "Export" in the header → downloads a .json file
Import: Click "Import" → select a previously exported .json file
Customizing the Header
Click on "Department of Computer Studies" or "A.Y. 2026–2027 (1st Semester)" in the header to edit them inline
🎓 Educational Context
This project was designed as a first-year computer science student project that demonstrates:

✅ Arrays of Objects (data modeling)
✅ DOM Manipulation (reading/writing HTML)
✅ Functions & Event Listeners (user interactions)
✅ CRUD Operations (Create, Read, Update, Delete)
✅ Filtering & Searching through data
✅ LocalStorage (client-side persistence)
✅ Form validation with error feedback
✅ Responsive CSS layout techniques
✅ Accessible UI patterns (ARIA, keyboard nav)
🤝 Contributing
Contributions are welcome! Here are some ideas for improvements:

 Dark mode toggle
 CSV export option
 Date range filtering
 Sorting by column headers (click to sort)
 Pagination for large datasets
 Chart.js integration for richer visualizations
 PDF report generation
Fork the repository
Create your feature branch (git checkout -b feature/dark-mode)
Commit your changes (git commit -m 'Add dark mode toggle')
Push to the branch (git push origin feature/dark-mode)
Open a Pull Request
📄 License
This project is open source and available under the MIT License.

🙏 Acknowledgements
Google Fonts — Fraunces, Inter, JetBrains Mono
Feather Icons — SVG icon inspiration
Built with ❤️ for the academic community
Faculty Consultation Log · An Academic Ledger for Student–Faculty Consultations
