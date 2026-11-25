# EMS — Employment Management System

A responsive, lightweight employment-management website built with HTML, CSS and vanilla JavaScript. No build step or backend required for the demo.

## Features
- Overview dashboard and employee statistics
- Add, edit, search and delete employee records
- Daily attendance marking
- Leave requests and approve/decline actions
- Basic salary overview and CSV export
- Reports and CSV export
- Local browser storage (localStorage)

## Deploy to Netlify

### Drag-and-drop
1. Unzip this folder.
2. Open https://app.netlify.com/drop
3. Drag the `ems-netlify` folder (containing `index.html`, `styles.css` and `app.js`) onto the page.
4. Netlify publishes the static website and provides a URL.

### Git deployment
1. Upload this folder to a GitHub repository.
2. In Netlify choose **Add new site → Import an existing project** and connect the repo.
3. Leave the build command empty and set publish directory to `.` (the root containing `index.html`).

## Demo data and limitations
The demo stores data in the current browser's localStorage. It does not have user authentication, a shared database, server-side authorization, or real payroll calculations. Data entered in one browser/device does not automatically sync with other users. For production, add authentication, database and server-side security.
