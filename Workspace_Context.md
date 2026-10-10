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
  - `.gitignore` (Active system filter ignoring operating system files, Python cache, and `.ipynb_checkpoints/`)
  - `claim_assistant_main.ipynb` (Primary development and execution notebook)

## 🎯 Active Project Objective & Scope
- **Project Name:** ril.claim.assistant
- **Domain:** AI-Powered Claim Reimbursement Assistant
- **AI Core:** Leveraging the **Google AI Developer Free Tier** via the Gemini API.
- **Workflow Architecture:** Multi-project scalability. The user intends to host multiple independent development workspaces under the master `/content/drive/MyDrive/ril_learning/` directory in the future.

## 🔒 Security & Git Rules for AI Agents
1. **Zero Credential Leaking:** Never request or append plain-text Personal Access Tokens (`ghp_...`) or explicit Gemini API Keys (`AIzaSy...`) inside saving notebook cells or script assets.
2. **Environment Variable/Secrets Handling:** All sensitive access keys must be pulled dynamically from volatile memory during cell execution or sourced via Google Colab's native hidden Secrets/Environment panel.
3. **Clean Workspace Pushes:** Always utilize the automated `.gitignore` structures to safeguard the public repository history from runtime junk.
