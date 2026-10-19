# AZ-900 Study Planner (Unofficial)

A simple, offline-friendly web tool that turns your exam date, daily study hours and weak areas into a day-by-day study plan for the Microsoft Azure Fundamentals (AZ-900) exam.

> **Unofficial.** This project is not affiliated with or endorsed by Microsoft. Topics follow the public AZ-900 skills outline on Microsoft Learn. No real exam questions are used.

Built for the **#1MillionDevs Vibe Coding Hackathon: AZ-900 Exam Prep Edition** (Planning challenge: Personal Study Planner).

## The problem
Many learners don't know how to split their study time before an exam date, so they either cram or skip the topics they find hard.

## What it does
- Takes your **exam date**, **hours available per day**, and **weak areas**
- Covers 12 topics across the three AZ-900 domains: Cloud Concepts, Azure Architecture and Services, and Azure Management and Governance
- Gives **extra time to weak areas** (1.6x weighting)
- Reserves the **last day before the exam for revision**
- Shows a **countdown**, total study hours, and a **progress bar**
- Lets you **tick off each day**; progress is saved in your browser
- Can be **printed or saved as PDF**

## How the plan is calculated
1. Work out the days left until the exam (the last study day is kept for revision).
2. Total study time = study days x hours per day.
3. Each topic gets a weight based on its share of the AZ-900 skills outline; topics marked as weak get 1.6x.
4. Time is shared out in proportion to the weights and filled into the days in order.

## How to use it
1. Open the live demo: **[add your GitHub Pages link here]**
2. Pick your exam date and daily hours.
3. Tick your weak areas.
4. Click **Build my plan** and follow it day by day.

Or download `index.html` and open it in any browser. No install and no internet needed.

## Tech
Plain HTML, CSS and JavaScript in a single file. No frameworks, no backend. Built with AI-assisted "vibe coding" using Claude for prompt engineering and building support.

## Future ideas
- Add a Flashcard Coach and Readiness Tracker so the planner links to practice scores
- Support other Microsoft fundamentals exams (AI-900, SC-900, etc.)
- Add reminders and a Swahili interface

## Author
Keisha Akinyi Ochieng

## Disclaimer
Always check the latest skills outline on Microsoft Learn before your exam.
