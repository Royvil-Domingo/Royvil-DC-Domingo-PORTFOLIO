# Royvil Domingo — Developer Portfolio

A responsive developer portfolio (light and dark, following the visitor's system setting) built with plain HTML, CSS, and vanilla JavaScript. It shows my projects, skills, school background, and contact details on a single page.

> **Before publishing:** Replace every personal-information placeholder and verify all education, certification, organization, and event details. Do not publish unverified credentials or experience as confirmed facts.

## Preview

Open `index.html` in a modern web browser. An internet connection is needed for Google Fonts and GSAP. If offline, system fonts take over and the page simply shows without animations.

## Features

- Responsive layout that works on phones, tablets, and desktops.
- Light and dark themes with a toggle in the header. It follows the visitor's system setting at first and remembers their choice afterwards.
- Projects are listed from one array in the script, so adding a project is a single entry.
- Filters (web apps, algorithms, research and writing) and a details dialog for each project.
- Contact form that validates in the browser and opens your email app with the message ready.
- Page-load, scroll, and button animations powered by GSAP. They switch off automatically for visitors who prefer reduced motion.
- No build step, framework, or server.

## Built With

- **HTML5, CSS3, and vanilla JavaScript.**
- **GSAP 3.12.5 and ScrollTrigger** from cdnjs, for animation.
- **Google Fonts**: Bricolage Grotesque and Instrument Sans.

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

### 3. VHK Construction Supply: Inventory, Sales and Cash Flow System

A group project (five members) for IT 225: a web system that monitors stock, sales, and cash flow for a construction supply business. Course rules ruled out frameworks, so it uses plain PHP, HTML, CSS, and MySQL, with vanilla JavaScript for form validation. Scope includes login, dashboard, and products and categories CRUD.

### 4. Memory and CPU Scheduling Simulators

Platform Technologies work in Python, C++, and Java: best-fit and worst-fit memory allocation, plus SJF, SRTF, Round Robin, and Multi-Level Queue scheduling with Gantt chart output.

### 5. Technology and Academic Performance Study

A school research project examining the impact of technology on the academic performance of aspiring engineering students at Saint John School, Makapilapil, San Ildefonso, Bulacan. The working study involved Grade 12 students and survey-based data collection.

**Methods and tools discussed:** Google Forms, descriptive statistics, normality testing, and group-comparison procedures.

> Update the research description, sample details, statistical methods, and findings to match the final submitted paper before publishing them.

### Writing and video

- Two scripts for the SSP101 film contest ("Lead like the Babaylans, Filipinas!"): *Huwag Kang Matakot* and *Hilom ng Lahi*.
- A 2-minute promotional video for the Institute of Computer Studies at BASC (group project).

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

Placeholders now live in three places: the `CONTACT_EMAIL`, `GITHUB_URL`, and `LINKEDIN_URL` constants at the top of the script, plus a few HTML comments in the School section. Links stay hidden until you replace the constants. Fill these in:

| Placeholder | What to add |
|---|---|
| `[INSERT_EMAIL]` | Professional contact email |
| `[INSERT_GITHUB_URL]` | GitHub profile URL |
| `[INSERT_LINKEDIN_URL]` | LinkedIn profile URL |
| School years | Add your exact years where the TODO comment is in the School section |
| Certificate, organization, hackathon | Currently commented out in the School section. Uncomment each only after you can verify it |

To add repository or demo links, extend the project entries in the `P` array.

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

- Google Fonts needs internet access. System fonts are the fallback.
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