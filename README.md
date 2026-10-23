# MIS MCQ Practice

A static, mobile-friendly MCQ practice website built from the uploaded NPTEL Management Information Systems Weeks 1–12 PDF.

## Features
- 12 weekly practice sets with 10 questions each (120 total)
- Option to practise all 120 questions in one round
- Questions and answer choices shuffle each time a set starts or is retried
- Immediate feedback: correct answers turn green; a wrong selected answer turns red and the correct answer is shown in green
- Score and completion screen
- No backend, database, API keys, or build step

## Run locally
Open `index.html` in a browser.

## Deploy to Vercel
1. Create a new GitHub repository and upload `index.html` (and this README if you want).
2. In Vercel, choose **Add New → Project** and import that repository.
3. For a plain static site, no framework or build command is needed. Set the output directory to `.` if prompted.
4. Deploy. The website can be opened from the Vercel URL on a phone.

## Content note
Question text, options, and correct answers were extracted from the provided PDF. The PDF does not provide explanations, so the site shows the correct answer but does not invent explanations.
