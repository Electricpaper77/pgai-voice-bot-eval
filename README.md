\# Pretty Good AI - Voice Bot Evaluation Assessment



This repository contains the infrastructure, execution scripts, and evidence for the automated red-teaming and latency evaluation of the Athena clinical voice agent.



\## 📊 Executive Summary



| Deliverable | File / Link | Description |

| :--- | :--- | :--- |

| \*\*Execution Engine\*\* | \[`bot.py`](./bot.py) | Python script automating outbound calls to the target agent using Twilio/Bland AI. |

| \*\*Architecture Specs\*\* | \[`ARCHITECTURE.md`](./ARCHITECTURE.md) | Breakdown of the STT/TTS pipeline, latency budgets, and security boundaries. |

| \*\*Triage \& Bug Report\*\* | \[`BUG\_REPORT.md`](./BUG\_REPORT.md) | P0-P3 severity matrix mapping turn-taking failures and prompt adherence. |

| \*\*Call Evidence\*\* | \[`/evidence`](./evidence) | Contains raw audio recordings and JSONL transcripts of the 10 evaluation calls. |



\## 🚀 Quick Start



1\. Clone the repository:

&#x20;  ```bash

&#x20;  git clone \[https://github.com/Electricpaper77/pgai-voice-bot-eval.git](https://github.com/Electricpaper77/pgai-voice-bot-eval.git)

