# Royvil Domingo — Developer Portfolio

A responsive, dark-mode developer portfolio built with semantic HTML5, Tailwind CSS, and vanilla JavaScript. It presents selected software projects, technical skills, academic work, education details, and contact information in a single-page layout.

> **Before publishing:** Replace every personal-information placeholder and verify all education, certification, organization, and event details. Do not publish unverified credentials or experience as confirmed facts.

## Preview

Open `index.html` in a modern web browser. An internet connection is required for the Tailwind CSS CDN and Google Fonts used by the page.

## Features

- Responsive layout for desktop, tablet, and mobile screens.
- Dark interface with subtle visual effects and scroll animations.
- About section and grouped technical skills.
- Project filtering for web applications and research work.
- Interactive project case-study dialogs.
- Education, certification, and activity timeline.
- Contact form with browser-side validation and `mailto:` message preparation.
- Mobile navigation and reduced-motion support.
- No application server, framework build process, or database required to preview the portfolio.

## Built With

- **HTML5** for page structure and semantic content.
- **Tailwind CSS** via CDN for utility-based styling.
- **Vanilla JavaScript** for navigation, project filters, case-study dialogs, scroll effects, and contact-form behavior.
- **Google Fonts** for Inter and DM Mono typography.

## Featured Work

### 1. Dialysis Center Management System

A Laravel-based management platform intended to centralize routine dialysis-center workflows.

**Remembered features include:**
- Patient records and patient lookup.
- Appointment scheduling and management.
- Treatment records linked to patients.
- Charges and billing records.
- Reports and dashboard summaries.
- Notifications and activity logging.
- Role-based access and user management.
- FAQ-first chatbot with AI fallback using OpenRouter free models.

**Technology:** Laravel 12, PHP, MySQL/MariaDB, Blade, JavaScript, CSS, and Vite.

### 2. Flask Library / Equipment Borrowing System

A borrower-oriented web application for managing equipment availability, borrowing requests, and administrator approval.

**Remembered features include:**
- Borrower registration and login.
- Equipment catalog and quantity tracking.
- Borrowing request records.
- Administrator approval workflow.
- Quantity-aware borrowing rules.

**Technology:** Python, Flask, HTML, CSS, SQL, and SQLite.

### 3. Technology and Academic Performance Study

A school research project examining the impact of technology on the academic performance of aspiring engineering students at Saint John School, Makapilapil, San Ildefonso, Bulacan. The working study involved Grade 12 students and survey-based data collection.

**Methods and tools discussed:** Google Forms, descriptive statistics, normality testing, and group-comparison procedures.

> Update the research description, sample details, statistical methods, and findings to match the final submitted paper before publishing them.

## Skills Presented

The portfolio groups the technologies and subjects discussed or used in projects and coursework. The list does not claim independently assessed proficiency levels.

- **Frontend:** HTML5, CSS3, JavaScript, Blade, responsive layouts, Tailwind CSS, and Bootstrap (coursework).
- **Backend:** PHP, Laravel 12, Python, Flask, MVC structure, CRUD operations, validation, and role-based access.
- **Databases:** MySQL, MariaDB, SQLite, SQL queries, and relational data modeling.
- **Systems and tools:** Git/GitHub, Vite, XAMPP, Windows, command line, and local development/deployment workflows.
- **Networking:** IPv4 addressing, subnetting, VLSM, FLSM, subnet masks, and LAN fundamentals.
- **Security and quality:** Security fundamentals, threat-analysis concepts, software testing, input validation, and access control.
- **Programming fundamentals:** C++, Python fundamentals, linked lists, queues, searching, sorting, and introductory digital-logic exercises.

## Run Locally

No installation is needed for a basic preview.

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html`, or open it in your browser.

For a local development server, you may use the VS Code Live Server extension or run this command from the project folder if Python is installed:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Personalization Checklist

Search `index.html` for the following placeholders and replace them with accurate details:

| Placeholder | What to add |
|---|---|
| `[INSERT_EMAIL]` | Professional contact email |
| `[INSERT_GITHUB_URL]` | GitHub profile URL |
| `[INSERT_LINKEDIN_URL]` | LinkedIn profile URL |
| `[INSERT_PROGRAM]` | Exact degree or academic program |
| `[INSERT_START_YEAR–EXPECTED_GRADUATION]` | Actual education dates |
| `[INSERT_CREDENTIAL_URL]` | Official certificate verification URL, if applicable |
| `[INSERT_COMPLETION_DATE]` | Verified certificate completion date |
| `[INSERT_ROLE_AND_DATES]` | Confirmed organization role and participation dates |
| `[INSERT_EVENT_NAME]` | Exact hackathon name |
| `[INSERT_YEAR_AND_RESULT]` | Verified event year, role, and result |
| `[INSERT_LIVE_DEMO_URL]` | Public project demo URL, when available |

Also update the project repository/demo placeholders inside the case-study dialogs when the corresponding links exist.

### Contact form configuration

The contact form does not send messages through a backend. It validates the form in the browser and opens the visitor's default email application with a prepared message.

In `index.html`, find this JavaScript constant:

```js
const CONTACT_EMAIL = '[INSERT_EMAIL]';
```

Replace the placeholder with the email address where you want to receive inquiries. The visible contact details in the footer should be updated as well.

## Deploy

This is a static website and can be hosted by services such as GitHub Pages, Netlify, or Vercel.

### GitHub Pages

1. Create a GitHub repository for the portfolio.
2. Add `index.html` and `README.md` to the repository's root directory.
3. Commit and push the files to GitHub.
4. Open the repository's **Settings → Pages**.
5. Under the build and deployment settings, select **Deploy from a branch**.
6. Choose the branch containing the portfolio (commonly `main`) and the `/ (root)` folder, then save.
7. Open the published URL shown in the Pages settings.

### Vercel or Netlify

Import the GitHub repository and configure it as a static site. Because the entry page is in the repository root, use the root directory and do not specify a framework build command or a `dist` output folder. Follow the hosting provider's current deployment prompts.

## Notes and Limitations

- Tailwind CSS is loaded from its CDN for easy setup. For a larger production site, consider a local Tailwind build so CSS can be optimized and pinned to a controlled version.
- Google Fonts and the Tailwind CDN require internet access. System fonts remain as fallbacks if the font service is unavailable.
- The contact form uses `mailto:` and depends on the visitor having an email application configured. It does not store submissions or send mail directly from the website.
- Project repository URLs, demo URLs, and personal profile links should be added only after they are verified and publicly accessible.
- Confirm all school, certificate, organization, and event information before making the portfolio public.

## Suggested Repository Structure

```text
royvil-portfolio/
├── index.html
└── README.md
```

## License

Add a license file if you intend to let other people reuse, modify, or redistribute this portfolio's code. Otherwise, no reuse license is specified by this README.

---

**Maintainer:** Royvil Domingo  
**Portfolio:** Add the deployed URL here after publishing.
