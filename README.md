# EduTrack — Student Learning Hub

A polished responsive frontend prototype for a Student Learning Management System, built with HTML, CSS, and vanilla JavaScript.

## Run
Open `index.html` in a modern browser, or open this folder in VS Code and use Live Server.

## Included
- Responsive sign-in and sign-up screens with input validation and password visibility toggle
- Demo-account entry point and sign-out flow to preview the dashboard without a server
- Dashboard with learning metrics, course cards, weekly agenda, activity chart and announcements
- Course listing/filtering and sample progress interactions
- Weekly schedule and study reminder dialog
- Searchable learning-resource library with links to public documentation
- Progress overview, achievements, help centre and student profile dialog
- Responsive mobile sidebar, keyboard focus styling, and reduced-motion support

## Scope and limitations
This is a frontend-only academic project prototype. All student, course, schedule and progress information is sample content. There is no backend, database, real authentication, secure credential handling, server-side persistence, school integration or real notification service. The sign-in/sign-up screens are demonstration-only: they validate form fields in the browser but do not create real accounts or verify passwords. Do not enter a real password or sensitive personal information. The progress interactions are demonstration behaviour and do not save to a server.

## Suggested next steps
1. Build a backend and database (for example, Node.js/Express and PostgreSQL or MySQL) if real accounts are required.
2. Add server-side authentication, password hashing, sessions, email verification and password reset before using real student data.
3. Test the sign-in, sign-up and dashboard flows on mobile, tablet and desktop.
1. Confirm requirements with the supervisor and replace sample content with approved content.
2. Test in desktop and mobile browsers and capture genuine screenshots for the SIWES report.
3. Add backend/API/database only if required by the project scope.
4. Implement authentication securely on a server; do not rely on frontend-only login for real student data.
