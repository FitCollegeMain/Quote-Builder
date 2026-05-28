# FIT College Interactive Quote Generator

This is a browser-based quoting tool built for the FIT College sales team. It allows Career Advisers to dynamically construct quotes, apply percentage or dollar-value discounts, manage bundled package inclusions, and generate clean, branded PDFs to attach to student emails. 

## Features
- **Dynamic Calculation:** Automatically calculates savings and final prices.
- **Auto-Fill Pricing:** Select a course product and the RRP automatically populates.
- **Elite Package Inclusions:** Selecting a FIT Elite package (including Fit Elite Ultra) automatically builds the 5 included online skillset courses at a locked $0.00 price point.
- **Campus & Timetable Selection:** Selecting an On-Campus (F2F) pathway reveals drop-down menus to select the specific FIT College Campus location, exact start date, and study timetable (Full-Time or Part-Time).
- **Secondary Pathways:** Allows reps to build multiple pathway options on a single quote (e.g. comparing Face-to-Face vs. Online pricing). 
- **PIN Protected Output:** Requires a 4-digit PIN (`1234`) before the user is allowed to initiate the PDF generation. 
- **Smart Naming:** Automatically titles the output PDF as `Fit College Quote [Student Name] [Date] by [Adviser First Name]`.

## How to Deploy via GitHub Pages
1. Push this code to the `main` branch of your repository. 
2. Go to your repository **Settings**.
3. In the left sidebar, click on **Pages**.
4. Under "Build and deployment", set the **Source** to `Deploy from a branch`.
5. Under "Branch", select your `main` branch and click **Save**.
6. GitHub will provide you with a live URL (e.g., `https://[your-username].github.io/[repo-name]/`). Share this URL with your sales team!
