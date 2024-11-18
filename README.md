# custom-email-sender
The source code is archived in the rar file that satisfies your requirements
Custom Email Sender Application
Project Overview
The Custom Email Sender Application is a versatile and robust web application designed to simplify the process of managing and sending personalized bulk emails. It integrates cutting-edge machine learning techniques and seamless API connections, enabling institutions and businesses to achieve efficient email communication while tracking real-time analytics.

The application features an intuitive dashboard, allowing users to connect their email accounts, customize email content using AI, schedule and throttle email delivery, and monitor performance with real-time insights and tracking.

Key Features
1. Data Input and Connection
Allows users to upload CSV files or link Google Sheets to import email recipient data dynamically.
Auto-detection of columns for seamless placeholder integration into email templates.
2. Email Integration
Supports both personal accounts (Gmail, Outlook) and ESPs (e.g., SendGrid, Amazon SES, Mailgun).
Secure account connection using OAuth2 and configurable SMTP or API integration.
3. AI-Driven Customization
Incorporates a customizable prompt box where placeholders (e.g., {Name}, {Company}) are dynamically replaced with data from uploaded files.
Uses LLM (Language Learning Models) APIs to generate personalized email content for each recipient.
4. Scheduling and Throttling
Enables users to schedule emails for specific times or intervals, ensuring flexibility in delivery.
Implements throttling options to respect provider limits (e.g., X emails per hour).
5. Real-Time Analytics and Tracking
Provides a comprehensive dashboard displaying:
Total emails sent, pending, failed, and scheduled.
Delivery statuses like "Delivered," "Opened," "Bounced."
Real-time progress indicators and insights into recipient engagement metrics.
6. Email Delivery Tracking
Integrates with major ESPs to track delivery events such as opened, clicked, or bounced emails.
Real-time updates on delivery statuses through webhooks or polling mechanisms.
Technologies Used
Backend
Python (Flask): Backend framework for handling APIs and logic.
SQLAlchemy: ORM for database management.
Celery + Redis: Scheduling and throttling services.
Integration with ESPs: SendGrid API and Amazon SES for email delivery and tracking.
Frontend
React.js: For building a dynamic and user-friendly interface.
Axios: For communicating with backend APIs.
WebSocket: Real-time updates on analytics and email statuses.
Database
PostgreSQL: To store email logs, schedules, and tracking data.
Project Architecture
The application follows a modular architecture to ensure scalability and maintainability.

Frontend: React.js-based dynamic dashboard.
Backend: Flask-powered REST APIs managing email services and data processing.
Database: Centralized storage for logs, metrics, and configurations.
Third-party Integrations: APIs for AI-generated content (e.g., GPT-based LLMs), ESPs, and OAuth2 authentication.
How It Works
Upload Recipient Data:
Users upload a CSV or connect Google Sheets containing recipient information.

Customize Emails:
Through an intuitive prompt box, users define email content with dynamic placeholders.

Schedule and Send:
The app schedules and sends personalized emails, ensuring delivery rates are optimized through throttling.

Track Performance:
A real-time dashboard tracks delivery and engagement metrics (e.g., opened, clicked).

Setup Instructions
Refer to the docs/setup-instructions.md for detailed steps on:

Installing and configuring the project.
Setting up APIs and environment variables.
Running the application locally or using Docker.
Use Cases
Marketing Campaigns: Send targeted and personalized email campaigns to a large audience.
Institutional Communication: Streamline email communications for announcements, promotions, or updates.
Automated Follow-ups: Efficiently manage follow-ups with real-time tracking.
Why This Project Stands Out
AI-Powered Personalization: Makes each email feel tailored, increasing engagement rates.
User-Centric Design: A straightforward and intuitive interface prioritizing user needs.
Scalability: Robust architecture supports small-scale to enterprise-level email campaigns.
Reliability: Ensures compliance with email provider limits and handles errors gracefully.
About the Developer
This project was developed as part of an internship assessment, showcasing skills in:

Backend development (Flask, Celery, Redis).
Frontend development (React.js, Axios).
API integrations (LLMs, ESPs, OAuth2).
Database management (PostgreSQL).
Deployment (Docker).
I am eager to contribute my technical skills and problem-solving abilities to projects requiring a balance of innovation and functionality.
