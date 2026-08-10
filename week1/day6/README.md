# Day 6 - SOQL and Apex Triggers

## What is SOQL?

SOQL stands for Salesforce Object Query Language. It is used to retrieve records and data from Salesforce objects.

Example:
Find all students in a course.

---

# What is an Apex Trigger?

An Apex Trigger is a piece of code that runs automatically when records are inserted, updated, deleted, or restored in Salesforce.

---

# Difference Between Flow and Trigger

## Flow
- No-code automation
- Easier to build
- Best for simple business processes

## Trigger
- Programming-based automation
- Handles complex logic
- Used for advanced automation and integrations

---

# Difference Between Before Trigger and After Trigger

## Before Trigger
Runs before saving data to the database.

Example:
Validate student information before saving.

## After Trigger
Runs after data is saved.

Example:
Send notification after student registration.

---

# Trigger Use Cases for College Management System

## 1. Welcome Email After Registration
Event:
After a student record is created.

## 2. Attendance Warning
Event:
After attendance percentage becomes less than 75%.

## 3. Notify Faculty When Course is Full
Event:
After course seats reach maximum limit.

## 4. Fee Reminder Notification
Event:
After fee due date approaches.

## 5. Auto Generate Student ID
Event:
Before student record is saved.

---

# Query Examples

## 1.
Find all students in Course A.

## 2.
Find all courses handled by Faculty X.

## 3.
Find students with attendance below 75%.

## 4.
Find students who did not pay fees.

## 5.
Find courses with available seats.

---

# Reflection

Enterprise systems need event-driven behavior because systems must automatically react to important data changes quickly and accurately without manual work.

---

# Trailhead Modules Completed

1. Database & .NET Basics
2. Apex Triggers

---

# Learning Outcomes

- Learned SOQL basics
- Understood Apex Triggers
- Learned event-driven automation
- Understood Flow vs Trigger
- Learned how systems react automatically to events
