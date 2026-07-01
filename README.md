# Shaban Alam — AI Automation Developer

[![Email](https://img.shields.io/badge/Email-shabandev27%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white)](mailto:shabandev27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Shaban27--dev-181717?style=flat-square&logo=github)](https://github.com/Shaban27-dev)
[![Location](https://img.shields.io/badge/Location-India-orange?style=flat-square&logo=googlemaps&logoColor=white)](https://github.com/Shaban27-dev)
[![Freelance](https://img.shields.io/badge/Freelance-Open%20to%20Work-brightgreen?style=flat-square)](mailto:shabandev27@gmail.com)

I build automation systems for businesses that want to stop doing things manually. My work spans AI-powered n8n workflow orchestration, Python-based data pipelines, and webhook infrastructure — built to run in the background, handle edge cases, and deliver measurable results without ongoing supervision.

---

## Featured Technologies

![n8n](https://img.shields.io/badge/n8n-FF6D5A?style=flat-square&logo=n8n&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-000000?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)

---

## About Me

Most business operations run on tasks that are predictable and repetitive in ways that scale badly. Someone reads a form submission and decides manually whether the lead is worth pursuing. Someone opens an invoice PDF, types the numbers into a spreadsheet, and repeats it the next day. Someone checks five websites each morning to stay current with a fast-moving industry. None of this is difficult — it's just consistent enough to automate, and every hour it takes is an hour not spent on work that needs human judgment.

I build systems that handle it entirely: event-driven pipelines that fire on trigger, AI-augmented workflows that enrich and classify data before a human sees it, and scheduled tools that deliver results while the business sleeps. The goal isn't to show automation is possible — it's to make the manual version feel unnecessary.

---

## Engineering Principles

| Principle | What it means in practice |
|---|---|
| **Production-ready over prototypes** | Every workflow is tested against live data, handles edge cases, and includes error paths before it ships |
| **Business value before technical complexity** | The simplest implementation that solves the problem reliably is the right one |
| **Modular architecture** | Each node or function carries a single responsibility — components can be swapped or extended without rebuilding the whole |
| **Documentation as a deliverable** | Every project ships with a README explaining the business problem, the architecture, and the deployment steps |
| **Reliability as the success criterion** | A workflow that runs unattended without breaking is more valuable than one that demonstrates impressive technical complexity |

---

## Automation Domains

`AI Workflow Automation` · `Business Process Automation` · `Lead Qualification & Enrichment` · `Document Processing` · `CRM Automation` · `Knowledge Base Automation` · `Google Workspace Automation` · `Email Automation` · `API Integrations` · `Data Pipelines` · `Web Scraping` · `Webhook Architecture`

---

## Portfolio

Three repositories, each serving a distinct function. `n8n-workflows` is the primary delivery — production AI and business automation pipelines built for operational deployment, each exported as an importable JSON file ready to activate. `automation-projects` contains the Python layer: standalone automation tools, API integrations, and webhook infrastructure built to the same production standard. `python-projects` is the technical foundation — the Python fundamentals, OOP patterns, and problem-solving structures the automation work is built on top of.

---

## Featured Portfolio

### ⭐ n8n Workflows — Flagship Repository

> Production-ready n8n automation pipelines for AI-powered business operations, document processing, lead qualification, and Google Workspace integration.

Every workflow in this repository starts from a real operational problem. Each is tested against live data, includes error handling and edge-case routing, and ships with a deployment-ready JSON file and a full README walkthrough.

| Workflow | Business Problem Solved | Technologies |
|---|---|---|
| 🤖 [AI Lead Enrichment & Qualification Pipeline](https://github.com/Shaban27-dev/n8n-workflows/tree/main/ai-lead-enrichment-qualification-pipeline) | Enriches inbound Typeform leads via Apollo, scores them against a deterministic rubric, generates AI-driven sales strategies for qualified prospects, routes by score threshold, and logs to separate Sheets dashboards with branded HTML alerts | Typeform · Apollo API · JavaScript · AI Agent · OpenRouter · Google Sheets · Gmail |
| 🧾 [Intelligent Invoice Processing Pipeline](https://github.com/Shaban27-dev/n8n-workflows/tree/main/intelligent-invoice-processing-pipeline) | Monitors Gmail for invoice attachments, OCR-extracts each PDF, parses structured fields via LangChain, validates against four conditions, archives to Drive, and routes to success logging or a compliance audit trail with distinct email notifications per outcome | Gmail Trigger · OCR API · LangChain Extractor · OpenRouter · Google Drive · Google Sheets · Gmail |
| 📰 [AI News Digest Automation](https://github.com/Shaban27-dev/n8n-workflows/tree/main/ai-news-digest-automation) | Polls the AI industry RSS feed every four hours, generates LLM-powered executive summaries and impact analysis per article, builds a Notion knowledge base automatically, and emails a curated briefing at 8 AM daily | RSS Feed · AI Agent · OpenRouter · Notion · Gmail |
| 📋 [Client Form → CRM](https://github.com/Shaban27-dev/n8n-workflows/tree/main/client-form-crm) | Captures Typeform client inquiries, scores leads against business rules, logs every submission to a Notion CRM, and routes each prospect into one of three distinct automated email paths | Typeform · JavaScript · Notion · Switch · Gmail |
| ⚙️ [Drive File Organizer](https://github.com/Shaban27-dev/n8n-workflows/tree/main/drive-file-organizer) | Detects new Google Drive uploads, classifies each file by extension, moves it to the appropriate folder, appends an audit row to Sheets, and sends a confirmation email — no manual action required | Google Drive · Switch · JavaScript · Google Sheets · Gmail |
| 🔔 [Price Drop Notifier](https://github.com/Shaban27-dev/n8n-workflows/tree/main/price-drop-notifier) | Checks a product page on a daily schedule and fires an email alert the moment the price drops to a configured target | HTTP Request · HTML Extraction · IF Node · Gmail |

→ **[View n8n Workflows Repository →](https://github.com/Shaban27-dev/n8n-workflows)**

---

### Python Automation Projects

> Production-style Python automation tools — API integrations, live monitoring systems, and webhook infrastructure for businesses that need scheduled, unattended data operations.

| Project | Business Problem Solved | Stack |
|---|---|---|
| 🔗 [Flask Webhook Relay](https://github.com/Shaban27-dev/automation-projects/tree/main/flask-webhook-relay) | Receives and authenticates incoming webhook payloads, logs structured events to the terminal, and dispatches branded HTML email alerts for every valid event. Integrates directly with n8n, Zapier, or any HTTP client | Flask · smtplib · python-dotenv |
| 🔔 [Job Alert Automator](https://github.com/Shaban27-dev/automation-projects/tree/main/job-alert-automator) | Monitors RemoteOK for listings matching configured keywords, deduplicates across runs by job ID and content fingerprint, logs every match to Google Sheets, and emails a clean HTML digest | requests · gspread · schedule |
| 📊 [SheetSync Crypto Reporter](https://github.com/Shaban27-dev/automation-projects/tree/main/SheetSync-Crypto-Reporter) | Fetches live cryptocurrency prices from CoinGecko on a configurable schedule and appends timestamped rows to Google Sheets automatically — zero manual data entry after initial setup | requests · gspread · Google Sheets API |
| 🤖 [Multi-API Alert Bot](https://github.com/Shaban27-dev/automation-projects/tree/main/multi_api_alert_bot) | Monitors weather and stock data across three APIs simultaneously and fires contextual email alerts with analysis when thresholds are exceeded | requests · smtplib · python-dotenv |

→ **[View Automation Projects Repository →](https://github.com/Shaban27-dev/automation-projects)**

---

### Python Projects — Technical Foundation

> A structured portfolio of 20 Python projects demonstrating the language fundamentals, OOP design patterns, and problem-solving depth that underpin the automation work in this profile.

Categories: `CLI Tools` · `OOP Projects` · `GUI Applications` · `Games` · `Data Projects`

Includes a Library Management System, Student Grade Analyser, ATM Simulator, Snake Game, and a Tkinter-based Password Manager — each independently runnable and documented.

→ **[View Python Projects Repository →](https://github.com/Shaban27-dev/python-projects)**

---

## Technology Stack

| Category | Tools |
|---|---|
| **Automation & Orchestration** | n8n · LangChain AI Agent · LangChain Information Extractor · Structured Output Parser |
| **AI & LLM** | OpenRouter · LangChain |
| **Language** | Python 3 |
| **Web & Webhooks** | Flask · HTTP Request · HTML Extraction · Typeform Trigger · Apollo Organization API · OCR API (api4ai) |
| **External APIs** | CoinGecko · OpenWeatherMap · Alpha Vantage · NewsAPI · RemoteOK |
| **Google Workspace** | Google Sheets API · Google Drive API · Gmail · gspread · google-auth |
| **Data & Storage** | Notion · Google Sheets · JSON |
| **Python Libraries** | requests · Flask · gspread · pandas · python-dotenv · schedule · Tkinter |
| **Developer Tools** | Docker · Git · GitHub · VS Code |
| **Email** | smtplib · MIMEMultipart · HTML email templates |

---

## Current Focus

Active development is concentrated on three categories of systems:

- **AI-powered intake and qualification pipelines** — multi-stage workflows that accept inbound data from form triggers, enrich it against external sources, apply deterministic scoring rules, invoke LLM analysis for qualifying records, and route outputs into CRM dashboards and notification emails. The manual triage layer between submission and action is removed entirely.
- **Intelligent document processing pipelines** — end-to-end systems that ingest unstructured business documents, extract structured data via AI, validate fields against compound conditions, archive originals, and maintain separate audit logs for success and failure paths. Manual data entry is replaced with an automated, auditable record.
- **Operational knowledge base automation** — systems that monitor external information sources on a continuous schedule, generate structured LLM summaries, and maintain a queryable, up-to-date knowledge base with no ongoing human curation required.

Each system is built around the same outcome: a process that once required regular manual attention runs reliably on its own, with the right people notified at the right time.

---

## Contact

**Shaban Alam** · AI Automation Developer · n8n Workflow Specialist · Python Automation Engineer

If you have a process that runs on a predictable pattern — a form that needs routing, a document that needs processing, a data source that needs monitoring — reach out.

[![Email](https://img.shields.io/badge/Email-shabandev27%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white)](mailto:shabandev27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Shaban27--dev-181717?style=flat-square&logo=github)](https://github.com/Shaban27-dev)
[![Freelance](https://img.shields.io/badge/Freelance-Open%20to%20Work-brightgreen?style=flat-square)](mailto:shabandev27@gmail.com)

Available for freelance n8n workflow builds, AI pipeline development, Python automation tools, and Google Workspace integrations.
