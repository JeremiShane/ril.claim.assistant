# Workspace Context: ril.claim.assistant

This file serves as a system context anchor for AI agents assisting with the development infrastructure of this repository.

## 🛠️ Environment Configuration
- **Platform:** Google Colab (Jupyter Notebook environment)
- **Primary Runtime Storage:** Google Drive (Mounted workspace)
- **Google Drive Storage Hierarchy:** `/content/drive/MyDrive/ril_learning/ril.claim.assistant/`
- **Version Control:** Linked directly to GitHub repository `JeremiShane/ril.claim.assistant`
- **Branch Infrastructure:** `main` (Default and active branch)

## 📁 Repository Layout & File Mapping
- `/ril.claim.assistant/` (Root Directory)
  - `README.md` (Project overview and landing summary)
  - `Workspace_Context.md` (This infrastructure context configuration file)
  - `.gitignore` (Active system filter ignoring system junk and checkpoints)
  - `claim_assistant_main.ipynb` (Primary development and execution notebook)
  - `/receipts/` (Target subfolder for incoming business travel receipts)

## 🎯 Active Project Objective & Scope
- **Project Name:** ril.claim.assistant
- **Domain:** AI-Powered Business Travel Expense Claim Assistant
- **Primary Use Cases:** Auditing, parsing, and extracting data from:
  1. Restaurant receipts (meals, itemization, tips)
  2. Hotel receipts/folios (room rates, taxes, incidentals)
  3. Ride-sharing & transit invoices (Uber, Lyft, taxi cab receipts)
- **AI Core:** Leveraging the **Google AI Developer Free Tier** via the `gemini-3.8-flash` model.

## 🔒 Security & Git Rules for AI Agents
1. **Zero Credential Leaking:** Never write down plain-text personal tokens or explicit Gemini API Keys in code cells.
2. **Environment Variable/Secrets Handling:** Sourced via Google Colab's native hidden Secrets panel (`GEMINI_API_KEY`).
