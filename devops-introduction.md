# DevOps Introduction

## Stakeholders

**Definition:**
Stakeholders are people or organizations who are involved or interested in the system.

### Examples

* **School System** → Students, Teachers, Parents, Principal, Management
* **Bank System** → Customers, Employees, Managers, Management, Government
* **IT Project** → Clients, Developers, Testers, DevOps, Users, Management

### Who are the stakeholders in your project?

The stakeholders in our project include:

* Clients
* Users
* Developers
* Testers
* DevOps Team
* Management

---

# SDLC

**SDLC = Software Development Life Cycle**

SDLC is a structured process used to plan, design, develop, test, deploy, and maintain software throughout its life cycle.

### Main Goal

Deliver reliable software that meets customer requirements within time and budget.

### Reliable

Reliable means a system works correctly and consistently with minimum failures.

---

# Phases of SDLC

1. **Requirement Analysis**

   * Identify and document the requirements of customers, clients, and end users.

2. **Planning & System Design**

   * Plan the project and design the architecture, database, APIs, and UI.

3. **Implementation / Development**

   * Developers write the code and fix bugs.

4. **Testing**

   * Test the software and fix bugs.

5. **Deployment**

   * Release the software to users.

6. **Maintenance**

   * Monitor, support, and fix issues.

---

# SDLC Models

* Waterfall
* Agile
* Agile with DevOps

### Waterfall

Waterfall is a step-by-step development model.

### Agile

Agile is an iterative and incremental development model with frequent feedback and small releases.

### Agile with DevOps

Agile with DevOps focuses on continuous feedback and continuous improvement through automation.

---

# Waterfall vs Agile vs Agile with DevOps

## Example: School Examination System

Let's understand these concepts using a school management system for student examinations.

### Waterfall Approach

Imagine a school conducting examinations for students only once a year.

* Parents → Paying fees
* Students → Studying
* Teachers → Teaching students

### End Result

* 40% → Fail
* 60% → Pass

### Problem

The problem is identified only at the end of the year.

By the time the results are available, there is very little time to analyze the problem and improve student performance.

This is similar to the **Waterfall model**.

---

# Waterfall Model

Waterfall model is a linear, step-by-step software development model where each phase is completed before moving to the next phase.

### Phases of Waterfall Model

```text
Requirement
     ↓
Design
     ↓
Development
     ↓
Testing
     ↓
Deployment
     ↓
Maintenance
```

### Disadvantages of Waterfall

* Not flexible when requirements change.
* Problems are discovered late.
* Changes can be costly after a phase is completed.
* Final feedback comes late from customers/users.
* Working software is delivered late.

---

# Agile - Continuous Assessment & Examination Model

Instead of conducting only one exam at the end of the year, the school conducts multiple exams throughout the year.

### Examination Flow

```text
Unit-Test-1
    ↓
Unit-Test-2
    ↓
Unit-Test-3
    ↓
Unit-Test-4
    ↓
Unit-Test-5
    ↓
Unit-Test-6
    ↓
Quarterly
    ↓
Half-Yearly
    ↓
Pre-Final
    ↓
Final Exam
```

This allows teachers to check student performance regularly and get feedback earlier.

---

## Unit-Test-1

**Teachers:** Complete the required syllabus before conducting the exam.

**Students:** Start preparing before the exam, for example, one week in advance.

### Result

* 60% → Pass
* 40% → Fail

### Analyze the Results

The school now has time to:

* Analyze failing students' problems.
* Understand why students are failing.
* Conduct student-parent meetings.
* Identify areas where students need improvement.

### After analyzing the students' problems and taking corrective actions

**Pass percentage → 65%**

The result improves:

**60% → 65%**

This shows the benefit of frequent feedback and improvement.

---

# Final Exam

After continuous assessments and improvements:

* 80% → Pass
* 20% → Fail

The remaining students who need improvement can receive targeted practice and additional support.

---

# What is Agile?

Agile is an iterative and incremental software development model where software is developed in small increments, with frequent feedback and continuous improvement.

---

# Sprint

A **Sprint** is a fixed time period in which the team develops and delivers a small part of the software.

### Why do we use Sprints in Agile?

Sprints help divide a large application into small, manageable parts and develop them step by step within a fixed time period.

---

# Agile Advantages Over Waterfall

* Flexible to requirement changes.
* Early defect detection.
* Lower cost for changes.
* Frequent customer feedback.
* Early delivery of working software.

---

# Agile with DevOps - Targeted Improvement

After the Agile process, the school focuses specifically on the students who are still struggling.

## Small Tests

Conduct small tests regularly to identify specific problem areas.

## Teachers

Teachers analyze the results regularly and share the progress with parents.

## Additional Support

Additional study hours and better learning methods can be introduced to help students improve.

### Final Test Result

```text
80% Pass
   ↓
20% Need Improvement
   ↓
Targeted Practice
   ↓
Improved Result
   ↓
99% Pass (Example)
```

---

# What is Agile with DevOps?

Agile with DevOps means developing software in small increments and continuously building, testing, deploying, monitoring, getting feedback, and improving it using automation.

### Simple Meaning

**Agile** → How to develop software.

**DevOps** → How to build, test, release, deploy, monitor, and continuously deliver software.

---

# What is DevOps?

DevOps is a combination of **Development** and **Operations** that improves collaboration and automates the software delivery process.

### Simple Explanation

DevOps is the process of continuously:

* Building software
* Testing software
* Deploying software
* Monitoring software
* Improving software

---

# DevOps Flow

```text
Development
     ↓
Build
     ↓
Test
     ↓
Deploy
     ↓
Monitor
     ↓
Feedback
```

---

# Development vs Operations

### Development

```text
Code → Build → Test → Release
```

### Operations

```text
Deploy → Monitor → Maintain
```

---

# What is DevSecOps?

DevSecOps extends DevOps by integrating security into the software delivery process.

### Goal

Identify and fix security issues early in the development and delivery process.

### DevSecOps Flow

```text
Develop
   ↓
Build
   ↓
Security Scan
   ↓
Test
   ↓
Deploy
   ↓
Monitor
   ↓
Feedback
```

---

# Tools Used to Achieve DevOps

Different tools can be used to automate different stages:

| Tool           | Purpose                      |
| -------------- | ---------------------------- |
| Git            | SCM (Source Code Management) |
| Jenkins        | CI/CD                        |
| Scanning Tools | Security                     |
| Kubernetes     | Container Orchestration      |
| Cloud          | Scalability                  |
