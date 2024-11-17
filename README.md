MailWave - Smart Email Campaign Manager
MailWave is an advanced email-sending application designed to simplify email campaign management. Built with Django, Celery, and WebSocket technologies, it provides customizable email templates, real-time tracking, scheduling, and seamless integration with ESPs like SendGrid.

Features
Data Integration:

Import email recipient data via Google Sheets or CSV files.
Auto-detect columns for placeholders in email templates.
Email Customization:

Use dynamic templates powered by an LLM for personalized emails.
Placeholders such as {Company Name} or {Location} are replaced with real data.
Email Scheduling and Throttling:

Schedule emails at specific times or stagger them.
Throttle sending rates to stay within provider limits.
ESP Integration:

SendGrid integration for email delivery, tracking, and analytics.
Support for other ESPs (e.g., Amazon SES, Mailgun).
Real-Time Analytics:

Track email statuses like Sent, Delivered, Bounced, or Opened.
View campaign progress in an interactive dashboard.
WebSocket Updates:

Live updates on email statuses via WebSocket connections.
Tech Stack
Frontend: HTML, CSS, JavaScript (WebSocket.js for live updates)
Backend: Django, Django Channels, Celery
Database: PostgreSQL
Email Services: SendGrid API
Task Scheduling: Celery with Redis as the message broker

Usage

Navigate to the dashboard at http://localhost:8000/.
Upload a CSV or connect to Google Sheets for data input.
Customize your email template with placeholders.
Schedule or send your emails in real-time.
Monitor email statuses and analytics on the dashboard.

Contributions

Contributions are welcome! Please open an issue or submit a pull request for bug fixes, new features, or improvements.
