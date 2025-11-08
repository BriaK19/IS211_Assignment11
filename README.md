# IS211 Assignment 11 – Flask To-Do List App

## Overview
This project is a simple **To-Do List web application** built using the **Flask** framework for **IS211 – Software Application Programming II**.  
The app allows users to add, view, and clear tasks directly from a browser interface.

---

## Features
- Add new tasks with:
  - Task name
  - Email address
  - Priority level (Low, Medium, High)
- View all current tasks in a formatted HTML table
- Clear all tasks instantly
- Input validation for email and priority fields
- Flash messages for user feedback (success/error)

---

## How It Works
The application uses Flask routes:
- `/` → Displays the list and the task submission form  
- `/submit` → Handles form submissions and adds new tasks  
- `/clear` → Clears all tasks  

All tasks are stored temporarily in memory using a Python list.  
When the Flask server restarts, the list resets (per the assignment requirements).

---

## File Structure
