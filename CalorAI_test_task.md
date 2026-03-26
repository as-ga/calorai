# CalorAI test task

## Important: AI Tools Are Required
We heavily encourage and **require** the use of AI tools when generating code. This includes GitHub Copilot, Claude, ChatGPT, Cursor, or any other AI coding assistants.
We value:
*   Speed of implementation
*   Quality of the final product
*   Your ability to leverage modern tools effectively
We do **not** value you writing everything manually. Use AI to move fast.
* * *
## Important: Please Time Yourself
Before you begin each section, start a stopwatch or timer. Record your time separately for the Primary Task, Secondary Task, and each Bonus Task you attempt. Do not pause the timer unless taking a genuine break. You will be asked to share your time breakdown during our discussion call, so keep a written note of it.
* * *
## Background
We hypothesize that introducing a structured onboarding flow for our Telegram chatbot will improve user retention. Since retention is a lagging metric (typically requiring 30 to 60 days to observe), our primary evaluation metric will be research-based and should serve as a reliable leading indicator that correlates with long-term retention.
* * *
## Marking Overview

| Section | Marks |
| ---| --- |
| Primary Task: A/B Test Chatbot (n8n + Statsig) | 40 |
| Secondary Task: Health Chatbot | 25 |
| Bonus Task 1: Expo Go Mobile App | 15 |
| Bonus Task 2: Real-time Sync and Push Notifications | 10 |
| Bonus Task 3: Analytics Dashboard | 10 |
| Walkthrough Video | 10 |
| Total | 110 |

> Bonus tasks are optional but carry significant marks and will strongly differentiate candidates. Attempt as many as you can within the time budget.
* * *
## Primary Task: A/B Test Chatbot in n8n \[40 marks\]
### 1\. Build a Telegram Chatbot A/B Test in n8n
Develop a simple Telegram chatbot that automatically assigns each new user to one of two groups:
*   **Control Group** — receives a generic welcome message
*   **Test Group** — goes through a guided 3-step onboarding flow
You must use **Statsig** as the A/B testing provider for group assignment.
### 2\. Event Logging
Log every group assignment and key user event in a structured manner to enable downstream analysis.
### 3\. Evaluation Plan
Define a rigorous evaluation framework that includes:
*   A **primary metric** (leading indicator correlated with long-term retention)
*   **Guardrail metrics** (e.g., bot block rate) to detect unintended negative effects
*   **Secondary metrics** (e.g., Day-7 return rate, onboarding completion rate)
*   A **pre-committed decision framework** outlining how results will be interpreted and acted upon
* * *
## Secondary Task: Health Chatbot \[25 marks\]
Build a simple health chatbot on Telegram where users can:
*   Log meals
*   Track their day
*   Edit logged meals
*   Delete logged meals
This can be kept lightweight in scope. Focus on clean command handling and reliable data storage.
* * *
## Bonus Tasks \[up to 35 marks\]
### Bonus Task 1: Expo Go Mobile App \[15 marks\]
Build a simple React Native mobile app using **Expo Go** that syncs with the health chatbot. The app should reflect the same meal data that users log via Telegram, in real time (or near real time).
Screens to include:
*   A meal log screen listing all meals with timestamps
*   Ability to add, edit, and delete meals directly from the app
*   Changes made in the app should reflect in the chatbot's data and vice versa
> **Tip:** Use a shared backend (e.g., Supabase, Firebase, or any simple REST API) to keep both the chatbot and the app in sync.
### Bonus Task 2: Real-time Sync and Push Notifications \[10 marks\]
Extend Bonus Task 1 with the following:
*   Real-time updates in the mobile app when a meal is logged via Telegram (no manual refresh)
*   A daily push notification reminding users to log their meals (e.g., at a set time each evening)
*   A simple daily summary notification showing total meals logged for the day
### Bonus Task 3: Analytics Dashboard \[10 marks\]
Build a minimal analytics dashboard (can be a simple web page or an in-app screen) that visualizes:
*   Daily meal logging activity over the past 7 days
*   A/B test group distribution (Control vs. Test users)
*   Onboarding funnel completion rate for the Test group
> **Tip:** You can use a simple charting library like Recharts, Chart.js, or Victory Native.
* * *
## Definition of Done
Your submission is complete when:
*   All primary task features are functional (A/B test, event logging, evaluation plan)
*   The chatbot supports meal logging, editing, and deletion
*   App runs without errors
*   README includes clear setup instructions
*   Code is pushed to a **public** GitHub repository
*   Walkthrough video is recorded (5 to 10 minutes)
* * *
## Submission Requirements
### GitHub Repository
*   Push all your work to a **public** GitHub repository
*   Maintain a **clean commit history** that shows your progression, not one giant commit
*   Your `README.md` must include:
    *   Setup instructions (how to run locally)
    *   Environment variables needed
    *   Architecture overview (brief)
    *   Tools and services used and why (1 to 2 sentences each)
    *   Any assumptions or trade-offs you made
    *   Approximate time breakdown per section
### Walkthrough Video \[10 marks\]
Record a **5 to 10 minute** walkthrough video and upload it to Loom, YouTube (unlisted), or Google Drive.
Your video should cover:
*   A live demo of the working solution end-to-end
*   A brief explanation of your architecture decisions
*   What you would improve or add with more time
*   Any interesting challenges you ran into
> A clear, well-structured walkthrough video demonstrates communication skills and product thinking, both of which we value highly.
### How to Submit
Reply to your recruiter with:
1. GitHub repository link (must be public)
2. Video link (Loom, YouTube unlisted, or Google Drive)
3. Any notes about your submission
* * *
## Evaluation Criteria
### What Impresses Us
*   Clean commit history showing progression
*   Thoughtful use of AI tools, not just copy-paste
*   Documented trade-offs ("I chose X because Y")
*   Code that is easy to read and extend
*   A walkthrough video that is clear, confident, and concise
### What Concerns Us
*   Code that does not run
*   Missing core features
*   No documentation or README
*   One giant commit with no history
*   A walkthrough video that is unclear or missing entirely
* * *
## Questions?
If something is unclear, ask. We would rather you clarify than assume incorrectly.
Reach out to [bhavesh@calorai.ai](mailto:bhavesh@calorai.ai) with any questions before you begin.
* * *
**Good luck! We are excited to see what you build.**