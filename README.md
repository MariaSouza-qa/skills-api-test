🔪 skills-api-test 

This repository contains automated API tests using Postman and Newman. It is part of my learning process and practice as a Junior QA, where I'm developing and organizing a set of tests for real-world APIs, focusing on quality, clarity, and safe version control.

📌 About the project

This project simulates a real API testing scenario for a skills classification API, using Postman, Newman, automation scripts, folder organization, and secure Git/GitHub practices.

I focus on:

Creating well-structured Postman collections and environments

Writing tests to validate response status, content, and structure

Automating execution with .bat scripts

Generating HTML reports with Newman

Organizing the repo clearly and safely for public portfolio use

🧠 What I'm practicing

This project is also my learning space. I'm practicing and improving on:

✅ Test organization by scope and folders

✅ Use of variables and environments in Postman

✅ Basic JavaScript assertions in the Tests tab

✅ Execution via Newman CLI

✅ Automatic report generation

⚙️ Git versioning and .gitignore safety

🚧 Currently learning more about automation, CI/CD, and test documentation.

📂 Project structure

skills-api-test/
├── collections/        → Postman collections (sanitized for GitHub)
├── environments/       → Postman environments without secrets
├── scripts/            → Batch script to run tests via Newman
├── reports/            → Automatically generated HTML reports
├── docs/               → Future documentation (in progress)
├── .gitignore          → Tracks ignored/sensitive files
└── README.md           → You are here! :)

▶️ Running the tests locally

Requirements

Postman

Newman installed via Node.js

Clone this repo:

git clone https://github.com/MariaSouza-qa/skills-api-test.git

Steps

Open your terminal in the repo folder

Run the script:

scripts\runtest.bat

The report will be saved to reports\newman-report.html

📊 Report example



