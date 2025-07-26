# Day 3 – Group Policy Struggles (but Progress!)

### 🧠 What I worked on:
- Created a GPO named `INTERNS GPO tasks`
- Linked it to the `INTERNS` OU
- Configured:
  - Disable Task Manager
  - Set a desktop background image
- Applied security filtering (added Domain Users, Neyger, and Admins)

### 🛑 What went wrong:
- Tried to test the GPO on a client VM using Windows 10 **Home**
- Hit a wall: Home editions **can’t join domains**, so GPO didn’t apply
- Spent hours troubleshooting logon permissions, OU structure, and login rights

### ✅ What I learned:
- GPO linking, security filtering, OU targeting
- Domain login policies and Local Security Policy
- How to troubleshoot logon errors
- That **Windows 10 Pro is required** to test GPOs

### 📸 Screenshots:

---

Will install Windows 10 Pro tomorrow and **come back to test it all properly**.

#60DayITChallenge #HelpDesk #ActiveDirectory #GroupPolicy #itspecialist

<img width="1020" height="785" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/35315006-ae1d-48c4-978a-573aa5691a6e" />

