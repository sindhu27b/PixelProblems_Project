# Code Challenge Platform

## Overview
This project is a dynamic code challenge platform with integrated AI capabilities for real-time evaluation. Users can write and test their HTML, CSS, and JavaScript code while receiving immediate, constructive feedback from AI, enhancing their learning experience.

---

## Features
### Client-Side:
- Built with **HTML**, **CSS**, and **JavaScript**.
- **Features**:
  - Question selection dropdown.
  - Integrated code editor for HTML, CSS, and JavaScript.
  - Real-time AI feedback displayed in the interface.

### Server-Side:
- Implemented using **Node.js** and **Express**.
- **Handles**:
  - User authentication (Sign-up and Login).
  - Communication with OpenAI GPT-4 API for evaluation.
  - Database interactions for user data and payment tracking.

### Database:
- **Firestore**:
  - Stores user data (e.g., usernames, hashed passwords, payment status).
  - Tracks user challenge progress.

---

## How It Works
### Data Flow:
1. **User Actions**:
   - Log in or sign up via the frontend.
   - Select a coding challenge.
   - Write code in the editor and submit for evaluation.

2. **Backend Processing**:
   - Server validates user session.
   - Sends code to the OpenAI API for evaluation.
   - Displays results on the frontend.

3. **Database**:
   - Updates user actions (e.g., progress, payment status) in Firestore.

---

## Tools and Technologies
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: Firestore
- **API**: OpenAI GPT-4
- **Other Services**:
  - SendGrid: For sending OTPs.
  - Stripe: For payment processing.
  - GCP: For Firebase integration.

---

## Achievements
- Fully responsive frontend for seamless coding and evaluation.
- Integrated OpenAI GPT-4 API for real-time feedback:
  - Syntax correctness checks.
  - Requirement fulfillment verification.
  - Constructive feedback and scoring.
- Secure user authentication and payment system using Firebase.

---
