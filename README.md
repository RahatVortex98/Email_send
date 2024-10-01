# Email_send
Python Email Sender with HTML Template


This Python script sends an HTML email using Gmail's SMTP server. It allows customization of the email content through a template.

Features
Sends an email using Gmail’s SMTP server.
Customizes the email content using an HTML template.
Secures the connection using TLS encryption.
Prerequisites
Python 3.x: Ensure Python is installed on your system.
smtplib: Standard Python library for sending emails.
email.message.EmailMessage: For creating email message objects.
string.Template: To use placeholders in your email templates.
pathlib.Path: For file handling and reading HTML files.
Gmail Account: A Gmail account with either:
Less secure apps enabled.
App-specific password (if using 2-factor authentication).
Setup Instructions
Install Python: Download Python from python.org if not installed.

Set Up Gmail:

Enable Less Secure Apps for your Gmail account.
Or generate an App-Specific Password if using 2-factor authentication.