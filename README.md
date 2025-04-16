# SCMS Online Exam System

## Overview
This repository contains the Online Exam Subsystem for the School/College Management System (SCMS). The online exam module enables students to take exams remotely, with features for timed assessments, automatic submission, and detailed result analysis.

## Features
- **Exam Dashboard**: Browse and access available exams with timing information
- **Active Exam Interface**: Take exams with various question formats (multiple choice, essay)
- **Persistent Timer**: Tracks remaining time even if the page is refreshed
- **Automatic Submission**: Submits exams when time expires
- **Result Analysis**: View comprehensive exam results with correct/incorrect indications
- **Deadline-Based Access Control**: Controls access to detailed results based on exam deadline

## Pages
1. **Exam Dashboard** (`index.html`)
   - Lists all available exams with dates, times, and duration
   - "Start Exam" button becomes active when an exam is available
   - Visual indicators for upcoming, active, and past exams

2. **Active Exam** (`active_exam.html`)
   - Interactive interface for taking the exam
   - Supports multiple choice and essay-type questions
   - Persistent timer that continues correctly even after page refresh
   - Submission button to complete the exam

3. **Exam Result** (`exam_result.html`)
   - Shows submission status and overall score
   - Conditional navigation based on submission time vs. deadline
   - Score visualization with progress bar

4. **Detailed Exam Result** (`detailed_exam_result.html`)
   - Question-by-question breakdown with correct answers
   - Color-coded feedback (correct, partially correct, incorrect)
   - Instructor comments on essay responses
   - Only accessible after the exam deadline

## Technologies
- HTML5
- CSS (Tailwind CSS, DaisyUI)
- JavaScript (ES6+)
- Font Awesome Icons


## Integration with SCMS
This subsystem is designed to integrate seamlessly with the broader School/College Management System. It shares the same design language, authentication flow, and database architecture as other SCMS modules.

Other SCMS modules include:
- Student Management
- Course Management
- Attendance Tracking
- Assignment Submission
- Library Management
- Activities and Events
- Complaints Handling



