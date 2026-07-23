# Awesome Task Mining

> A curated list of task mining tools, research, and resources.

Created and maintained by the co-founders of [MemoryLane](https://trymemorylane.com), a task mining tool for the mid-segment.

Task mining maps how people work on their computers (screenshots, clicks, keystrokes, app switches) to identify patterns, bottlenecks, and automation opportunities.

## Contents

- [Task vs. Process Mining](#task-mining-vs-process-mining)
- [Tools](#commercial-tools)
- [Open source resources](#open-source-and-free-tools)
- [Research](#research-papers)
- [Guides](#articles-and-guides)
- [Communities](#communities)
- [Related](#related-lists)

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

### Large Enterprises

- [Celonis](https://www.celonis.com/insights/topics/what-is-task-mining) - Maps desktop interactions to the Celonis process data model. Premium add-on.
- [UiPath](https://www.uipath.com/product/task-mining) - Records desktop activity and ranks automation opportunities by ROI.
- [SAP Signavio](https://www.signavio.com/wiki/process-discovery/task-mining/) - Desktop capture integrated with SAP Signavio Process Intelligence.
- [Microsoft Power Automate](https://learn.microsoft.com/en-us/power-automate/process-mining-overview) - Desktop agent and Chrome extension. Built on Minit (acquired 2022).
- [IBM](https://www.ibm.com/products/process-mining) - Desktop agent and Chrome extension. Built on myInvenio (acquired 2021).
- [ABBYY](https://www.abbyy.com/timeline/) - Process and task mining combined with document intelligence.
- [Skan.ai](https://www.skan.ai/platform) - Always-on screen observation with AI context graphs. No integrations needed.
- [EdgeVerve](https://www.edgeverve.com/assistedge/assistedge-discover/) - Task mining from Infosys subsidiary.
- [Nintex](https://www.nintex.com/learn/process-management/what-is-process-discovery/) - Discovery robots that export to Nintex RPA Studio. Built on Kryon (acquired 2022).
- [Mimica](https://www.mimica.ai/) - AI-driven automation discovery. In Gartner's 2025 Market Guide for Task Mining Tools.
- [Worktrace](https://www.worktrace.ai/) - Desktop activity analytics for knowledge workers.
- [Fluency](https://usefluency.com/) - Task mining and process capture for enterprise automation.
- [Soroco](https://www.soroco.com/) - Work graph platform that maps how work gets done across teams.
- [Kyp.ai](https://kyp.ai/) - Desktop activity intelligence platform.

### Mid-Segment & SMBs

- [MemoryLane](https://trymemorylane.com) - Privacy-first task mining. No large internal project required to get started.
- [Paxray](https://paxray.com/) - Real-time desktop activity capture. Made in Germany.
 
## Open Source

- [SmartRPA](https://github.com/bpm-diag/smartRPA) - Records desktop interactions and mines RPA-ready routines. University research.
- [ActivityWatch](https://activitywatch.net/) - Open-source time tracker. Local-only, privacy-first, no analytics.

## Research Papers

- [Identifying Candidate Routines for RPA from Unsegmented UI Logs (Leno et al., 2020)](https://arxiv.org/abs/2008.05782) - Extracts automatable routines from raw desktop interaction logs. ICPM 2020.
- [A Reference Data Model for Process-Related User Interaction Logs (Abb & Rehse, 2022)](https://arxiv.org/abs/2207.12054) - Proposed standard schema for UI log data.
- [Applications and Challenges of Task Mining (Mayr, Herm et al., ECIS 2022)](https://aisel.aisnet.org/ecis2022_rip/55/) - Literature review covering task mining use cases, methods, and open problems.
- [SmartRPA: Generating Software Robots from User Interface Logs (Agostinelli et al., 2025)](https://www.sciencedirect.com/science/article/pii/S2352711024003650) - Tool paper for the SmartRPA system. Records desktop actions and generates executable RPA bots. SoftwareX.
- [Assessing Reproducibility in Screenshot-Based Task Mining (Martínez-Rojas et al., 2026)](https://www.sciencedirect.com/science/article/pii/S0306437926000591) - Tests whether screenshot-based task mining yields consistent results across analysts. Information Systems.
- [Enriching UI Logs Via Screenshot-Based Activity Labeling Using Vision-Language Models (Rodríguez-Ruiz et al., 2026)](https://link.springer.com/article/10.1007/s12599-026-00990-6) - Uses VLMs to auto-label activities in UI logs from screenshots. BISE.

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
