# Realtime Classroom Consensus Vote & Monitor with Firebase

A small tool for classroom that allows people 'in class' to make consensus vote on some choices. Each person will be given a certain amount of points so they can spend on whatever choices they prefer. Class moderator or class master has the right to start, pause, resume, end session and control time window to accept points for each choice.

---

## Endpoint
- Voter Screen - /index.html
- Class Master Dashboard - /backend/dashboard.html
- Central Monitor - /backend/monitor.html

---

## Setup Step
- Add your Firebase project's configuration in each endpoint file
- Create Firebase Authentication account to access Class Master Dashboard
- Create new session and enter choices in Class Master Dashboard, get token list (*appears once*), distribute tokens to users, start session and proceed