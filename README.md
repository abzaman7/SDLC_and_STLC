# SOFTWARE DEVELOPMENT LIFE CYCLE (SDLC)

The **Software Development Life Cycle (SDLC)** is a structured process used to plan, develop, test, deploy, and maintain software applications.

It provides a systematic approach to software development, helping teams deliver high-quality software while managing requirements, resources, timelines, and risks effectively.

---

## SDLC Stages

The Software Development Life Cycle (SDLC) typically consists of the following unified stages:

* Requirement Phase
* Design Phase
* Coding Phase
* Testing Phase
* Release Phase
* Maintenance Phase

### 1. Requirement Phase

The project requirements are gathered, analyzed, and documented. The team focuses on understanding what the software should accomplish and what the stakeholders expect.

### 2. Design Phase

The requirements are transformed into a detailed software design. This may include system architecture, database design, UI/UX design, and technical specifications.

### 3. Coding Phase

Developers implement the design by writing the source code and building the required features and functionality.

### 4. Testing Phase

The developed software is systematically tested to identify defects and verify that the application meets the specified requirements.

### 5. Release Phase

After successful testing and approval, the software is deployed or released to the intended users or production environment.

### 6. Maintenance Phase

After release, the software is monitored and maintained. Defects are fixed, improvements are introduced, and the application may be updated to meet changing business or technical requirements.

---

# SOFTWARE TESTING LIFE CYCLE (STLC)

The **Software Testing Life Cycle (STLC)** is a systematic process followed by the testing team throughout the software testing activities.

STLC begins with **studying and analyzing the requirements** and continues through test planning, test execution, defect management, and reporting.

The goal of STLC is to ensure that software is thoroughly evaluated and that identified defects are properly managed before the product is released.

---

## STLC Stages

The STLC typically consists of the following stages:

* Requirement Study
* Test Planning
* Writing Test Cases
* Test Case Review
* Test Case Execution
* Bug Logging & Tracking
* Bug Re-testing
* Close or Reopen Bugs
* Results & Test Reporting

### 1. Requirement Study

The QA team reviews and analyzes the requirements to understand the expected behavior of the application.

The team identifies:

* Testable requirements
* Functional and non-functional requirements
* Testing scope
* Potential risks and ambiguities

### 2. Test Planning

A **Test Plan** is prepared based on the project requirements and testing objectives.

This phase may define:

* Testing scope and objectives
* Testing approach
* Resources and responsibilities
* Test environment
* Test schedule
* Testing tools and techniques

### 3. Writing Test Cases

Test cases are designed based on the approved requirements.

A good test case should clearly define:

* Test conditions
* Preconditions
* Test steps
* Test data
* Expected results

### 4. Test Case Review

The written test cases are reviewed to ensure they are:

* Correct
* Complete
* Clear
* Traceable to requirements
* Free from unnecessary duplication

### 5. Test Case Execution

The QA team executes the prepared test cases against the application and compares the **actual results** with the **expected results**.

Test cases are typically marked as:

* ✅ Pass
* ❌ Fail
* ⏭️ Blocked
* ⏸️ Not Executed

### 6. Bug Logging & Tracking

When a defect is identified, it is documented in a defect tracking system.

A good bug report generally includes:

* Bug title
* Description
* Steps to reproduce
* Expected result
* Actual result
* Severity
* Priority
* Environment
* Screenshots or supporting evidence

### 7. Bug Re-testing

After developers fix a reported defect, the QA team re-tests the affected functionality to verify that the defect has been resolved.

### 8. Close or Reopen Bugs

Based on the re-test result:

* If the defect is fixed successfully → **Close the bug**
* If the defect still exists → **Reopen the bug**

### 9. Results & Test Reporting

At the end of the testing cycle, the QA team prepares test results and reports.

Reports may include:

* Total test cases
* Passed test cases
* Failed test cases
* Blocked test cases
* Defects identified
* Defects resolved
* Defects remaining
* Overall test status

---

## 🔗 SDLC vs STLC

**SDLC** focuses on the **complete software development process**, from requirements through maintenance.

**STLC** focuses specifically on the **software testing process** and ensures that the product is verified and validated throughout the testing activities.

> **SDLC builds the software. STLC ensures that the software works as expected.**

## 🧑‍💻 SDLC & STLC Interview Questions

### 🔷 SDLC Interview Questions

**What is Software Development Life Cycle (SDLC)?**

SDLC is a structured process used to plan, develop, test, deploy, and maintain software applications. It ensures that software is built in a systematic and organized way to meet user requirements and quality standards.

**STLC INTERVIEW QUESTIONS**

---

### What are the main phases of SDLC?

The main phases of SDLC are:

* Requirement Phase
* Design Phase
* Coding (Development) Phase
* Testing Phase
* Release/Deployment Phase
* Maintenance Phase

---

### Why is SDLC important in software development?

SDLC is important because it provides a clear structure for development, improves software quality, reduces risks, helps manage time and cost effectively, and ensures that the final product meets user requirements.

---

### What is the difference between Waterfall and Agile SDLC models?

Waterfall is a linear and sequential model where each phase is completed before moving to the next, making it rigid and less flexible. Agile is an iterative and flexible model where development happens in small increments with continuous feedback and improvements.

---

### What happens in the requirement phase of SDLC?

In the requirement phase, all user and system requirements are gathered, analyzed, and documented. The goal is to clearly understand what the software should do and what the stakeholders expect.

---

### What is the role of the design phase in SDLC?

The design phase converts the gathered requirements into a technical blueprint. It defines system architecture, database design, user interface design, and overall system structure.

---

### What is the purpose of the testing phase in SDLC?

The testing phase is used to identify defects in the software and ensure that it works according to the specified requirements. It helps improve software quality before release.

---

### What is the difference between verification and validation in SDLC?

Verification checks whether the product is being built correctly according to requirements (static process like reviews). Validation checks whether the correct product is being built by testing the actual software (dynamic process).

---

### What is the maintenance phase in SDLC?

The maintenance phase occurs after software deployment. It involves fixing bugs, improving performance, updating features, and ensuring the software continues to function properly in changing environments.

---

### What are the advantages and disadvantages of SDLC?

**Advantages:** It provides structure, improves software quality, reduces risks, and ensures better planning and documentation.
**Disadvantages:** It can be time-consuming, costly, and less flexible in traditional models like Waterfall.

---
</br>
</br>

## 🔶 STLC Interview Questions

**What is Software Testing Life Cycle (STLC)?**
**Answer:** STLC is a systematic process followed by the testing team to plan, design, execute, and report software testing activities to ensure the quality of the software product.

---

**What are the phases of STLC?**
**Answer:** The main phases of STLC are: Requirement Analysis, Test Planning, Test Case Design, Test Case Review, Test Execution, Bug Reporting, Re-testing, and Test Closure/Reporting.

---

**How is STLC different from SDLC?**
**Answer:** SDLC is the complete software development process from requirement to maintenance, while STLC focuses only on the testing activities to ensure the software is defect-free and meets requirements.

---

**What is the purpose of requirement analysis in STLC?**
**Answer:** The purpose is to understand and analyze requirements to identify what needs to be tested, define test scope, and detect any missing or unclear requirements early.

---

**What is a test plan and why is it important?**
**Answer:** A test plan is a document that defines the testing strategy, scope, resources, schedule, and approach. It is important because it guides the entire testing process and ensures organized and efficient testing.

---

**What is the difference between test case and test scenario?**
**Answer:** A test scenario is a high-level idea of what to test, while a test case is a detailed set of steps, input data, and expected results used to validate a specific function.

---

**What is test case execution in STLC?**
**Answer:** Test case execution is the process of running test cases on the application, comparing actual results with expected results, and recording the outcomes as pass or fail.

---

**What is bug life cycle in software testing?**
**Answer:** The bug life cycle is the process a defect goes through from identification to closure, including stages like New, Assigned, Open, Fixed, Retested, Verified, and Closed.

---

**What is the difference between severity and priority?**
**Answer:** Severity indicates the impact of a defect on the system, while priority indicates how urgently the defect should be fixed.

---

**What happens after a bug is fixed in STLC?**
**Answer:** After a bug is fixed, the QA team performs re-testing to verify the fix and may also conduct regression testing to ensure no other functionality is affected.

---

**What is regression testing in STLC?**
**Answer:** Regression testing is performed to ensure that recent code changes or bug fixes have not negatively impacted existing functionality.

---

**Why is test case review important?**
**Answer:** Test case review is important to ensure test cases are accurate, complete, clear, and aligned with requirements, reducing errors during execution.

---
</br>
</br>

## SDLC vs STLC Concept Questions

---

## **1. How do SDLC and STLC work together in a project?**

SDLC and STLC work in parallel to ensure successful software development. SDLC focuses on building the software step by step, while STLC focuses on testing each part of the software to ensure it meets requirements. STLC activities are aligned with SDLC phases to detect defects early and improve quality throughout the development process.

---

## **2. At which stage of SDLC does STLC start?**

STLC starts during the **Requirement Phase** of SDLC. In this stage, the testing team analyzes requirements to understand what needs to be tested and begins planning the testing approach.

---

## **3. Can STLC exist without SDLC? Why or why not?**

No, STLC cannot exist without SDLC because testing is dependent on software development. STLC requires software requirements, design, and code produced during SDLC to perform testing activities. Without SDLC, there would be no software to validate.

---

## **4. How does testing improve the SDLC process?**

Testing improves SDLC by identifying defects early, ensuring requirements are correctly implemented, and improving overall software quality. It reduces development risks, prevents costly post-release issues, and ensures the final product meets user expectations.

---

## **5. What is the final goal of SDLC and STLC?**

The final goal of SDLC is to deliver a fully functional, reliable, and maintainable software product. The final goal of STLC is to ensure that the software is thoroughly tested, defect-free as much as possible, and meets all specified requirements before release.
