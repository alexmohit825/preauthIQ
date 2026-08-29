# PreAuthIQ (v3.0 Clinical Edition)

**AI-powered surgical prior authorization, gap analysis, and medical necessity appeal studio for Spine and Orthopedic Surgery.**

- 🌐 **Live GitHub Pages URL:** [https://alexmohit825.github.io/preauthIQ/](https://alexmohit825.github.io/preauthIQ/)
- 👨‍⚕️ **Author:** Alex Mohit MD PhD, Neurological and Complex Spinal Surgeon

---

## ⚡ Core Capabilities

- 🏥 **Comprehensive 74-Carrier Insurance Knowledge Base:** Complete national commercial, Blue Cross Blue Shield, Medicare LCDs/MACs, Medicare Advantage, Medicaid MCOs, Workers' Comp (WA L&I, CA SCIF, SAIF Oregon, Texas DWC, NYS WCB), Military/VA (TRICARE, VA CCN, UMP/PEBB), and major utilization review engines (Carelon/AIM, InterQual, Milliman MCG).
- 🌲 **Dedicated Washington & Oregon (PNW) Sector Suite:** 21 specialized Pacific Northwest payers including Premera, Regence (WA & OR), Asuris, WA L&I, SAIF Corporation, Apple Health (CHPW, Coordinated Care, Wellpoint WA, Molina), Oregon Health Plan (OHP / HERC Guideline Notes 56 & 37), CareOregon / Health Share CCO, Samaritan Health, KPWA, Moda, PacificSource, and First Choice Health.
- 📋 **Tri-Mode Generation Hub:**
  1. **Option 1 (Two-Stage Copilot Mode):** 1-click prompt synthesis formatted specifically for Microsoft Copilot or ChatGPT.
  2. **Option 2 (On-Device Fast Synthesizer):** Zero-latency deterministic template generation running 100% locally with zero API key needed.
  3. **Option 3 (Direct Cloud LLM):** Direct client-to-API connection supporting Google Gemini (1.5 Pro / Flash), OpenAI (GPT-4o / 4o-mini), and Anthropic (Claude 3.5 Sonnet).
- 🩺 **EPIC EMR Clipboard Optimization:**
  - `[📥 Paste from EPIC]` and `[+ Append EPIC]` multi-snippet clipboard ingestion.
  - Formats output titled **`Medical Necessity Letter`** signed by **Alex Mohit MD PhD, Neurological and Complex Spinal Surgeon**.
  - `[📋 Copy Letter for EPIC]` for instant paste into Epic NoteWriter / SmartText addenda.
- 🔍 **Instant Carrier Auto-Resolver:** Simply type any carrier name (e.g. `Devoted`, `Carelon`, `CareSource`, `Kaiser`, `Harvard Pilgrim`, `Tufts`, `SCAN`, `Zing Health`, `Clever Care`, `Sentara`) to auto-populate exact guidelines in 1 second.
- ⚖️ **Unlisted Medicare Advantage Parity:** Automatically leverages **42 CFR § 422.101** against obscure Advantage plans.
- 🔒 **Zero-Leakage HIPAA Privacy Shield:** 100% client-side computation with one-click PHI de-identification.
- 🖨️ **Print & Clean PDF Export:** Instant letterhead formatting for faxing or portal upload.

---

## 🚀 GitHub Pages Automated CI/CD

This repository is configured with `.github/workflows/deploy_pages.yml` to automatically build and deploy the app to GitHub Pages on every push to `main`.
