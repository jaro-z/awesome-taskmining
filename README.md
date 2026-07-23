# Awesome Task Mining [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of task mining tools, research, and resources.

Created and maintained by the co-founders of [MemoryLane](https://trymemorylane.com).

Task mining watches how people actually work on their computers (clicks, keystrokes, app switches) and finds patterns, bottlenecks, and automation opportunities. It's the missing piece between process mining (which reads system logs) and real life (which happens on desktops).

## Contents

- [How Is Task Mining Different from Process Mining?](#how-is-task-mining-different-from-process-mining)
- [Commercial Tools](#commercial-tools)
- [Open Source and Free Tools](#open-source-and-free-tools)
- [Research Papers](#research-papers)
- [Articles and Guides](#articles-and-guides)
- [Communities](#communities)
- [Related Lists](#related-lists)

## How Is Task Mining Different from Process Mining?

| | Process Mining | Task Mining |
|---|---|---|
| **What it reads** | System event logs (SAP, Salesforce, ServiceNow) | Desktop activity (clicks, keystrokes, screenshots) |
| **Granularity** | System-level ("order created", "invoice posted") | Click-level ("copied cell B7, pasted into SAP field X") |
| **Scope** | End-to-end workflows across departments | Individual tasks at the desktop level |
| **What it finds** | Bottlenecks, deviations, compliance gaps in the process flow | Manual workarounds, repetitive steps, automation candidates |
| **Setup** | Needs access to backend databases, 3-18 months | Desktop agent install, no backend integration, 2-8 weeks |
| **Blind spot** | Can't see what happens between system transactions | Can't see the end-to-end process context |

They work best together. Process mining tells you *where* the problem is. Task mining tells you *why*.

## Commercial Tools

### Enterprise Platforms

- [Celonis Task Mining](https://www.celonis.com/insights/topics/what-is-task-mining) - Captures desktop interactions and maps them to the Celonis process data model. Premium add-on to the Celonis platform.
- [UiPath Task Mining](https://www.uipath.com/product/task-mining) - Records employee desktop activity and ranks automation opportunities by ROI. Part of the UiPath automation platform.
- [SAP Signavio Task Mining](https://www.signavio.com/wiki/process-discovery/task-mining/) - Desktop-level capture integrated with SAP Signavio Process Intelligence.
- [Microsoft Power Automate Process Mining](https://learn.microsoft.com/en-us/power-automate/process-mining-overview) - Task mining via desktop agent and Chrome extension. Built on the Minit acquisition (2022).
- [IBM Process Mining](https://www.ibm.com/products/process-mining) - Task mining via desktop agent and Chrome extension. Built on the myInvenio acquisition (2021).
- [ABBYY Timeline](https://www.abbyy.com/timeline/) - Process and task mining with document intelligence.
- [Skan.ai](https://www.skan.ai/platform) - Always-on screen observation with AI context graphs. No integrations needed.
- [EdgeVerve AssistEdge Discover](https://www.edgeverve.com/assistedge/assistedge-discover/) - AI-first task mining from Infosys subsidiary.
- [Nintex Process Discovery](https://www.nintex.com/learn/process-management/what-is-process-discovery/) - Desktop discovery robots that export directly to Nintex RPA Studio. Built on the Kryon acquisition (2022).
- [Mimica](https://www.mimica.ai/) - AI-powered task mining focused on automation discovery. Named in Gartner's 2025 Market Guide for Task Mining Tools.
- [Worktrace](https://www.worktrace.io/) - Desktop activity analytics for understanding how knowledge workers spend their time.
- [Fluency](https://www.fluency.inc/) - Task mining and process capture for enterprise automation.
- [Soroco Scout](https://www.soroco.com/) - Work graph platform that maps how work gets done across teams.

### Mid-Segment Platforms

- [Paxray](https://paxray.com/) - German task mining platform. Captures real-time desktop activity to find inefficiencies and automation opportunities.
- [Kyp.ai](https://kyp.ai/) - Desktop activity intelligence and task mining platform.
- [MemoryLane](https://trymemorylane.com) - Privacy-first task mining for individuals and teams. Runs locally, no cloud required.

## Open Source and Free Tools

- [SmartRPA](https://github.com/bpm-diag/smartRPA) - Records desktop user interactions and mines RPA-ready routines. By Antonio Marrella's group at Sapienza University of Rome. Python-based.
- [ActivityWatch](https://activitywatch.net/) - Open-source automated time tracker. Runs locally, privacy-first. Captures the raw activity data that task mining builds on.
- [PM4Py](https://github.com/process-intelligence-solutions/pm4py) - Python process mining library. Widely used for analyzing UI logs and event data.
- [RPA-US Tools](https://github.com/RPA-US) - University of Seville research group's open-source tools for RPA and user interaction recording, including ScreenRPA and UI log generation.

## Research Papers

- [Robotic Process Mining (Springer, 2022)](https://link.springer.com/chapter/10.1007/978-3-031-08848-3_16) - Chapter in the Process Mining Handbook covering techniques that use UI logs to discover automatable routines.
- [Identifying Candidate Routines for RPA from Unsegmented UI Logs (Leno et al., 2020)](https://arxiv.org/abs/2008.05782) - How to find automatable routines in noisy desktop interaction logs. Presented at ICPM 2020.
- [A Reference Data Model for Process-Related User Interaction Logs (Abb & Rehse, 2022)](https://arxiv.org/abs/2207.12054) - Proposed standard for UI log data, bridging task mining and process mining.
- [Applications and Challenges of Task Mining: A Literature Review (Mayr, Herm et al., ECIS 2022)](https://aisel.aisnet.org/ecis2022_rip/55/) - Structured review of task mining applications and challenges.
- [Democratizing Robotic Process Mining (2024)](https://link.springer.com/chapter/10.1007/978-3-031-70445-1_12) - Framework connecting user actions, task abstractions, and RPA bot generation.
- [Process Mining: Data Science in Action (van der Aalst, 2016)](https://link.springer.com/book/10.1007/978-3-662-49851-4) - The foundational textbook on process mining.

## Articles and Guides

- [IBM: What is Task Mining?](https://www.ibm.com/think/topics/task-mining) - Vendor-neutral overview of task mining and its role in process intelligence.
- [Gartner: Market Guide for Task Mining Tools (2025)](https://www.gartner.com/en/documents/6403875) - Defines the task mining market and evaluates vendors.

## Communities

- [UiPath Forum, Task Mining](https://forum.uipath.com/c/build/task-mining/134) - Dedicated task mining category with active discussions.
- [r/processmining](https://reddit.com/r/processmining) - Small but active subreddit covering process and task mining.
- [r/rpa](https://reddit.com/r/rpa) - Broader RPA subreddit where task mining topics come up regularly.

## Related Lists

- [awesome-processmining](https://github.com/TheWoops/awesome-processmining) - Curated list of process mining resources.

---

## Contributing

Contributions welcome! Read the [contributing guidelines](CONTRIBUTING.md) first.
