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
  - `User_Onboarding_Guide.md` (Detailed step-by-step instructions for non-technical users)
  - `.gitignore` (Active system filter ignoring operating system files, Python cache, and checkpoints)
  - `claim_assistant_main.ipynb` (Primary development and execution notebook)
  - `User_Main.ipynb` (Minimalist "One-Click" smart user control dashboard)
  - `/receipts/` (Target subfolder for incoming business travel receipts grouped by Claim ID)
  - `/Documentation/` (Archive directory containing Google Docs outlining the project development timeline)

## 🎯 Active Project Objective & Scope
- **Project Name:** ril.claim.assistant
- **Domain:** AI-Powered Business Travel Expense Claim Assistant
- **Primary Use Cases:** Auditing, parsing, and extracting data from travel receipts using the modern **Gemini 3.8-Flash architecture**.

## 🔒 Security & Git Rules for AI Agents
1. **Zero Credential Leaking:** Never request or append plain-text Personal Access Tokens (`ghp_...`) or explicit Gemini API Keys (`AIzaSy...`) inside saving notebook cells or script assets.
2. **Environment Variable/Secrets Handling:** All sensitive access keys must be pulled dynamically from volatile memory during cell execution or sourced via Google Colab's native hidden Secrets/Environment panel.
