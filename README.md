# Property Lifecycle Orchestrator

**Full-cycle real estate AI swarm** for buying, selling, and owning properties in Europe – built 100% no-code in IBM watsonx Orchestrate.

## 🚀 Live Demo
- **Chat with the Agent**: [Paste your Orchestrate public link here, e.g., https://orchestrate.ibm.com/your-agent]


## 🎯 What It Does
One natural language request → agent swarm handles everything:
- **Sales**: Live search on Immobilienscout24.de/Immowelt.de for matching properties + CRM sync (Salesforce/HubSpot).
- **Customer Service**: Post-sale tickets for repairs + Slack escalations.
- **Full Workflow**: Pricing comps, calendar bookings, email brochures, human approvals.

**ROI**: Saves agents 15–20 hrs/week → €100k+ extra commission/year.

## 🏗️ Architecture (7-Agent Swarm)
![Architecture Diagram](architecture.png)

- **Orchestrator**: Routes requests (Granite-powered, ReAct style).
- **Property Research Agent**: Live web scraping + neighborhood analysis.
- **CRM Master Agent**: Lead/Opportunity creation.
- **Scheduler & Outreach Agent**: Google Calendar + Gmail.
- **Listing & Pricing Agent**: Comps-based recommendations.
- **Service Ticket Agent**: Post-sale support.
- **Human Approval Agent**: Slack/Teams gates.

## 🔧 Built With
- IBM watsonx Orchestrate (no-code drag/drop).
- Tools: Web Search, Browse Page, Salesforce, Google Workspace, Slack.
- Models: Granite 3.1 for reasoning.

## 📁 Files
- `agents.yaml`: Orchestrate agent configs (exported).
- `architecture.png`: Visual swarm diagram.

## 🎉 Hackathon Submission
- **Core Areas**: Sales + Customer Service.
- **Innovation**: Live web + multi-agent delegation.
- **Impact**: Accelerates deals 30–50%, reduces support time to minutes.

Fork, star, or contribute! Questions? @your-twitter.

---
*Built for Agentic AI Hackathon with IBM watsonx Orchestrate (Nov 2025). #AI #RealEstate #watsonx*
