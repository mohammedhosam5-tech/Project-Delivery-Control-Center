# Project Delivery Control Center

A browser-based workspace for planning, tracking, and reviewing
project delivery across multiple projects.

Keep project timelines, milestones, tasks, risks, and issues
organized in one place.

## Features

- Dashboard with delivery indicators and project summaries.
- Multiple project management.
- Project timeline visualization.
- Milestone tracking.
- Task ownership, priorities, due dates, and completion tracking.
- Risk and issue management.
- Calendar view.
- Reports with print and copy options.
- Saved views.
- Audit trail.
- Configurable statuses, phases, owners, and customers.
- Light and dark themes.

## Import and Export

- Import tasks and milestones from CSV files.
- Export tasks, milestones, risks, and issues as CSV.
- Export the audit trail as CSV.
- Download and restore full JSON backups.

CSV imports append records. Review your data before importing
to avoid duplicates.

The CSV importer supports simple comma-separated data.
Avoid embedded commas and line breaks within field values.

## Getting Started

1. Select Code → Download ZIP.
2. Extract the downloaded ZIP file.
3. Open index.html in a modern browser.
4. Configure owners, customers, statuses, and phases
   under Administration.
5. Create a project.
6. Add milestones, tasks, risks, and issues.
7. Review progress through the dashboard, timeline, and reports.

Use Data Management → Load Demo Data to explore a sample project.

No installation or application server is required.

## Example Use Cases

- Track delivery across several customer projects.
- Monitor upcoming milestones and overdue tasks.
- Maintain project risk and issue registers.
- Prepare project progress reviews.
- Organize ownership and follow-up actions.

## Data Storage

Project data and settings are saved in browser local storage.

Data is specific to your browser, browser profile, and
application location. It does not automatically synchronize
between users or devices.

Keep the application in a stable location and use the same
browser to access existing data.

This is a local tracking application. It does not provide
shared multi-user editing or authenticated user accounts.

## Backup and Restore

Open Data Management to export a full JSON backup.

Backups include projects, milestones, tasks, risks, audit
history, configuration, and saved views.

Restoring a backup replaces the current project datasets.
Export your current data before restoring another backup.

Export backups regularly and before updating or moving
the application. Clearing browser data can remove saved records.

GitHub preserves the application source code, not the project
records stored in your browser.

## Privacy and Connectivity

Project records are processed and stored locally.
The application does not include a backend for uploading
or synchronizing project data.

Google Fonts are requested for typography when available.
Core functionality uses local HTML, CSS, and JavaScript,
with fallback fonts available offline.

## Technology

- HTML
- CSS
- JavaScript
- Browser local storage
- Google Fonts for typography

## Updates

Export a full backup before updating.

Replace index.html with the latest application version
and use a descriptive commit message to document the change.
