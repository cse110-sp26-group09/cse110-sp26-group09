# Meeting Minutes – Akatsuki 4/26

**Team Number:** Group 09  
**Team Name:** Akatsuki  
**Meeting Type:** General weekly meeting  
**Date:** 4/26/26  
**Start Time:** 5:00 PM  
**End Time:** 5:43 PM  
**Location:** Zoom  
**Recorded By:** Hemendra Ande  
---

## 1. Attendance

### Members Present

- Alexis Navarette  
- Daniel Wu  
- Jason Nguyen  
- Hemendra Ande  
- James Villanueva  
- Woosik Kim  
- Aditya Jadhav  

### Members Absent

- Fahad Majidi  
- Hieu Le  
- Josh Victoria  
- Waleed Alghaithi  

---

## 2. Meeting Purpose
The purpose of this meeting is to discuss the logistics of the quarter-long project.
---

## 3. Agenda
- Look through the project guidelines and understand what needs to be done  
- Learn what the deliverables are  
---

## 4. Old Business
- None  
---

## 5. New Business

### Topic 1: Project

**Summary:**

- DANIEL IS READING THROUGH THE PDF, AND WE TAKE NOTES AND WORK THROUGH IT TOGETHER  
- End-to-end testing: “a methodology that validates an entire software application's workflow from start to finish, including databases, networks, APIs, and user interfaces, to ensure all components function together as expected.” HUMAN-DONE  
- Unit Testing: “a software testing method where individual, isolated components of source code, such as functions, methods, or classes, are tested to ensure they function correctly.”  
- Structures to commits. Our commit history must be clean  
- Robots.txt: A file that is… “a plain text file placed in a website's root directory that instructs web crawlers (bots) which pages or sections they should not crawl. It acts as a gatekeeper, helping manage server load and prevent irrelevant content from being indexed, but it is not a tool to prevent page indexing, as robots can ignore it.“
- No frameworks  
- MADR: Markdown Architectural Decision Records (template-based way to document decisions)
-- provides a structured markdown format, available in full, minimal, or bare formats, to capture the context, options, and consequences of design choices in a lightweight, version-controllable manner 
- PROCESS OVER PRODUCT  
- We cannot use frameworks 
- Ask Audria what kind of dependencies we can use  
- Ask Audria if the three meetings per week need all of us to be there  
- Personas, research, wire frame (storyboard for application)  
- Week 9: look at the other team's project, give feedback  
- Prompt: Create software that detects other software  
- Meet 3 times a week  
---

### Topic 2: [CI/CD pipeline]([url](https://www.redhat.com/en/topics/devops/what-cicd-pipeline))

**Summary:**
- Source control: Code is stored and managed in a version control system like Git
- Build stage: Code is compiled, and dependencies are installed to create a runnable version
- Test stage: Automated tests run to check for bugs and correctness
- Continuous integration: Code changes are frequently merged and validated automatically
- Artifact storage: Built outputs like binaries or Docker images are saved for later use
- Continuous delivery: Code is prepared and validated for release to production
- Continuous deployment: Approved changes are automatically deployed to production
- Deployment stage: Application is pushed to target environments like dev, staging, or prod
- Infrastructure as code: Infrastructure is defined and managed through code instead of manual setup
- Monitoring and logging: System performance and errors are tracked after deployment
- Feedback loop: Insights from monitoring and users are used to improve the system
---

### Topic 3: Security

**Summary:**
- Our code and application need to be clean and safe  
- Hackers can exploit things like AI systems because of hallucinations  
- Follow good practices:
  - branches  
  - issues  
  - secure coding  
- Backend is very big (API calls)  
- Documentation is very, very important  
---

### Topic 4: Sprint

**Summary:**
- Our client is TA  
- Nothing really deliverable right now  
- We need to research before doing actual things  
---

### Topic 5: [Dev Sec Ops]([url](https://www.redhat.com/en/topics/devops/what-is-devsecops#:~:text=DevSecOps%20stands%20for%20development%2C%20security%2C%20and%20operations.,shared%20responsibility%20throughout%20the%20entire%20IT%20lifecycle)) 

**Summary:**

- Source control: Code and security configurations are stored and tracked in version control systems
- Secure coding: Developers follow practices to avoid vulnerabilities while writing code
- Build stage: Code is compiled with security checks and dependency validation
- Static application security testing: Code is scanned for vulnerabilities without running it
- Dynamic application security testing: Running the application tests for security issues
- Dependency scanning: External libraries are checked for known vulnerabilities
- Continuous integration: Code changes are automatically built, tested, and security-validated
- Artifact security: Built artifacts are scanned and stored securely
- Infrastructure as code security: Infrastructure definitions are checked for misconfigurations
- Continuous deployment: Secure and approved builds are deployed automatically or with approval
- Runtime security monitoring: Applications and systems are monitored for active threats
- Logging and incident response: Security events are logged and used to detect and respond to attacks
- Feedback loop: Security findings are fed back into development to improve future code
---

### Topic 6: Lab 4

**Summary:**
- This lab is ROUGHHHHH  
- Spend a good amount of time on this  
- 5–8 hours  
- JavaScript maxxing  
---

## 6. Decisions Made
- None  
---

## 7. Items Not Discussed / Deferred
- None  
---

## 8. Action Items
| Task                          | Assigned To | Due Date | Notes                                   |
|-------------------------------|------------|----------|-----------------------------------------|
| PostHog Research + Dev Sec Ops | Team       | ASAP     | Start gathering ideas and references    |
| GitHub Repo                  | Team Leads | ASAP     | Set up the repo for the project         |
---

## 9. Next Meeting

- **Date:** 05/01/2026  
- **Time:** 2:00 PM  
- **Location:** Geisel  

**Planned Topics:**
- Project brainstorm meeting  
---

## 10. Meeting Adjournment
Meeting concluded at 5:43 PM.
