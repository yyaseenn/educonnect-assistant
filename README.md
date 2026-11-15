# EduConnect Student Assistant (CSIT205 prototype)

A working prototype of a student-support chatbot for **EduConnect**, the case company in our CSIT205 Generative AI Assignment 2 (University of Wollongong in Dubai, Autumn 2026).

**Live site:** https://yyaseenn.github.io/educonnect-assistant/

## What it does
- Ranked search (BM25) over 8 sample guides (29 sections): timetables, enrolment changes, learning platform, IT account, library, exams, fees, student services.
- Scope and privacy gate: grades, appeals, complaints and wellbeing questions skip the bot and go to staff; student IDs, emails and phone numbers are stripped from questions.
- Every answer shows its source guide, section, owner and review date.
- If nothing relevant is found, it says so instead of guessing.
- A side panel shows each pipeline step for every question.

On this website the assistant runs in **search mode**: answers are the matching guide text with its source.

## Important
- All guides are **fictional sample content** made for the demo. They are not real EduConnect or UOWD policy.
- Not connected to any real systems (no SharePoint, Zendesk or student records).
- Built with Claude (Anthropic) for the CSIT205 group project.
