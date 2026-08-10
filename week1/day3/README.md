# Day 3 - Data Modeling and Business Logic

## What is an App?

An App in Salesforce is a collection of objects, tabs, and tools used for a business purpose.

---

# What is an Object?

An Object is a database table used to store data.

Examples:
- Student
- Faculty
- Course

---

# What is a Record?

A Record is a single row of data inside an object.

Example:
A student's details stored in the Student object.

---

# What is a Field?

A Field stores specific information inside an object.

Examples:
- Name
- Email
- Age

---

# Difference Between Standard and Custom Objects

## Standard Objects
Objects already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

## Custom Objects
Objects created based on business needs.

Examples:
- Student
- Faculty
- Course

---

# College Management System Data Model

## Objects
- Student
- Faculty
- Course
- Department

---

# Relationships

- One Department has many Students
- One Faculty teaches many Courses
- One Course has many Students

Lookup relationships connect related objects together.

---

# Formula Fields

## 1. Full Name
Combines first name and last name automatically.

## 2. Percentage
Calculates student percentage automatically.

## 3. Remaining Seats
Calculates available course seats automatically.

Formula fields reduce manual calculations and save time.

---

# Validation Rules

## 1. Email cannot be empty
Prevents missing contact information.

## 2. Student age cannot be negative
Prevents invalid age data.

## 3. Course seats cannot exceed limit
Prevents incorrect seat allocation.

Validation rules help maintain accurate and valid data.

---

# Reflection

Companies need structured data because random spreadsheets can create duplicate, missing, and inconsistent information. Structured systems improve accuracy, organization, security, and reporting.

---

# Trailhead Modules Completed

1. Data Modeling
2. Formulas and Validations

---

# Learning Outcomes

- Learned Objects, Fields, and Records
- Understood relationships between objects
- Learned Formula Fields
- Learned Validation Rules
- Understood importance of structured data
