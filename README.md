# Interview-AI
Interview AI is an intelligent scheduling bot that automates the process of arranging interviews between recruiters and candidates. It parses natural language input (e.g., "next Monday 2pm"), checks recruiter availability via Google Calendar, and creates events with Google Meet links. Built with Python, it leverages NLP (spaCy, NLTK) and the Google Calendar API for seamless scheduling.

# Features
Natural Language Parsing: Understands inputs like "Monday 2pm", "next Wednesday afternoon", or "tomorrow 10am".
Availability Checking: Queries the recruiter’s Google Calendar to confirm free slots within work hours (9 AM–4 PM IST).
Event Creation: Schedules interviews with custom reminders and Google Meet links.
Time Zone Support: Handles IST (Asia/Kolkata) and converts to UTC for Google Calendar.
Modular Design: Reusable functions for parsing, slot checking, and event management.

# Prerequisites

Python: 3.8 or higher
Google Cloud Project: With Calendar API enabled and OAuth credentials downloaded
Dependencies:
google-api-python-client
google-auth-oauthlib
spacy
nltk
python-dateutil
pytz
python -m spacy download en_core_web_sm
from nltk nltk.download('punkt')

# Configuration

Time Zone: Set to IST (Asia/Kolkata) via pytz.
Work Hours: 9 AM–4 PM IST (adjustable via st and end_st).
Recruiter Email: Define rec_mail (e.g., "recruiter@example.com") in the script.


# Contributing

Fork the repository.
Create a feature branch (git checkout -b feature/new-feature).
Commit changes (git commit -m "Add new feature").
Push to the branch (git push origin feature/new-feature).
Open a Pull Request.

# Future Improvements

Support for minute-level precision in time parsing.
Multi-recruiter scheduling.
Interactive CLI or GUI interface.
Integration with email or Slack for notifications.

# Contact :
jasmakhija1234@gmail.com
