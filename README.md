# Risk2Safe BowTie Studio

AI-assisted bow tie risk assessment and Safety Critical Task Analysis (SCTA) for process safety professionals.

---

## 🌐 Two ways to use it

### **[Open the AI-Assisted version →](./index.html)**
Full feature set including AI suggestions, deep 7-step SCTA, context-aware analysis with P&ID upload, and AI-generated reports. **Requires your own free Anthropic API key** (about 5 minutes to set up; see below).

### **[Open the Manual version →](./manual.html)**
Same visual bow tie diagramming, editing, and export features — without any AI. **No API key needed.** Use this for general bow tie workshops, training sessions, or when AI input is not required.

You can switch between the two versions from the header at any time. No data is shared between them.

---

## What it does

- Build visual bow tie diagrams with full editing capability
- Attach P&IDs, process descriptions, and ESD cause-and-effect logic as context for AI analysis *(AI version only)*
- Auto-flag Safety Critical Elements (SCEs) using a consequence × human-involvement risk matrix
- Run deep 7-step Safety Critical Task Analysis (SCTA) on any identified SCT *(AI version only)*
- Generate Word and PDF reports with cover page, executive summary, methodology, and full proformas
- Export to multi-sheet Excel for spreadsheet workflows

---

## 🔐 Privacy and security

**Your data never leaves your browser** except for direct, end-to-end encrypted requests to Anthropic when you use the AI features.

- **No backend server** — there is no intermediary processing your data
- **No analytics, no tracking, no telemetry**
- **No accounts, no login** — anonymous use
- **No shared API key** — each user provides their own (see below)
- **localStorage only** — your API key and bow tie data are stored only in your own browser, on your own device

### How API keys work

The AI-assisted version requires an Anthropic API key. **This is not a shared key — each user provides their own**, and the key stays on their device.

1. Visit [console.anthropic.com](https://console.anthropic.com/settings/keys)
2. Sign up (free trial credits included — usually enough for dozens of analyses)
3. Click **Create Key** and copy the key (starts with `sk-ant-api03-...`)
4. Paste it into the app when prompted

The key is stored in your browser's localStorage, which is sandboxed per-device — no one else, including the developer of this tool, can access it. When you click "Clear Key" or open the tool in incognito mode, the key is removed.

**Typical cost per analysis:** $0.01–0.15 USD depending on depth. AI requests go directly from your browser to api.anthropic.com.

---

## Important disclaimer

This tool **supports** the bow tie and SCTA process but does **not** replace formal HAZID, HAZOP, LOPA, or SCTA workshops conducted with a multidisciplinary team. Always have outputs reviewed by competent persons and integrate them into your formal safety management system.

---

*Built by Kannan — a senior HSE professional with 30+ years of experience in oil and gas, based in Dubai. Connect on [LinkedIn](https://linkedin.com) for feedback and beta access discussions.*
