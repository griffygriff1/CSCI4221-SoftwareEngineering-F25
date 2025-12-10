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





