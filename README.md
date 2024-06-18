# URL Phishing Attack Awareness Project

## Introduction
Phishing attacks exploit user trust to steal sensitive information by mimicking legitimate websites. This project demonstrates the mechanics of phishing by creating a realistic clone of the Instagram login page. The goal is to raise awareness about the risks of entering credentials on suspicious websites and to highlight the importance of cybersecurity measures.

## Features
- **Website Mimicry**: A replica of the Instagram login page using HTML and CSS.
- **User Data Capture**: JavaScript captures the entered credentials (username and password).
- **Discord Webhook Integration**: Credentials are sent to a specified Discord channel using a webhook.
- **User Redirection**: After capturing credentials, users are redirected to the legitimate Instagram website.
- **Realistic Loading Delay**: A custom JavaScript sleep function adds a 400ms delay to mimic real login page behavior.

## Project Objectives
- Educate users on the dangers of phishing attacks.
- Demonstrate the techniques used by cybercriminals to create convincing phishing websites.
- Highlight the importance of user awareness and proactive cybersecurity measures.

## Technologies Used
- **HTML**: For creating the structure of the phishing page.
- **CSS**: For styling the page to look identical to the Instagram login.
- **JavaScript**: For capturing user credentials and sending them to a Discord channel.
- **Discord Webhook**: For receiving captured credentials.
- **Web Server**: To host the phishing page locally for testing.

## Getting Started
### Prerequisites
- A modern web browser (Google Chrome, Mozilla Firefox, etc.)
- A text editor or IDE (Visual Studio Code, Sublime Text, etc.)
- A web server (Apache, Nginx, or Node.js)
