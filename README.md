# ITEC-APP
# ITEC-App: Teacher Candidate Support System

## Description
This application is designed to support Teacher Candidates working towards their initial teacher education certification and degree. It aims to provide a comprehensive tool for tracking progress, accessing resources, and facilitating communication throughout the program.

## Purpose
The purpose of this app is to:
- Streamline the journey of Teacher Candidates through their education program
- Provide easy access to essential resources and information
- Facilitate tracking of progress and completion of program requirements
- Enhance communication between candidates, instructors, and program administrators

## Planned Features
- User authentication for Teacher Candidates, Instructors, and Administrators
- Dashboard displaying program progress and upcoming deadlines
- Resource library with teaching materials, lesson plan templates, and educational research
- Progress tracking tool for practicum hours, course completions, and certification requirements
- Communication platform for announcements, discussions, and direct messaging
- Calendar integration for important dates, workshops, and submission deadlines
- Digital portfolio creation for Teacher Candidates to showcase their work

## Target Users
- Teacher Candidates enrolled in the initial teacher education program
- Faculty and Instructors involved in the program
- Program Administrators and Support Staff

## Technologies (Proposed)
- Frontend: [e.g., React, Vue.js]
- Backend: [e.g., Node.js, Django]
- Database: [e.g., MongoDB, PostgreSQL]
- Authentication: [e.g., JWT, OAuth]
- Hosting: [e.g., Heroku, AWS]

## Future Enhancements
- Integration with state certification databases
- AI-powered lesson planning assistant
- Virtual classroom simulation for practice teaching
- Mobile app version for on-the-go access

## Project Status
This project is currently in the initial planning and development phase. The README will be updated as the project progresses.
As of 9/8/2024- Installed Flutter, Visual Studio, VS Code User, Android Studio and Git.  Set up an old phone as my emulator and turned on the developer options.  
Subscribed to Poe to address the "running out of credits way too fast" issue. 

## Resources
Sources:

I am reviewing the following sources to determine what features the APP should focus on:

Based on the report's evaluation criteria, the app can offer self-assessment tools for candidates to evaluate their readiness and areas for growth.
A library of resources focused on culturally responsive teaching and diversity in education could be included.
Features that facilitate mentorship and networking among candidates and experienced educators.
Tools for reflective practice and feedback loops to encourage continuous learning and adaptation.
EVALUATING AND IMPROVING TEACHER PREPARATION PROGRAMS CONSENSUS REPORT
https://naeducation.org/wp-content/uploads/2024/04/Evaluating-and-Improving-Teacher-Preparation-Programs.pdfLinks to an external site.

Recruiting the Next Generation of Great Educators
https://www.nea.org/resource-library/great-teaching-and-learning/recommendations/potential-teacherLinks to an external site.

Responsibilities of Teacher Candidates
https://www.stonybrook.edu/commcms/dtale/guide/responsibilities_teacher_candidate.phpLinks to an external site.

Developing Quality Fieldwork Experiences for Teacher Candidates A Planning Guide for Educator Preparation Programs and District Partners
https://ceedar.education.ufl.edu/wp-content/uploads/2017/03/CEEDAR-FieldExperGuide-508.pdfLinks to an external site.

An analysis of teacher candidate success as measured by admission requirements
https://files.eric.ed.gov/fulltext/EJ1111067.pdfLinks to an external site.

Assessing and evaluating teacher preparation programs
https://www.apa.org/ed/schools/teaching-learning/teacher-preparation-programs.pdfLinks to an external site.

# Troubleshooting the Flutter Installation and Emulator Setup

In this document, I will walk through the problems I encountered during the setup of Flutter and the external emulator (an old phone), and how I used AI (Claude) to resolve these issues.

## 1. Pathway Error in Flutter

### Problem:
While installing Flutter, I encountered a pathway error that prevented the Flutter SDK from being recognized properly by the system.

### Steps Taken to Resolve:

1. I first checked that I had added the Flutter SDK to the system’s environment variables correctly.
2. After verifying the path, I noticed there was a mistake in the directory path.
3. I used **Claude (via Poe)** to assist me with the correct commands to fix the path. Claude suggested running a few commands to troubleshoot and verify the current environment setup:
    ```bash
    echo $PATH
    ```
4. Claude walked me through updating the environment variables on my system:
    - I added the correct path to the system’s **Path** environment variable.
5. Finally, I restarted my terminal, ran the Flutter doctor command, and the issue was resolved.
   ```bash
   flutter doctor
### Installed the following 
1. Visual Studio Code
2. Visual Studio 2022
3. Android Studio

### To Begin Building the App
1. Using Windows Power Shell
2. Command Palette
### Built Sample App on old phone
Used USB to attach an old phone and built a simple APP as provided by CodeLab
YouTube: https://www.youtube.com/watch?v=8sAyPDLorek&t=3323s
## Assignment 4:
AI Assistance- Throughout this project, I've utilized AI to assist with:
1. Code generation for the APP and Troubleshooting code errors with Flutter

## Contact
Ronda Cypret - RCypret-Mahach@Lindenwood.edu
Program: College of Education & Human Services/ Curriculum & Instruction/ Initial Teacher Education with Lindenwood University

## Acknowledgments
This project is being developed as part of an IRB Application by Dr Ronda Cypret with Lindenwood University.
