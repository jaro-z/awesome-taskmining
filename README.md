# Awesome Task Mining

> A curated list of task mining tools, research, and resources.

Created and maintained by the co-founders of [MemoryLane](https://trymemorylane.com), an SMB- and mid-segment-focused task mining tool.

Task mining records how people work on their computers (clicks, keystrokes, app switches) to surface patterns, bottlenecks, and automation opportunities. Process mining reads system logs. Task mining covers what happens between those logs, on the desktop.

## Contents

- [Task Mining vs Process Mining](#task-mining-vs-process-mining)
- [Commercial Tools](#commercial-tools)
- [Open Source and Free Tools](#open-source-and-free-tools)
- [Research Papers](#research-papers)
- [Articles and Guides](#articles-and-guides)
- [Communities](#communities)
- [Related Lists](#related-lists)

## Task Mining vs Process Mining

| | Process Mining | Task Mining |
|---|---|---|
| **Data source** | System event logs (SAP, Salesforce, ServiceNow) | Desktop activity (clicks, keystrokes, screenshots) |
| **Granularity** | System-level ("order created") | Click-level ("copied cell B7, pasted into SAP field X") |
| **Scope** | End-to-end workflows across departments | Individual tasks on the desktop |
| **Finds** | Bottlenecks, deviations, compliance gaps | Manual workarounds, repetitive steps, automation candidates |
| **Setup** | Backend database access, 3-18 months | Desktop agent install, 2-8 weeks |
| **Blind spot** | What happens between system transactions | End-to-end process context |

Process mining shows *where* the problem is. Task mining shows *why*.

## Commercial Tools

### Enterprise Platforms

- [Celonis Task Mining](https://www.celonis.com/insights/topics/what-is-task-mining) - Maps desktop interactions to the Celonis process data model. Premium add-on.
- [UiPath Task Mining](https://www.uipath.com/product/task-mining) - Records desktop activity and ranks automation opportunities by ROI.
- [SAP Signavio Task Mining](https://www.signavio.com/wiki/process-discovery/task-mining/) - Desktop capture integrated with SAP Signavio Process Intelligence.
- [Microsoft Power Automate Process Mining](https://learn.microsoft.com/en-us/power-automate/process-mining-overview) - Desktop agent and Chrome extension. Built on Minit (acquired 2022).
- [IBM Process Mining](https://www.ibm.com/products/process-mining) - Desktop agent and Chrome extension. Built on myInvenio (acquired 2021).
- [ABBYY Timeline](https://www.abbyy.com/timeline/) - Process and task mining combined with document intelligence.
- [Skan.ai](https://www.skan.ai/platform) - Always-on screen observation with AI context graphs. No integrations needed.
- [EdgeVerve AssistEdge Discover](https://www.edgeverve.com/assistedge/assistedge-discover/) - Task mining from Infosys subsidiary.
- [Nintex Process Discovery](https://www.nintex.com/learn/process-management/what-is-process-discovery/) - Discovery robots that export to Nintex RPA Studio. Built on Kryon (acquired 2022).
- [Mimica](https://www.mimica.ai/) - AI-driven automation discovery. In Gartner's 2025 Market Guide for Task Mining Tools.
- [Worktrace](https://www.worktrace.ai/) - Desktop activity analytics for knowledge workers.
- [Fluency](https://usefluency.com/) - Task mining and process capture for enterprise automation.
- [Soroco Scout](https://www.soroco.com/) - Work graph platform that maps how work gets done across teams.
- [Kyp.ai](https://kyp.ai/) - Desktop activity intelligence platform.

### Mid-Segment Platforms

- [Paxray](https://paxray.com/) - Real-time desktop activity capture. Made in Germany.
- [MemoryLane](https://trymemorylane.com) - Privacy-first task mining. Runs locally, no cloud required.

## Open Source and Free Tools

- [SmartRPA](https://github.com/bpm-diag/smartRPA) - Records desktop interactions and mines RPA-ready routines. Sapienza University of Rome. Python.
- [ActivityWatch](https://activitywatch.net/) - Open-source time tracker. Local-only, privacy-first.
- [PM4Py](https://github.com/process-intelligence-solutions/pm4py) - Python process mining library for analyzing UI logs and event data.
- [RPA-US Tools](https://github.com/RPA-US) - University of Seville tools for UI interaction recording, ScreenRPA, and UI log generation.

## Research Papers

- [Robotic Process Mining (Springer, 2022)](https://link.springer.com/chapter/10.1007/978-3-031-08848-3_16) - Using UI logs to discover automatable routines.
- [Identifying Candidate Routines for RPA from Unsegmented UI Logs (Leno et al., 2020)](https://arxiv.org/abs/2008.05782) - Finding automatable routines in noisy desktop interaction logs. ICPM 2020.
- [A Reference Data Model for Process-Related User Interaction Logs (Abb & Rehse, 2022)](https://arxiv.org/abs/2207.12054) - Proposed standard for UI log data.
- [Applications and Challenges of Task Mining (Mayr, Herm et al., ECIS 2022)](https://aisel.aisnet.org/ecis2022_rip/55/) - Literature review of task mining applications and challenges.
- [Democratizing Robotic Process Mining (2024)](https://link.springer.com/chapter/10.1007/978-3-031-70445-1_12) - Connecting user actions, task abstractions, and RPA bot generation.
- [Process Mining: Data Science in Action (van der Aalst, 2016)](https://link.springer.com/book/10.1007/978-3-662-49851-4) - The foundational process mining textbook.

## Articles and Guides

- [IBM: What is Task Mining?](https://www.ibm.com/think/topics/task-mining) - Vendor-neutral overview.
- [Gartner: Market Guide for Task Mining Tools (2025)](https://www.gartner.com/en/documents/6403875) - Market definition and vendor evaluation.

## Communities

- [UiPath Forum, Task Mining](https://forum.uipath.com/c/build/task-mining/134) - Dedicated task mining category.
- [r/processmining](https://reddit.com/r/processmining) - Process and task mining subreddit.
- [r/rpa](https://reddit.com/r/rpa) - RPA subreddit, task mining topics come up regularly.

## Related Lists

- [awesome-processmining](https://github.com/TheWoops/awesome-processmining) - Process mining resources.

---

## Contributing

Contributions welcome! Read the [contributing guidelines](CONTRIBUTING.md) first.
