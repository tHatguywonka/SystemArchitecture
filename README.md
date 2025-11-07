# SystemArchitecture
# System Architecture — PlanPal

# Overview
PlanPal is a web app. It has a front part (what users see) and a back part (where data is stored).  

- **Frontend:** React — shows the schedule and reminders.  
- **Backend:** Node.js + Express — handles user accounts and saves data.  
- **Database:** PostgreSQL — stores all events and users.  

# How it works
1. The user opens PlanPal on a phone or laptop.  
2. The front part talks to the back part through the internet (using HTTPS).  
3. The back part saves the user’s schedule in the database.  
4. When the user adds or edits something, it updates instantly.  
5. Reminders are sent from the server to the user before the task time.

# Why it works
This setup is simple, low-cost, and easy for small teams to build.  
It can grow later if more users join.
