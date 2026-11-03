# Placement Eligibility Decision Engine

A Core Java project that checks whether a candidate is eligible for a selected job.

## Features

- Runtime candidate input
- Runtime candidate skills
- Runtime job input
- Multiple jobs using arrays
- Runtime job selection
- Percentage eligibility
- Backlog eligibility
- Graduation year eligibility
- Skill eligibility
- Final readable eligibility result

## OOP Concepts Used

- Encapsulation
- Abstraction
- Inheritance
- Method Overriding
- Polymorphism
- HAS-A Relationship

## Project Structure

- Main.java – Controls application flow
- Candidate.java – Stores candidate data and skills
- Job.java – Stores job requirements and required skills
- EligibilityRule.java – Abstract parent for all eligibility rules
- PercentageRule.java – Checks percentage
- BacklogRule.java – Checks backlogs
- GraduationYearRule.java – Checks graduation year
- SkillRule.java – Checks required skills
- EligibilityChecker.java – Executes all rules

## Compile

javac src/*.java

## Run

java -cp src Main