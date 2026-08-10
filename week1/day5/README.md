# Day 5 - Apex Introduction

## What is Apex?

Apex is a programming language used in Salesforce to implement custom business logic and advanced automation.

---

# Why Apex is Needed

Flows and configuration tools are useful for simple automation, but some complex business requirements need programming using Apex.

---

# Difference Between Flow and Apex

## Flow
- No-code automation
- Easy to use
- Suitable for simple business logic

## Apex
- Programming-based solution
- Used for advanced customization
- Handles complex logic and integrations

---

# Difference Between Configuration and Coding

## Configuration
Uses clicks, settings, and drag-and-drop tools without programming.

Examples:
- Validation Rules
- Flow Builder
- Reports

## Coding
Uses Apex programming for advanced features.

Examples:
- Complex calculations
- API integration
- Advanced automation

---

# Real Examples Where Apex is Needed

## 1. Complex Fee Calculation
Different fee structures based on category and scholarship require custom logic.

## 2. External Payment Integration
Connecting Salesforce with online payment systems needs Apex APIs.

## 3. Advanced Eligibility Checking
Student eligibility based on attendance, marks, and rules requires complex conditions.

---

# Integrated College Management System

## CRM
Used to manage student admissions and communication.

## Objects
- Student
- Faculty
- Course
- Department

## Relationships
- Students enroll in Courses
- Faculty teaches Courses
- Department manages Courses

## Validation
- Email cannot be empty
- Age cannot be negative

## Formula Fields
- Percentage
- Remaining Seats

## Flow Automation
- Auto email after registration
- Fee reminder notifications

## Apex Usage
- Advanced fee calculations
- External integrations
- Complex business rules

---

# Pseudocode Examples

## Example 1

IF seats are full  
THEN block registration

---

## Example 2

IF attendance < 75%  
THEN notify student

---

## Example 3

IF fee is unpaid  
THEN send reminder email

---

# Reflection

Enterprise systems cannot depend only on clicks and configuration because some business requirements are complex and require programming logic, integrations, and advanced processing.

---

# Trailhead Modules Completed

1. Apex & .NET Basics
2. Apex Basics & Database

---

# Learning Outcomes

- Learned Apex basics
- Understood Flow vs Apex
- Learned programming logic concepts
- Connected all Salesforce concepts together
