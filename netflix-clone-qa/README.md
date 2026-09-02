# Netflix Clone — Manual QA Testing Project

A full manual QA project simulating real-world software testing on a live web application ([Netflix Clone](https://netflix-clone-three-blond.vercel.app/)), managed end-to-end in Jira using industry-standard QA processes: test planning, test case design, execution tracking, and defect management.

---

## 📋 Project Overview

This project demonstrates a complete manual QA workflow applied to a Netflix clone application. The goal was to plan, design, and execute a structured test effort the way a QA analyst would on a real product team — from requirements and traceability through to a final QA report.

**Application under test:** [netflix-clone-three-blond.vercel.app](https://netflix-clone-three-blond.vercel.app/)
**Test management tool:** Jira (Team-managed software project — `NCQA`)
**Role simulated:** Manual QA Analyst

---

## 🎯 Scope & Test Approach

The project was broken into 6 QA Epics, each covering a core functional area of the application:

| Epic | Focus Area |
|---|---|
| 01 – Project Planning & Requirements | Defining scope, requirements, and traceability |
| 02 – Test Planning & Strategy | Smoke and regression test strategy |
| 03 – Test Scenarios & Test Cases | Writing detailed test cases per feature |
| 04 – Test Execution & Evidence | Running tests and logging evidence |
| Defect Management | Bug lifecycle: identification → triage → resolution |
| Video Playback | Feature-specific testing for media playback |

**Approach used:**
- **Requirements & Traceability** — mapped each test case back to a functional requirement to ensure full coverage
- **Smoke Testing** — a lightweight pass to confirm core functionality works before deeper testing
- **Regression Testing** — re-verifying existing functionality after changes or fixes
- **Defect Management Process** — a defined workflow for logging, triaging, and tracking bugs through to resolution

---

## ✅ Test Cases

**65 test cases** were written across 6 functional Stories, covering areas including authentication, browsing/navigation, search, video playback, and responsive design.

Each test case follows a standard structure:
- Test case ID
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Pass/Fail status

> 📌 *Full test case list is tracked in Jira. See [screenshot below](#<img width="1595" height="764" alt="JIRA Board " src="https://github.com/user-attachments/assets/389b21a0-dc25-4137-9d88-eb151501035a" />
) or [view the board](https://zaynabaudu2.atlassian.net/jira/software/projects/NCQA/boards/34?filter=&groupBy=none&atlOrigin=eyJpIjoiNDNlMGUxZjMwMjE5NDU2YzgwOWE4MjA5MjMwMTRkNGEiLCJwIjoiaiJ9) for the complete set.*

---

## 🐞 Bugs Found

| ID | Summary | Severity | Status |
|---|---|---|---|
| — | *<img width="1227" height="414" alt="Error messgae2026-03-31 121402" src="https://github.com/user-attachments/assets/9cdf229f-ddea-46a7-b03d-7dff8498a15a" />
* | Medium | To Do |
| — | *<img width="1128" height="541" alt="NETFLIXCLONESCREENSHOT " src="https://github.com/user-attachments/assets/f178b9ba-157a-4c3c-9498-cef08ac3bf51" />
* | Low | To Do |

Two defects were identified and logged during test execution, each documented with steps to reproduce, expected vs. actual behavior, and severity classification, following the project's defect-management process.



![Jira Board](
![Test Case List]()
![Bug Report Example]()

---

## 🛠️ Tools Used

- **Jira** — test planning, test case management, execution tracking, and defect management
- **Chrome DevTools** — responsive/device testing and inspection
- **GitHub** — project documentation and portfolio presentation

---

## 📊 Summary

| Metric | Count |
|---|---|
| Epics | 6 |
| Stories | 6 |
| Test Cases | 65 |
| Bugs Logged | 2 |
| Test Plans (Smoke, Regression, Requirements, Final Report) | 4 |

This project reflects a realistic QA lifecycle: from requirements and planning, through test design and execution, to defect tracking and reporting — all managed in Jira and documented here for portfolio review.
