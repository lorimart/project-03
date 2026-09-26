# Project Plan: The Mana Potion Lounge Website

## 1. Work Breakdown Structure (WBS)

The project schedule is broken down into four major phases leading up to the final submission deadline on Thursday, October 1, 2026.

### Phase 1: Planning & Documentation (Target: Sept 24)

* **Task 1.1:** Draft Project Scope Statement (docs/final-project-scope.md)
* **Task 1.2:** Draft Project Plan & Risk Analysis (docs/plan.md)
* **Task 1.3:** Initialize GitHub Repository with README.md

### Phase 2: Core Development (Target: Sept 27)

* **Task 2.1:** Code index.html structure with semantic HTML5
* **Task 2.2:** Code about.html structure and mock reservation form
* **Task 2.3:** Link style.css and implement global "Gamer Noir" variables

### Phase 3: Visual Polish & Responsive Design (Target: Sept 29)

* **Task 3.1:** Apply Flexbox layout to navigation and Grid layout to homepage features
* **Task 3.2:** Validate internal cross-page navigation links

### Phase 4: Deployment & Review (Target: Oct 1, 11:59 PM)

* **Task 4.1:** Deploy site live using GitHub Pages
* **Task 4.2:** Complete post-project process reflection (docs/retrospective.md)

## 2. TAME Risk Analysis

### Risk 1: Scope Creep (Going Beyond Minimum Requirements)
* **Threat:** Getting distracted trying to add complex features (like user login systems, real-time booking calendars, or advanced animations) that exceed the baseline project assignment requirements.
* **Analysis:** High likelihood as a solo developer trying to build a polished portfolio piece, which wastes valuable time and risks missing the core deadline. High impact.
* **TAME Strategy:** Eliminate
* **Actionable Response Plan:** Enforce strict boundaries established in Section 4 of the scope. Eliminate the possibility of writing complex interactive scripts by keeping the form as a frontend-only visual mockup. Regularly audit progress against the rubric to keep the code basic.

### Risk 2: Poor Time Management
* **Threat:** Procrastinating on building the layout files or drafting the final project reflection papers, leading to a rushed, low-quality submission right at the deadline due to competing coursework.
* **Analysis:** Medium likelihood given standard university workloads across different courses. Fatal impact on the final grade if the deadline is missed.
* **TAME Strategy:** Accept
* **Actionable Response Plan:** Accept that heavy course schedules are an inevitable risk. Handle this reality by creating a timeline buffer into the project schedule. Enforce a strict internal code-freeze by midnight on Tuesday, September 29, leaving the final 48 hours exclusively for code checking and validation.

### Risk 3: Website Layout or Function Failure
* **Threat:** The design layout breaking on mobile devices, navigation links resulting in 404 errors, or the external stylesheet failing to load properly once deployed to GitHub Pages.
* **Analysis:** High likelihood because pathing rules behave differently on local machines compared to active production web servers. High impact.
* **TAME Strategy** Mitigate
* **Actionable Response Plan:** Mitigate this by keeping all project file paths strictly relative. Code all links using plain relative syntax (`href="about.html"`) and enforce a strict lower-case naming rule across all files to prevent server case-sensitivity errors. Continuously push adjustments to GitHub Pages early to check for errors live.
