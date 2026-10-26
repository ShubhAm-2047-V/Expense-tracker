# ExpenseTracker Website

A responsive browser-based ExpenseTracker prototype based on the uploaded 34-page industrial training report.

## Included features
- Overview dashboard with balance, monthly income/expenses and savings rate
- Add, edit and delete income/expense entries
- Categories: Food, Travel, Shopping, Necessities, Entertainment and Other
- Search and date-range filters, pagination and CSV export
- Category spending breakdown for 7 days, 30 days and 12 months
- Weekly and monthly summaries with overspending warnings
- Profile settings for profession, opening savings and monthly income target
- Responsive desktop and mobile layouts
- Demo login/register screen

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser. No build step is needed.
3. Use the sample data, or clear/edit it in the app.

## Important limitations
This is a **front-end demo**, not a production financial service. It stores data in this browser's `localStorage`; it does not include Django, a server database, real account authentication, password reset email, or server-side access controls. The login screen is only a demo flow and must not be used to protect real financial data. To match the report's intended architecture for real deployment, connect a Django backend, use Django authentication and validated forms, enforce per-user ownership checks, enable CSRF protection and login throttling, and deploy with production settings and backups.

The report describes Django + Python, HTML/CSS/Bootstrap and SQLite, with account/profile management, transaction ledger, charts, weekly/monthly summaries and security improvements. This prototype implements the main user-facing workflows with plain HTML/CSS/JavaScript to make the ZIP easy to run locally.
