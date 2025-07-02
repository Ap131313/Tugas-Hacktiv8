# Tugas-Hacktiv8

Daily Mood Tracker

Description
Daily Mood Tracker is a clean, responsive web app that allows users to log, edit, and review their daily moods and personal notes. Built as a frontend-only solution with local storage, it is ideal for lightweight emotional self-reflection.

Technologies Used
- HTML5, CSS3 (Responsive with mobile-first approach)
- JavaScript (Vanilla)
- LocalStorage (to simulate persistent data)
- Google Fonts (Inter)
- Optional: Can be enhanced using AI via IBM Granite prompts

Features
- Log daily mood with emoji + note
- Edit or delete individual entries
- Confirmation modal before delete
- Fully responsive design for mobile and desktop
- LocalStorage-based persistence

Setup Instructions
1. **Clone or download** the repository.
2. **Open `index.html`** in any modern web browser.
3. **No backend required** — everything runs client-side.

To Deploy on Netlify:
- Drag and drop the `index.html` into Netlify Drop: https://app.netlify.com/drop
- OR connect your GitHub repo and select this project folder.

Prompting Strategy via IBM Granite 

You are a frontend developer assistant.
Your task is to generate a complete HTML/CSS/JavaScript codebase for a responsive web app called **Daily Mood Tracker**.

Requirements:
- Input form with:
  - Dropdown for mood (😊 Happy, 😐 Neutral, 😢 Sad, 😠 Angry, 😰 Anxious, 😴 Tired)
  - Textarea for optional notes
- Two tabs:
  - Log Mood (form input)
  - Mood History (display all previous entries)
- Use localStorage to store and persist mood entries
- Full CRUD:
  - Create: Submit form to save entry
  - Read: View entries in "Mood History"
  - Update: Edit entry, prefill form, resubmit
  - Delete: Show custom confirmation modal before deletion
- Responsive UI (mobile-first):
  - Use flexbox/grid layouts, media queries
  - Avoid elements overflowing on small screens
- Good UX:
  - Highlight active tab
  - Reset form after submit
  - Custom modal dialog for delete confirmation
  - Buttons for ✏️ Edit and ❌ Delete per entry

Example (for reference, do NOT copy):
A contact manager app with:
- Tabs: "Add Contact", "Contact List"
- localStorage data
- Modal confirmation before delete
- Edit form support

Use vanilla HTML, CSS, and JavaScript only.
Do not use external frameworks or libraries.

Output only the complete working HTML file.
