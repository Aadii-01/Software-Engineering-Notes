# Software Quality Attributes & Software Myths

## Definition

Developing software is not just about making it work—it is about making it **high-quality**.

Software quality is determined by a set of characteristics known as **Quality Attributes**. However, many software projects fail to achieve these attributes because developers, managers, or customers believe incorrect assumptions called **Software Myths**.

> **Simple Definition**
>
> * **Software Quality Attributes** describe the characteristics of good software.
> * **Software Myths** are false beliefs that prevent teams from building good software.

---

# Why Study This Topic?

Understanding software quality helps developers build better software, while understanding software myths helps them avoid common mistakes.

Together they answer two important questions:

* **What makes software good?**
* **Why do software projects fail to achieve that quality?**

---

# What is Software Quality?

Software quality is the degree to which software satisfies:

* Customer requirements
* User expectations
* Performance requirements
* Security requirements
* Reliability requirements
* Maintainability requirements

Good software should not only produce correct results but should also be easy to use, secure, scalable, and maintainable.

---

# Major Quality Attributes

---

# 1. Correctness

## Definition

Software should perform exactly the functions specified in the requirements.

### Example

A calculator should correctly compute:

```
15 × 12 = 180
```

Incorrect output indicates poor correctness.

---

# 2. Reliability

## Definition

Reliability is the ability of software to perform consistently without failures.

Reliable software:

* Produces correct results
* Does not crash frequently
* Handles errors gracefully

### Example

Internet banking systems are expected to operate reliably 24×7.

---

# 3. Efficiency

## Definition

Efficiency refers to optimal use of:

* CPU
* Memory
* Storage
* Network
* Battery

### Example

A mobile application should consume minimal battery while maintaining good performance.

---

# 4. Usability

## Definition

Usability measures how easy software is to learn and use.

Good usability includes:

* Intuitive interface
* Easy navigation
* Accessibility
* Minimal learning curve

### Example

Google Search is popular partly because of its simple interface.

---

# 5. Maintainability

## Definition

Maintainability is the ease with which software can be modified after deployment.

Modifications include:

* Bug fixes
* New features
* Security updates
* Performance improvements

### Example

Well-organised code allows developers to implement new features quickly.

---

# 6. Portability

## Definition

Portability is the ability of software to run on different platforms with little or no modification.

### Example

Java applications can run on Windows, Linux, and macOS using the Java Virtual Machine (JVM).

---

# 7. Scalability

## Definition

Scalability is the ability of software to handle increasing workloads without significant performance degradation.

### Example

An e-commerce platform should continue to perform well during a major sale when millions of users access it simultaneously.

---

# 8. Security

## Definition

Security protects software and its data from unauthorised access and attacks.

Security includes:

* Authentication
* Authorisation
* Encryption
* Secure coding
* Data protection

### Example

Online banking applications use encryption and multi-factor authentication to protect user accounts.

---

# 9. Availability

## Definition

Availability is the percentage of time software remains operational and accessible.

### Example

Cloud services often target **99.9%** or higher uptime.

---

# 10. Flexibility

## Definition

Flexibility is the ease with which software can adapt to changing business requirements.

### Example

Adding a new payment method to an online shopping application.

---

# 11. Reusability

## Definition

Reusability means software components can be used in multiple projects.

### Example

Authentication libraries can be reused across several applications.

---

# 12. Testability

## Definition

Testability is the ease of verifying that software behaves correctly.

Good software is easier to:

* Unit test
* Integration test
* Automate

---

# Summary of Quality Attributes

| Attribute       | Meaning                      |
| --------------- | ---------------------------- |
| Correctness     | Meets requirements correctly |
| Reliability     | Works consistently           |
| Efficiency      | Uses resources effectively   |
| Usability       | Easy to use                  |
| Maintainability | Easy to modify               |
| Portability     | Runs on multiple platforms   |
| Scalability     | Handles growth               |
| Security        | Protects data                |
| Availability    | Remains operational          |
| Flexibility     | Adapts to change             |
| Reusability     | Components can be reused     |
| Testability     | Easy to test                 |

---

# What are Software Myths?

Software myths are **incorrect assumptions** that lead to poor software quality.

They are classified into:

* Customer Myths
* Management Myths
* Practitioner (Developer) Myths

---

# Customer Myths

### Myth

> "We only have a rough idea. Start coding."

### Reality

Good software begins with **clear requirements**.

**Quality attributes affected:**

* Correctness
* Maintainability
* Reliability

---

### Myth

> "Requirements can change anytime without affecting the project."

### Reality

Requirement changes impact:

* Cost
* Time
* Testing
* Design

**Quality attributes affected:**

* Flexibility
* Maintainability

---

### Myth

> "Software is finished after deployment."

### Reality

Software requires:

* Maintenance
* Security updates
* Feature additions

**Quality attributes affected:**

* Reliability
* Security
* Availability

---

# Management Myths

### Myth

> "Adding more developers will finish the project faster."

### Reality

New developers require onboarding and increase communication overhead (**Brooks's Law**).

**Quality attributes affected:**

* Reliability
* Maintainability

---

### Myth

> "Modern tools automatically guarantee quality."

### Reality

Tools improve productivity, but quality still depends on:

* Good requirements
* Good design
* Testing
* Skilled developers

**Quality attributes affected:**

* All quality attributes

---

### Myth

> "Once a project plan is created, it never changes."

### Reality

Plans evolve as requirements, risks, and technical challenges change.

**Quality attributes affected:**

* Flexibility
* Scalability

---

# Practitioner (Developer) Myths

### Myth

> "If the code runs, my work is complete."

### Reality

Professional software also requires:

* Documentation
* Testing
* Security
* Maintainability

**Quality attributes affected:**

* Maintainability
* Reliability
* Security

---

### Myth

> "Only source code matters."

### Reality

Software products also include:

* Documentation
* Tests
* Deployment scripts
* Configuration

**Quality attributes affected:**

* Maintainability
* Testability

---

### Myth

> "Testing happens after coding."

### Reality

Quality should be built throughout the development lifecycle.

**Quality attributes affected:**

* Reliability
* Correctness
* Security

---

### Myth

> "Writing code faster makes me a better developer."

### Reality

Good engineers prioritise:

* Readability
* Simplicity
* Maintainability
* Testability

---

# Relationship Between Myths and Quality

| Software Myth                  | Quality Attribute Affected |
| ------------------------------ | -------------------------- |
| Unclear requirements           | Correctness                |
| Frequent uncontrolled changes  | Maintainability            |
| No testing                     | Reliability                |
| No documentation               | Maintainability            |
| Only code matters              | Testability                |
| Security is added later        | Security                   |
| Software ends after deployment | Availability               |
| Tools solve everything         | Overall quality            |

---

# How Software Engineering Solves These Problems

| Problem               | Solution                |
| --------------------- | ----------------------- |
| Poor requirements     | Requirement Engineering |
| Lack of planning      | SDLC                    |
| Poor communication    | Agile & Scrum           |
| Low quality           | Software Testing        |
| Security issues       | Secure SDLC             |
| Difficult maintenance | Modular Design          |
| Frequent bugs         | Code Reviews & CI/CD    |
| Technical debt        | Refactoring             |

---

# Real-World Example

## Internet Banking Application

A good banking application should be:

* Correct
* Reliable
* Secure
* Available
* Efficient
* Maintainable
* Scalable

Now imagine the team believes:

> "Testing can wait until the end."

The result could include:

* Incorrect balance calculations
* Security vulnerabilities
* System crashes
* Poor customer experience

This illustrates how software myths directly undermine software quality.

---

# Interview Questions

## What are software quality attributes?

Software quality attributes are characteristics such as correctness, reliability, security, maintainability, usability, and scalability that determine how well software satisfies user needs and performs in real-world conditions.

---

## What are software myths?

Software myths are false assumptions made by customers, managers, or developers that negatively affect software quality and project success.

---

## How are software myths related to software quality?

Software myths encourage poor practices—for example, skipping requirement analysis or testing—which directly reduce quality attributes like correctness, reliability, maintainability, and security.

---

## Which quality attributes are most important in modern software?

The priority depends on the application, but commonly emphasised attributes include:

* Reliability
* Security
* Maintainability
* Scalability
* Availability
* Usability

---

# Summary

High-quality software is not defined only by correct functionality—it must also be reliable, secure, maintainable, scalable, usable, and available. Achieving these attributes requires disciplined software engineering practices. Software myths, on the other hand, create unrealistic expectations and poor development practices that reduce software quality. By understanding both concepts together, software engineers can build systems that are not only functional but also robust, maintainable, and successful throughout their lifecycle.

---

# Key Takeaways

* **Software Quality Attributes** define the characteristics of good software.
* **Software Myths** are false beliefs that hinder achieving those characteristics.
* Quality is built throughout the SDLC—not just during testing.
* Modern software engineering practices such as requirement engineering, Agile, code reviews, testing, and CI/CD help teams avoid myths and improve software quality.
* **Remember this interview formula:**

```text
Software Myths
        ↓
Bad Development Practices
        ↓
Poor Software Quality
        ↓
Software Engineering Practices
        ↓
High-Quality Software
```
