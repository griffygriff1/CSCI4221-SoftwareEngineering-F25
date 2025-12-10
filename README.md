# CSCI4221-SoftwareEngineering-F25
For Class
### Griffin Sanders — Project Manager
Oversees the entire project and keeps the team organized.
Make sure deadlines are met and everyone knows their tasks.
Communicates between the team and the professor (or stakeholders).
Helps resolve problems and keeps the project on track.
# Project Planning for Calendar and Budget Application

This repository contains the product backlog items and vision statement for a smart calendar and budgeting application.
# Minutes 1 – Group 1

| PBI | Status | Sprint | Estimate | Assigned | Reviewer |
| --- | --- | --- | --- | --- | --- |
| 1. Research and document user behaviours of busy professionals using scheduling apps | Ready for consideration | 2 weeks | One senior UX researcher for 40 hours | Sharif Muhammad | Cameron Brown |
| 2. Analyze time-management and expense-tracking needs of students | Ready for consideration | 2 weeks | One senior UX researcher for 40 hours | Cameron Brown | Griffin Sanders |
| 3. Collect insights on how families plan and share events and budgets | Ready for consideration | 2 weeks | One senior UX researcher for 40 hours | Griffin Sanders | Sharif Muhammad |
| 4. Prototype a Calendar System with Event Conflict Detection, showing how overlapping tasks are identified and flagged for rescheduling | Ready for refinement | 3 weeks | Two junior developers for 72 hours | Cameron Brown | Griffin Sanders |
| 5. Prototype a Notification Center that manages custom reminders, frequency settings, and smart prioritization of alerts | Ready for refinement | 3 weeks | One senior and one junior developer for 64 hours | Sharif Muhammad | Cameron Brown |
| 6. Prototype a User Engagement Dashboard that tracks task completion and introduces features to reduce abandonment (like streaks or progress tracking) | Ready for refinement | 3 weeks | Two junior developers for 72 hours | Griffin Sanders | Sharif Muhammad |
| 7. As a teacher, I want to organize class lessons, parent meetings, and grading deadlines on the calendar so I can stay on top of my weekly schedule | Ready for implementation | 4 weeks | Two juniors and one senior for 96 hours | Cameron Brown | QA lead |
| 8. As a college student, I want to link my budget to semester expenses (like books, tuition, and clubs) so I can see how each event impacts my spending | Ready for implementation | 4 weeks | One senior developer for 56 hours | Sharif Muhammad | UX lead |
| 9. As a working parent, I want to receive reminders for family events and bills so I can balance work, home activities, and budget responsibly | Ready for implementation | 4 weeks | Two juniors and one senior for 96 hours | Griffin Sanders | Product manager |
# Product Vision Statement 

Our goal is to create a smart, reactive calendar application that helps users organize events, manage budgets, and receive timely reminders without clutter or confusion. By integrating budgeting with scheduling, the app provides a single, clear view of time and money — making everyday planning effortless and efficient.
# Minutes for the Meeting

- Discussed and created the vision statement  
- Discussed PBI & Sprint Table  

### Issues with the program (using a student persona example)

1. **Overlapping Tasks and Calendar Conflicts:**  
   Users may schedule multiple tasks or events at the same time without realizing it.  
   Without a proper conflict-detection system, this can cause confusion and missed deadlines.

2. **Notification Overload or Missed Reminders:**  
   If reminders are too frequent, users might start ignoring or disabling them.  
   If they are too sparse or fail to trigger, users could miss important deadlines.

3. **Poor User Engagement / Task Abandonment:**  
   Users might stop using the app if the interface feels cluttered, unintuitive, or too time-consuming to add/manage tasks.  
   This can lead to abandoned to-do lists and reduced adoption of the app.

---

- Identified one feature of the software and began prototyping it  
- Discussed adding a calendar/email notification feature  
- Talked about making the calendar reactive  
- Created use cases explaining why someone would use the app  
- Added a budget feature to track money  


# Group 1 Meeting Minutes  
**Date:** October 22, 2025  
**Members Present:** Shariff, Cam, Griffin  

---

## Discussion Summary

- **Topic 1:** Installation of **Node.js**  
  - Reviewed the process of how to install Node.js on each member’s system.  
  - Ensured everyone understood setup requirements for project compatibility.  

- **Topic 2:** Importance of the **PBI Chart**  
  - Discussed how the PBI chart connects to Node.js in our workflow.  
  - Identified tasks to track installation progress and dependencies.  

---

##  Next Meeting

- **Date:** Friday, October 25, 2025  
- **Goal:**  
  Ensure all installations are complete so the team can **begin project development** by Friday.

---

**Prepared by:** Griffin  
**Team:** Group 1
# Project 3 – React Native Expo App (Calendar Conflict Detection)
**Author:** Griffin Sanders  
**Course:** CSCI 4221 – Software Engineering   

This section documents all work completed for **Project 3**, 

#  Project 3 Summary
For Project 3, I implemented the **Calendar Event Conflict Detection feature**, which was assigned to me in Project 2.  
The goal of this feature is to display scheduled events and highlight overlapping tasks visually inside a React Native Expo application.

This project includes:

- A working **React Native Expo app** created using `npx create-expo-app`  
- A functional **Home Screen**  
- A functional **Calendar Screen**  
- Event conflict detection (overlapping events shown with a warning color)  
- Two clickable interactions on the home screen  
- Updated PBIs for Project 3  
- A new meeting minutes document  
- Full folder structure generated automatically by Expo  
- Everything pushed to GitHub as required  

---

#  Project 3 Meeting Minutes (Required File)

**Date:** February 9, 2025  
**Members Present:** Griffin, Shariff, Cam  

### **Topics Discussed**
1. **Progress Reports**
   - Griffin: Calendar conflict detection feature being implemented in React Native Expo.
   - Shariff: Working on notification center planning.
   - Cam: Reviewing UI layout options for faculty scheduling feature.

2. **Issues**
   - Expo Go was not loading the project due to dependency mismatch.
   - QR code initially loaded the Expo welcome page instead of the app.
   - Solution: Updated Expo CLI + restarted server + rebuilt folder structure.

3. **Repository / PBI Updates**
   - Added Project 3 PBI items (Calendar Conflict Detection).
   - Verified correct Expo folder structure exists in repository.
   - Confirmed each member’s tasks for Project 3.

### **Next Meeting**
**Date:** October 27th, 2025  
**Goal:** Validate that all Project 3 features run inside Expo Go on iOS/Android.

**Minutes Prepared By:** Griffin Sanders  

---

# PBI Item Completed for Project 3 (Required File)

## **PBI Title: Calendar Interface With Event Conflict Detection (React Native Expo)**

### **Description**
Create the UI and logic for displaying calendar events and identifying overlapping tasks.  
This includes:
- A working Home Screen
- A “Show Tasks” button
- A Calendar display screen
- Events visually rendered
- Overlapping events highlighted or labeled as conflicts

### **Why This PBI?**
This directly extends PBI #4 from Project 2:  
> “Prototype a Calendar System with Event Conflict Detection, showing how overlapping tasks are identified and flagged for rescheduling.”

### **Acceptance Criteria**
- App runs in Expo Go on iPhone/Android  
- At least **two interactive clicks** work on the home screen  
- Calendar displays events  
- Overlapping events receive a conflict warning  
- All code generated using AI  

### **Sprint Estimate**
3 weeks – 72 hours – 2 junior dev equivalents

### **Assigned To**
**Griffin Sanders**

### **Reviewer**
**Sharif Muhammad**

---

# 🔄 Updated PBI Table (Project 3 Requirement)

| PBI # | Item | Status | Sprint | Estimate | Assigned | Reviewer |
|------|------|--------|--------|----------|----------|----------|
| 1 | Research user behavior of professionals | Completed | 2 weeks | 40 hrs | Sharif | Cameron |
| 2 | Analyze time-management needs of students | Completed | 2 weeks | 40 hrs | Cameron | Griffin |
| 3 | Insights on family event/budget planning | Completed | 2 weeks | 40 hrs | Griffin | Sharif |
| 4 | **Calendar System With Conflict Detection (React Native implementation)** | **Completed – Project 3** | 3 weeks | 72 hrs | **Griffin** | Sharif | Cam |
| 5 | Notification Center prototype | Ready for refinement | 3 weeks | 64 hrs | Sharif | Cameron |
| 6 | User Engagement Dashboard prototype | Ready for refinement | 3 weeks | 72 hrs | Griffin | Sharif |
| 7 | Teacher lesson/meeting scheduling | Ready for implementation | 4 weeks | 96 hrs | Cameron | QA Lead |
| 8 | Student budget linking | Ready for implementation | 4 weeks | 56 hrs | Sharif | UX Lead |
| 9 | Working parent reminders | Ready for implementation | 4 weeks | 96 hrs | Griffin | Product Manager |

---

# 📱 App Demonstration Summary (Professor Wants to See This)

### **Home Screen**
- Displays welcome information  
- Contains at least **two clickable buttons**  
  - **Show Tasks** → opens calendar  
  - **View Conflicts** → highlights overlapping tasks  

### **Calendar Screen**
- Shows sample events (hard-coded for prototype)
- Overlapping events turn **red** or show a **"Conflict" label**
- Events are rendered using JavaScript Date objects and simple overlap logic  

### **Runs Fully in Expo Go**
- Verified running on physical phone  
- QR code scans correctly  
- No missing dependencies 
