Real-Time Event Notifier API
This project provides a real-time event notification system that allows users to manage events like meetings, deadlines, or reminders. Users can receive notifications 5 minutes before the event and check historical logs of completed events.

Features
Event Management: Create events with a title, description, and scheduled time.
Real-Time Notifications:
Notify users 5 minutes before an event starts using WebSockets.
Detect and notify users about overlapping events.
Historical Logs: Save completed events asynchronously to a file (completed_events.log) for future reference.
Technologies Used
Node.js: Backend framework.
Express.js: REST API creation.
WebSocket (ws): Real-time communication.
Node-Cron: Event scheduling and notifications.
File System (fs): Logging completed events.
