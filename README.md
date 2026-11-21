# SpendWise — Personal Finance Dashboard

## Project Description
SpendWise is a responsive personal finance web application built with HTML5, CSS Grid/Flexbox, and vanilla JavaScript. Users can set a monthly budget, log categorized expenses across six core cards (Rent, Food, Transport, Utilities, Entertainment, and Savings), monitor category limits and budget health alerts, and view real-time balance calculations.

## Technologies Used
- **HTML5** for semantic dashboard structure and forms
- **CSS3** (CSS Custom Properties, CSS Grid, Flexbox, `@media` queries, and `prefers-color-scheme: dark`)
- **JavaScript (ES6+)** for state arrays, loops, conditional budget evaluation, event listeners, and DOM rendering
- **Git & GitHub** for version control and source hosting
- **Netlify** for continuous deployment and static web hosting

## GitHub Repository Information
- **Repository:** `https://github.com/<your-github-username>/<your-repo-name>`
- **Branch:** `main`

## Live Netlify Website URL
- **Live Site:** `https://<your-custom-site-name>.netlify.app`

## Deployment Process Summary
1. Organized `index.html`, `style.css`, `script.js`, and `README.md` in the project root using relative asset paths.
2. Initialized Git locally, committed the project files, and pushed them to a public GitHub repository.
3. Connected the GitHub repository to Netlify, deployed the site with root publish settings, and renamed the Netlify subdomain to a clear project name.
4. Pushed a visible update to GitHub and verified that Netlify automatically triggered a new build and updated the live site.

## Challenges Encountered During Deployment
- **[Describe any real issue you hit, e.g., case-sensitive file paths on Linux servers, waiting for initial DNS/subdomain propagation, or forgetting to include the live URL before a final push.]**

## Lessons Learned
- Connecting a Git repository to Netlify enables automatic continuous deployment whenever changes are pushed to the tracked branch.
- Testing on the live hosted URL (including browser DevTools console/network checks and responsive viewport resizing) catches environment or path issues that may not appear when opening files locally.
