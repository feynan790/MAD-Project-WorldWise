#  Capital City Quiz App

MULTIPLE CHOICE QUIZ APP WHICH HELP CHILDRENS TO REMEMBER CAPITAL CITIES OF COUNTRIES IN THE WORLD
https://docs.google.com/document/d/1jkgYIz91QgWkSV92gaxVggVEpIxcU18L/edit?usp=drivesdk&ouid=117917776562402914924&rtpof=true&sd=true

An interactive **Android mobile application** that allows users to test and improve their knowledge of world capital cities through a simple and engaging quiz experience. The app presents multiple-choice questions and displays the final score upon completion.

 
##  Project Overview

The **Capital City Quiz App** is designed to address the challenge of learning world geography in an engaging and accessible way. Traditional study methods can be boring and repetitive—this app turns learning into an enjoyable quiz-based experience with instant feedback.


##  Problem Statement

Most existing quiz apps:
- Are overloaded with unnecessary features
- Require constant internet connection
- Display intrusive ads
- Cover too many subjects at once

This project focuses on creating a **simple, distraction-free quiz application** specifically about **capital cities**, offering a quick **pick-up-and-play** learning experience.


##  Objectives

### General Objective
To develop a **user-friendly**, **interactive**, and **functional** Capital City Quiz mobile application.

### Specific Objectives
- Design UI screens: **Start**, **Quiz**, and **Results**
- Implement quiz logic:
  - Load and display multiple-choice questions
  - Validate answers and keep score
- Manage application state and transitions
- Handle all button interactions (Start, Next, Play Again, Exit)
- Display final score with clear visual feedback


##  Scope

This application includes:
- A fixed set of **10 capital city questions**
- A linear flow: **Start → Quiz → Results**
- Multiple-choice format
- Score calculation based on correct answers
- No external data or internet required


##  Tech Stack

 Component | Technology 
 Platform - Android 
 Language - Java 
 UI Layouts - XML 
 IDE - Android Studio 


##  Methodology (Development Phases)

### **Phase 1: UI Development**
- Set up project in Android Studio
- Create:
  - `StartActivity.java`
  - `QuizActivity.java`
  - `ResultsActivity.java`
- Implement layouts using XML

### **Phase 2: Logic Implementation**
- Create `Question` class to store:
  - Question text
  - Options
  - Correct answer index
- Create a question list (Question Bank)
- Implement answer validation and scoring logic

### **Phase 3: Testing**
- Test navigation and quiz flow
- Confirm scoring accuracy
- Debug all interactions


##  Final Deliverables

- Complete Android Studio source code (`.java` and `.xml` files)
- Fully functional APK for installation on Android devices
