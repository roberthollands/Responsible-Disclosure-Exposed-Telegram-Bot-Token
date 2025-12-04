# Responsible-Disclosure-Exposed-Telegram-Bot-Token

Documenting a responsible disclosure to a managed service provider after discovering their public website exposed a Telegram bot API token in client-side JavaScript. 
The token was used in a contact form submission flow; an attacker could intercept or abuse API calls to access or replay sensitive lead data such as names, emails, phone numbers, and requested services. 
There are several programs that offer this. One such program is seen here https://github.com/0x6rss/matkap.
This repo outlines the finding and impact. 
