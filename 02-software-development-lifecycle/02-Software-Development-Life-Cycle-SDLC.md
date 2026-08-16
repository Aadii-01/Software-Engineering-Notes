# 02. Software Development Life Cycle (SDLC)

## 1. SDLC Overview

**Software Development Life Cycle (SDLC)** is a systematic process used to develop, deliver, and maintain software systems.

It defines a structured sequence of activities that software teams follow from the initial idea or problem identification to the final deployment and maintenance of the software.

The primary goals of SDLC are to:

- Develop high-quality software.
- Clearly understand and document requirements.
- Complete projects within the planned time and budget.
- Reduce development risks.
- Improve software reliability and maintainability.
- Ensure that the final product satisfies user and business requirements.

### Basic SDLC Flow

```text
Planning
   ↓
Feasibility Study
   ↓
Requirement Gathering
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

SDLC is not necessarily a strictly linear process. Modern development methodologies such as Agile perform many of these activities repeatedly in short iterations.

---

# 2. Phases of SDLC

The major phases covered in a typical SDLC are:

1. Feasibility Study
2. Requirement Gathering
3. Design
4. Development
5. Testing
6. Deployment
7. Maintenance

Each phase has specific objectives, activities, and deliverables.

| Phase | Main Purpose | Major Output |
|---|---|---|
| Feasibility Study | Determine whether the project is practical | Feasibility Report |
| Requirement Gathering | Understand what the system must do | Requirements / SRS |
| Design | Decide how the system will be built | Design Documents |
| Development | Implement the system | Source Code |
| Testing | Find defects and verify requirements | Test Reports |
| Deployment | Release the system to users | Production System |
| Maintenance | Keep the system operational and improved | Updates / Fixes |

---

# 3. Feasibility Study

A **Feasibility Study** is performed to determine whether a proposed software project is technically, economically, operationally, and practically achievable.

It helps stakeholders make a **go/no-go decision** before significant development resources are invested.

## Objectives

The main objectives are:

- Determine whether the proposed system is technically possible.
- Estimate project costs.
- Identify expected benefits.
- Determine whether the organization can operate the system.
- Identify major risks and constraints.
- Determine whether the project can be completed within the required schedule.
- Evaluate alternative solutions.

## Types of Feasibility

### 3.1 Technical Feasibility

Determines whether the required technology, infrastructure, tools, and technical expertise are available.

Questions include:

- Do we have the required hardware?
- Is the required software or technology available?
- Does the team have the necessary skills?
- Can the system meet performance and scalability requirements?
- Can it integrate with existing systems?

### 3.2 Economic Feasibility

Determines whether the expected benefits justify the project costs.

It considers:

- Development costs
- Hardware costs
- Software and licensing costs
- Cloud infrastructure costs
- Training costs
- Maintenance costs
- Expected financial benefits

### 3.3 Operational Feasibility

Determines whether the proposed system can be successfully used within the organization.

It considers:

- User acceptance
- Existing business processes
- Employee training
- Organizational changes
- Management support

### 3.4 Schedule Feasibility

Determines whether the project can be completed within the required timeframe.

It considers:

- Available development resources
- Project deadlines
- Development complexity
- Dependencies
- Testing time
- Deployment requirements

### 3.5 Legal Feasibility

Determines whether the system complies with applicable laws, regulations, contracts, licenses, and organizational policies.

Examples include:

- Data protection requirements
- Software licensing
- Intellectual property
- Industry regulations
- Security and compliance requirements

---

# 4. Cost-Benefit Analysis

**Cost-Benefit Analysis (CBA)** compares the expected costs of developing and operating a system with its expected benefits.

It helps determine whether a project is financially worthwhile.

## Costs

Typical software project costs include:

- Developer salaries
- Hardware
- Software licenses
- Cloud infrastructure
- Database services
- Training
- Testing
- Security
- Maintenance
- Technical support

## Benefits

Potential benefits include:

- Increased revenue
- Reduced operational costs
- Reduced manual work
- Improved productivity
- Improved customer experience
- Faster decision-making
- Reduced errors

## Basic Formula

```text
Net Benefit = Total Benefits − Total Costs
```

For example:

```text
Total Benefits = ₹12,00,000
Total Costs    = ₹7,00,000

Net Benefit = ₹12,00,000 − ₹7,00,000
            = ₹5,00,000
```

A project with positive net benefits may be financially attractive, although real-world decisions should also consider risk, uncertainty, time value of money, and non-financial benefits.

## ROI

**Return on Investment (ROI)** can be used to evaluate the financial attractiveness of a project.

```text
ROI = (Net Benefit / Total Cost) × 100
```

For the above example:

```text
ROI = (₹5,00,000 / ₹7,00,000) × 100
    ≈ 71.43%
```

---

# 5. Requirement Gathering

**Requirement Gathering** is the process of identifying, understanding, documenting, and validating what users and stakeholders expect from the software.

It answers the fundamental question:

> **What should the system do?**

## Sources of Requirements

Requirements can be collected from:

- Customers
- End users
- Managers
- Domain experts
- Existing documentation
- Existing software systems
- Business processes
- Regulatory requirements

## Requirement Gathering Techniques

### Interviews

Developers or analysts directly communicate with stakeholders to understand their needs.

### Questionnaires

Structured questions are distributed to multiple users to collect information efficiently.

### Observation

Analysts observe users performing their actual tasks to identify requirements.

### Workshops

Stakeholders and development teams collaborate in structured sessions to identify and prioritize requirements.

### Document Analysis

Existing documentation, reports, manuals, and systems are analyzed.

### Prototyping

A basic version of the system is created to help users visualize the proposed functionality and provide feedback.

## Types of Requirements

### Functional Requirements

Describe **what the system should do**.

Examples:

- User can create an account.
- User can log in.
- Administrator can delete users.
- System can generate reports.

### Non-Functional Requirements

Describe **how well the system should operate**.

Examples:

- Performance
- Security
- Reliability
- Availability
- Scalability
- Usability
- Maintainability

Example:

> The system shall return search results within 2 seconds for 95% of requests under normal operating conditions.

## Requirements Documentation

Requirements are generally documented in an **SRS (Software Requirements Specification)** document.

The SRS acts as a reference for:

- Developers
- Testers
- Project managers
- Customers
- Other stakeholders

---

# 6. Design

The **Design phase** converts requirements into a technical blueprint for building the software.

It answers:

> **How will the system be built?**

## Major Design Activities

### System Architecture

Defines the overall structure of the system.

For example:

```text
Client
  ↓
Frontend
  ↓
Backend / API
  ↓
Database
```

### Database Design

Defines:

- Tables
- Relationships
- Primary keys
- Foreign keys
- Indexes
- Constraints

### User Interface Design

Defines:

- Screens
- Navigation
- Forms
- User interactions
- Layout

### API Design

Defines:

- Endpoints
- HTTP methods
- Request formats
- Response formats
- Authentication
- Error handling

### Security Design

Considers:

- Authentication
- Authorization
- Encryption
- Secure data storage
- Input validation
- Access control

## Design Levels

### High-Level Design (HLD)

Describes the overall system architecture and major components.

### Low-Level Design (LLD)

Describes the internal implementation details of individual modules or components.

## Design Output

Typical outputs include:

- Architecture diagrams
- Database schema
- ER diagrams
- API specifications
- UI designs
- Module designs
- Security architecture

---

# 7. Development

The **Development phase** involves converting the approved design into working software.

Developers write source code according to the requirements and design specifications.

## Major Activities

- Setting up the development environment.
- Creating project structure.
- Writing source code.
- Implementing business logic.
- Creating database components.
- Implementing APIs.
- Developing the frontend.
- Integrating components.
- Performing code reviews.
- Managing source code with version control.

## Version Control

Tools such as Git help developers:

- Track code changes.
- Create branches.
- Collaborate with team members.
- Review changes.
- Revert problematic changes.
- Maintain project history.

## Coding Standards

Development teams should follow:

- Naming conventions
- Code formatting
- Documentation standards
- Error-handling practices
- Security practices
- Testing practices

## Development Output

The primary output is:

```text
Source Code
+
Build Artifacts
+
Configuration
```

---

# 8. Testing

The **Testing phase** verifies that the software works correctly and satisfies the specified requirements.

The primary objectives are to:

- Find defects.
- Verify functionality.
- Validate requirements.
- Check system reliability.
- Ensure acceptable performance.
- Verify security and usability.

## Levels of Testing

### Unit Testing

Tests individual functions, methods, or components.

Example:

```text
Test calculateTotal()
```

### Integration Testing

Tests whether multiple components work correctly together.

Example:

```text
Frontend → API → Database
```

### System Testing

Tests the complete integrated software system.

### Acceptance Testing

Determines whether the system satisfies business and user requirements.

It is often performed with or on behalf of the customer or business stakeholders.

## Other Types of Testing

### Regression Testing

Ensures that new changes have not broken existing functionality.

### Performance Testing

Evaluates:

- Response time
- Throughput
- Resource utilization
- Scalability

### Security Testing

Identifies vulnerabilities and verifies security controls.

### Usability Testing

Evaluates how easily users can understand and use the system.

## Testing Process

```text
Test Planning
     ↓
Test Case Creation
     ↓
Test Execution
     ↓
Defect Identification
     ↓
Bug Fixing
     ↓
Retesting
     ↓
Regression Testing
     ↓
Test Completion
```

---

# 9. Deployment

**Deployment** is the process of making the completed and tested software available in its target environment.

The target environment may be:

- Local infrastructure
- Cloud infrastructure
- Enterprise data center
- Mobile application store
- Web hosting environment

## Deployment Activities

- Configure production infrastructure.
- Configure databases.
- Deploy application components.
- Configure environment variables.
- Set up networking.
- Configure security.
- Migrate data if required.
- Perform final validation.
- Enable monitoring and logging.

## Deployment Strategies

### Big Bang Deployment

The entire system is deployed at once.

### Rolling Deployment

New versions are gradually deployed across servers or instances.

### Blue-Green Deployment

Two environments are maintained:

```text
Blue  → Current Production
Green → New Version
```

Traffic can be switched from the old version to the new version after validation.

### Canary Deployment

The new version is initially released to a small percentage of users before being expanded to everyone.

## Deployment Output

The main output is:

> **A working production system available to its intended users.**

---

# 10. Maintenance

**Maintenance** begins after the software has been deployed.

The goal is to keep the system reliable, secure, compatible, and useful throughout its lifetime.

## Types of Maintenance

### Corrective Maintenance

Fixes defects discovered after deployment.

Example:

```text
Bug in payment calculation
        ↓
Identify issue
        ↓
Fix code
        ↓
Test
        ↓
Deploy update
```

### Adaptive Maintenance

Modifies software to work with changes in its environment.

Examples:

- New operating system
- New database version
- New browser
- New external API

### Perfective Maintenance

Improves existing functionality or performance.

Examples:

- Improving UI.
- Optimizing database queries.
- Adding useful features.
- Improving response time.

### Preventive Maintenance

Makes changes that reduce the likelihood of future problems.

Examples:

- Refactoring code.
- Updating dependencies.
- Improving documentation.
- Strengthening security.
- Improving test coverage.

---

# 11. Complete SDLC Flow

The complete process can be summarized as:

```text
              ┌─────────────────────┐
              │   Feasibility Study │
              └──────────┬──────────┘
                         ↓
              ┌─────────────────────┐
              │ Requirement         │
              │ Gathering           │
              └──────────┬──────────┘
                         ↓
              ┌─────────────────────┐
              │       Design        │
              └──────────┬──────────┘
                         ↓
              ┌─────────────────────┐
              │    Development      │
              └──────────┬──────────┘
                         ↓
              ┌─────────────────────┐
              │      Testing        │
              └──────────┬──────────┘
                         ↓
              ┌─────────────────────┐
              │     Deployment      │
              └──────────┬──────────┘
                         ↓
              ┌─────────────────────┐
              │    Maintenance      │
              └──────────┬──────────┘
                         │
                         └──────→ Continuous Improvement
```

---

# 12. Quick Revision

| Topic | Key Point |
|---|---|
| **SDLC** | Structured process for developing and maintaining software |
| **Feasibility Study** | Determines whether the project is practical |
| **Cost-Benefit Analysis** | Compares expected costs and benefits |
| **Requirement Gathering** | Determines what the system must do |
| **Design** | Determines how the system will be built |
| **Development** | Converts design into working code |
| **Testing** | Finds defects and verifies requirements |
| **Deployment** | Releases software to the target environment |
| **Maintenance** | Fixes, improves, and adapts deployed software |

# 13. Key Questions for Exams and Interviews

1. What is SDLC?
2. What are the phases of SDLC?
3. Why is feasibility analysis performed?
4. What are the different types of feasibility?
5. What is cost-benefit analysis?
6. What is the difference between functional and non-functional requirements?
7. What is an SRS?
8. What is the difference between HLD and LLD?
9. What are the different levels of software testing?
10. What is deployment?
11. What are the different deployment strategies?
12. What are the four types of software maintenance?
13. What is corrective maintenance?
14. What is adaptive maintenance?
15. What is perfective maintenance?
16. What is preventive maintenance?

# 14. Summary

The **Software Development Life Cycle (SDLC)** provides a systematic framework for developing software.

The major stages are:

```text
Feasibility
    ↓
Requirement Gathering
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

Each phase has a specific purpose. Feasibility determines whether the project is worth pursuing, requirements define what needs to be built, design determines how it will be built, development implements it, testing verifies it, deployment delivers it to users, and maintenance keeps it functional and improves it over time.

A well-managed SDLC helps teams deliver software that is **reliable, maintainable, cost-effective, secure, and aligned with user requirements**.