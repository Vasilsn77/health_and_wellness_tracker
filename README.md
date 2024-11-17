# Health and Wellness Tracker

A Flask-based web application that helps users track their physical and mental health, set wellness goals, and connect with friends sharing similar objectives.

---

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Database Schema](#database-schema)
- [File Structure](#file-structure)
- [Routes](#routes)
- [Future Improvements](#future-improvements)

---

## Features
1. **User Management**
   - Register, login, and logout functionality.
   - Profile management and session handling.

2. **Mental Health Tracking**
   - Log daily mood ratings and stress levels.
   - View historical data and delete entries.

3. **Exercise Tracking**
   - Log activities and track calories burned.
   - View exercise history and activity statistics.

4. **Goal Management**
   - Create and manage custom health goals.
   - Track progress and visualize completion rates.

5. **Social Features**
   - Add friends, accept/reject requests, and view friend lists.

6. **Dashboard**
   - Overview of health metrics, goal progress, and recent activities.

---

## Technology Stack
- **Backend:** Python Flask
- **Frontend:** HTML/CSS/JavaScript with Jinja2 templates
- **Database:** MySQL
- **Authentication:** Session-based

---

## File Structure
- `health-wellness-tracker/`
  - `app.py`: Main Flask application containing routes and logic.
  - `templates/`: HTML templates for rendering views.
    - `index.html`: Homepage template.
    - `register.html`: User registration page.
    - `login.html`: User login page.
    - `dashboard.html`: User dashboard displaying health metrics.
    - `mental_health_check.html`: Form to log mental health data.
    - `mental_health_history.html`: View past mental health entries.
    - `exercise_log.html`: Form to log exercise details.
    - `exercise_history.html`: View exercise history and statistics.
    - `goals.html`: Manage user health and fitness goals.
    - `friends.html`: View and manage friend connections.
    - `add_friend.html`: Add a friend by email.
  - `static/`: Static assets for styling and interactivity.
    - `css/`: Stylesheets for the application.
      - `style.css`: Custom CSS for layout and design.
    - `js/`: JavaScript files for frontend functionality.
      - `scripts.js`: Custom JavaScript for interactivity.
---

## Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Vasilsn77/health_and_wellness_tracker.git
   cd health-wellness-tracker
