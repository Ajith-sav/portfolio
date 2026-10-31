# Ajith Elumalai — Portfolio & Dynamic Resume System Guide

A complete documentation and owner's manual for the interactive portfolio website and single-source-of-truth ATS Resume Engine engineered for **Ajith Elumalai** (*Software Engineer | IT Analyst | Python Full Stack & Applied AI Developer*).

---

## 1. Secret Owner-Only Admin Page Shortcuts

To ensure recruiters and visitors only see your polished public portfolio and **Download Resume** buttons, the **Admin CMS** and **Preview CV Studio** are completely hidden from the public interface.

You can open your private Admin Login Gate at any time using **any of these 4 secret methods**:

| Method | Best For | Action / Shortcut |
| :--- | :--- | :--- |
| **1. Keyboard Shortcut** | Desktop / Laptop | Press **`Ctrl + Shift + A`** (Windows/Linux) or **`Cmd + Shift + A`** (Mac) anywhere on the page. |
| **2. Secret Logo Tap** | Mobile / Tablet / Desktop | Click or tap the top-left **`AE` logo 5 times rapidly** (within 2.5 seconds). |
| **3. Direct URL Hash** | Any Device / Bookmark | Add **`#admin`** or **`#cms`** to the end of your website URL (e.g., `https://ajith-portfolio.netlify.app/#admin`). |
| **4. Live CLI Command** | Interactive Terminal | Scroll to the **Interactive Recruiter Console** (`ajith@dev:~$`), type **`sudo admin`** or **`owner`**, and press `Enter`. |

### Default Owner Passcode
* **Secret Passcode:** `2026`
* *Note:* You can change this passcode at any time inside **Module 7 (Export & Security PIN)** of the Admin CMS.

---

## 2. Core Features Built Into the System

### A. Public Recruiter Landing Experience
1. **Interactive Telematics Particle Network Canvas**:
   * Custom HTML5 2D canvas background rendering a smooth, low-CPU connected-node telemetry network with ambient emerald, cyan, and indigo mesh glows.
2. **Public "Download Resume (PDF)" Action**:
   * Recruiters see clean **Download Resume (PDF)** buttons in the navbar, hero section, system verification card, experience header, contact section, and footer.
   * Clicking the button immediately downloads `Ajith_E_Resume_2026.pdf` without cluttering the public UI with editor controls.
3. **Interactive Project Filtering**:
   * Visitors can filter your 6 flagship enterprise systems across **All Systems**, **AI & Automation**, **Telematics & Real-Time**, and **Security & Enterprise**.
4. **Academic Foundation & Early AI Research**:
   * Showcases your **B.E. in Computer Science Engineering** (*SKP Engineering College, Tiruvannamalai — Class of 2023, CGPA: 8.0 / 10*) alongside dedicated cards for your two college capstone projects:
     * **Brain Tumor Detection using MRI Scan Report** (*Python, CNN, OpenCV, MRI Segmentation*)
     * **Car Resale Value Prediction** (*Python, Scikit-Learn, Pandas, Supervised Regression*)
5. **Interactive Recruiter CLI Terminal (`AjithOS v2026.3.0`)**:
   * Allows technical recruiters and engineering managers to query your profile using clickable chips or typed commands:
     * `resume` — Triggers an instant download of `Ajith_E_Resume_2026.pdf`
     * `skills` — Lists your full-stack, SQL/NoSQL, caching, AWS, and AI stack
     * `projects` — Summarizes your 6 deployed production platforms
     * `education` — Displays your B.E. CSE degree and both college capstone projects
     * `hire` — Outputs an executive summary of your 3+ years of impact
     * `contact` — Displays your location, email, and phone/WhatsApp number
     * `clear` — Clears the terminal screen
6. **Smart Multi-Channel Interview Email Launcher**:
   * Solves the common problem where standard `mailto:` links fail on computers without a configured default mail app.
   * Gives recruiters 5 instant ways to contact you with a pre-filled interview invitation:
     1. **Open in Gmail (Web)** (`mail.google.com`)
     2. **Open in Outlook / Office 365 Web** (`outlook.office.com`)
     3. **Launch Default OS Mail App** (with automatic clipboard backup)
     4. **Send via WhatsApp Direct** (`+91 9080946720`)
     5. **One-Click Copy Full Email + Subject + Message**

---

### B. Private Owner Admin CMS & Dynamic Resume Studio
Once unlocked via your secret shortcut and passcode, your private Admin CMS provides **7 dedicated modules**:

1. **Module 1 — Profile, Contact & Hero Metrics**:
   * Edit your full name, target role headline, location, phone/WhatsApp, email address, hero status badge, current role card title, 4 key metric counters (`3+ Yrs`, `99%`, `6+`, `8.0`), and professional summary.
2. **Module 2 — Technical Skills CRUD**:
   * Add new skill categories, update comma-separated skills, or remove outdated categories.
3. **Module 3 — Work Experience CRUD**:
   * Edit your roles at **Switch Mobility EV**, **GI Scripts**, and **Trillion Thoughts Technologies**, or click **Add New Role / Company** when you get promoted or switch companies in the future.
4. **Module 4 — Production Projects Manager CRUD**:
   * Add new projects, change filter categories (`ai`, `telematics`, `security`), update tech stacks, and edit achievement bullet points.
5. **Module 5 — Education & Academic Capstones CRUD**:
   * Update degree details, graduation year, CGPA, and manage your college capstone projects.
6. **Module 6 — Preview CV & Dynamic PDF Studio**:
   * **Preview CV (A4 Sheet)**: Opens the interactive A4 Resume Studio where you can inspect the exact layout of your resume, switch between **Role-Tailored Presets** (*Full Stack & Telematics*, *Applied AI & FastAPI Focus*, *React.js & Frontend Focus*), or toggle whether your college capstone projects appear on the PDF.
   * **Dual PDF Engine**:
     * **Mode A (Default — Auto-Generated Vector PDF)**: Uses the `jsPDF` vector engine to build a multi-page, ATS-readable `Ajith_E_Resume_2026.pdf` directly from your live Admin data.
     * **Mode B (Custom Uploaded PDF Override)**: Lets you upload any custom `.pdf` file from your computer so all public **Download Resume** buttons serve that exact file.
7. **Module 7 — Permanent Export & Security PIN**:
   * **Export Updated `index.html`**: Downloads a brand-new, single-file `index.html` with all of your latest Admin edits permanently baked into the source code.
   * **Backup / Restore (`.JSON`)**: Export or import a lightweight JSON backup of your entire portfolio state.
   * **Change Secret Owner Passcode**: Update your login PIN from `2026` to any custom passcode.

---

## 3. How to Update Your Portfolio & Resume in the Future

Whenever you want to add a new project, update your skills, or upload a new resume on your live hosted site:

1. Open your live portfolio website and press **`Ctrl + Shift + A`** (or tap the **`AE` logo 5 times** on mobile).
2. Enter your passcode (`2026`) and click **Verify & Unlock Admin**.
3. Make your updates in **Modules 1–6** and click **Save & Apply All Live**.
4. Click **Preview CV (A4 Sheet)** or **Download Updated PDF** in the top bar to verify how your new resume looks.
5. Open **Module 7 (Export & Security PIN)** and click **1. Export Updated `index.html`**.
6. Drag and drop that newly downloaded `index.html` file into your **Netlify**, **Vercel**, or **GitHub Pages** project to publish your updates worldwide in seconds.

---

## 4. Free Hosting Quick-Reference

### Option 1: Netlify Drop (Fastest — 30 Seconds)
1. Place your `index.html` file inside a folder named `ajith-portfolio`.
2. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
3. Drag and drop the `ajith-portfolio` folder into the browser window.
4. Your site is immediately live with free HTTPS. You can rename the subdomain under **Site Configuration → Change site name** (e.g., `https://ajith-elumalai.netlify.app`).

### Option 2: GitHub Pages
1. Create a public repository on GitHub (e.g., `portfolio`).
2. Upload `index.html` to the root of the repository and commit.
3. Go to **Settings → Pages**, select the `main` branch and `/ (root)` folder, and click **Save**.
4. Your portfolio will be live at `https://<your-github-username>.github.io/portfolio/`.