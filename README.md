This is a Python script that scrapes job listings from TimesJobs, filtering them based on your skills and preferred job titles.

🔍 What It Does
Takes input from you: your skills and job titles you're interested in.

Scrapes job postings from TimesJobs using your input as keywords.

Filters the results to only show jobs that match your criteria.

Displays:

Job title

Company name

Required skills

Salary (if available)

Date posted

Link to apply

Adds a timestamp to each result to show when it was fetched.

🛠️ Tech Stack
Python 3

requests – for sending HTTP requests

BeautifulSoup (bs4) – for parsing HTML

time and datetime – for delays and timestamps

✅ How to Use
Clone this repository or copy the script.

Run the script with Python:

bash
Copy
Edit
python job_scraper.py
Enter your skills and job titles when prompted.

Get a list of relevant job postings right in your terminal.

📌 Example
java
Copy
Edit
Put your skills (comma-separated):
< python, sql

Put job titles (comma-separated):
< data analyst, developer






