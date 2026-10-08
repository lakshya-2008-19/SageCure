# 🩺 SageCure: Next-Gen AI Health Copilot

Healthcare information is often fragmented, filled with medical jargon, and difficult for patients to understand. **SageCure** is an AI-powered Personal Health Copilot that runs **directly on the user's device**, turning complex lab reports and prescriptions into plain, accessible language with zero privacy risks.

## 🏆 Overview & Challenge Alignment
Designed for the **AI-Powered Personal Health Copilot** challenge, this prototype hits all core scope and bonus requirements:
* **Medical Record Intelligence:** Extracts key biomarkers and test values from uploaded documents.
* **Plain Language Summaries:** Explains abnormal values and clinical data in simple, jargon-free terms.
* **Bonus - Multi-Language & Voice:** Features instant English/Hindi toggling and an integrated audio Voice Companion for visually impaired or elderly users.
* **Bonus - ABDM/FHIR Readiness:** Follows a structured data schema ready for ABHA ID integration and FHIR-compliant storage.

## 🧠 Innovative Architecture (Zero-Cost, Privacy-First)
Unlike traditional applications that send sensitive medical data to paid cloud LLMs, SageCure utilizes an **Edge-Compute / Local AI Architecture**:
* **100% Private (HIPAA/ABDM Compliant):** AI inference runs entirely on the user's local machine/browser. Medical records never leave the device for AI processing.
* **Zero Token Limits:** By utilizing local AI capabilities, the app operates without costly API keys or server bottlenecks.
* **Serverless Data Sync:** Processed, structured data is pushed directly from the secure frontend to a **Supabase** backend.
* **Frictionless Deployment:** Hosted as a lightning-fast Static Site on **Render**.

## 🚀 Core Features
* **Interactive Triage Dashboard:** Senior-friendly UI featuring large typography (A/A+ scaling), high-contrast elements, and step-by-step visual guidance.
* **1-Click Sample Analysis:** Built-in simulated medical records (Diabetic Panel, CBC, Thyroid) for instant testing and evaluation.
* **Biomarker Visualizer:** Color-coded gauges mapping extracted patient values against standard healthy reference ranges.
* **Lifestyle Action Plan:** AI-generated recommended daily actions based on specific test flags.

## 🛠️ Setup & Deployment

**1. Local Development:**
No complex backend installation required.
* Clone this repository.
* Open `index.html` in your code editor.
* Replace `YOUR_SUPABASE_URL` and `YOUR_SUPABASE_ANON_KEY` in the script tag with your actual Supabase project credentials.
* Double-click `index.html` to run the app directly in your browser.

**2. Live Deployment (Render):**
* Push the repository to GitHub.
* Log into **Render** and select **New > Static Site**.
* Connect the repository, leave the build command blank, and set the publish directory to the root (`.`).
* Click Deploy. Your site is live!

---
*Disclaimer: SageCure is an AI-generated health assistant for informational purposes only. It is not a replacement for professional medical consultation.*
