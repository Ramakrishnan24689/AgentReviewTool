# 🧠 Agent Review Tool

## Overview

**Agent Review Tool** is a Copilot agent designed to evaluate other Copilot agents by analyzing their configuration stored in Dataverse. It performs a structured, deterministic review of agent instructions, tools, and orchestration setup, and provides actionable recommendations to improve agent quality.

This Power Platform solution enables makers and architects to assess Copilot agents with clarity, consistency, and confidence—whether you're building your first agent or managing a fleet.

---

## 🔍 What It Does

- Fetches agent configuration and components from Dataverse
- Evaluates:
  - Instructions (clarity, actionability, safety, structure)
  - Tools (naming, descriptions, fit)
  - Orchestration (generative/classic setup, triggers, fallback logic)
- Produces a structured JSON report with:
  - Overall score
  - Criteria breakdown
  - Tool-level insights
  - 3–5 actionable recommendations
- Generates a downloadable PDF summary
- Runs deterministically—same agent = same review result every time

---

## ⚙️ How it works

<img width="2871" height="2047" alt="image" src="https://github.com/user-attachments/assets/6660b772-1053-4b4c-ac38-d8504b102f69" />

---

## 🚀 Key Features

- ✅ Deterministic evaluation powered by Code Interpreter
- 📊 Structured scoring across multiple dimensions
- 📦 Integration with Dataverse for agent data
- 📄 PDF report generation for sharing and archiving
- 🔁 Repeatable and reliable reviews for governance and automation

---

## 👥 Who Is It For?

- **New Makers**: Learn best practices and avoid common mistakes
- **Enterprise Architects**: Scale agent quality across teams
- **QA Teams**: Automate agent evaluation and enforce standards

---

## 📦 Solution Contents

- Power Platform solution (.zip)
- Canvas app for agent selection and review
- Flows for data retrieval and report generation
- Code Interpreter integration for deterministic execution

---

## 🛠️ Setup Instructions

1. Import the Power Platform solution into your environment
2. Ensure Dataverse tables (`Copilot Bot`, `Copilot Component`) are accessible
3. Configure the Code Interpreter connection
4. Launch the canvas app and select an agent to review

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.

---

## 🙌 Contributions
Feel free to fork, enhance, and submit pull requests. For major changes, please open an issue first to discuss what you’d like to change.

---

## 📬 Contact

Created by [Ramakrishnan Raman](https://github.com/Ramakrishnan24689/AgentReviewTool)  
For questions or feedback, reach out via GitHub Issues or connect on LinkedIn.

LinkedIn Profile - [link](https://www.linkedin.com/in/ramakrishnan-raman-49312724/)
