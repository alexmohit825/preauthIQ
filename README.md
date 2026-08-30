# PreAuthIQ (v3.1 Clinical Edition)

**AI-powered surgical prior authorization, gap analysis, and medical necessity appeal studio for Spine and Orthopedic Surgery.**

- 🌐 **Live GitHub Pages URL:** [https://alexmohit825.github.io/preauthIQ/](https://alexmohit825.github.io/preauthIQ/)
- 👨‍⚕️ **Author:** Alex Mohit MD PhD, Neurological and Complex Spinal Surgeon

---

## ⚡ Core Capabilities

- 🏥 **Exhaustive 100-Carrier Payer Knowledge Base:** Complete coverage across all 50 states, including 34 dedicated Medicare Advantage plans (UHC MA, Humana Gold, Aetna Eagle, Anthem MediBlue, Kaiser Senior Advantage, Wellcare D-SNP, Devoted Health, SCAN, Alignment, Clover, Premera MA, Regence MedAdvantage, Moda MA, PacificSource Medicare, Providence MA, Samaritan Advantage, CareOregon Advantage, Highmark Freedom Blue, Florida Blue Medicare, HCSC Blue Cross MA, SelectHealth Advantage, etc.).
- 🔄 **Secondary / Supplemental Insurance & COB Engine:**
  - Dedicated **Secondary Insurance (COB / Medigap / Dual Eligible)** toggle and intake box.
  - Supports standard Medigap plans (Plan G/F/N), AARP/UHC Supplement, Mutual of Omaha, BCBS Medigap, TRICARE For Life, Secondary Medicaid (WA Apple Health / OHP Dual Eligible), and custom secondary plans.
  - Automatically incorporates secondary pre-authorization notices and coordination of benefits clauses into the Medical Necessity Letter and EMR chart addendum.
- 🌲 **Dedicated Washington & Oregon (PNW) Sector Suite:** 21 specialized Pacific Northwest payers including Premera, Regence (WA & OR), Asuris, WA L&I, SAIF Corporation (Oregon Workers' Comp OAR 436-010), Apple Health (CHPW, Coordinated Care, Wellpoint WA, Molina), Oregon Health Plan (OHP / HERC Guideline Notes 56 & 37), CareOregon / Health Share CCO, Samaritan Health, KPWA, Moda, PacificSource, and First Choice Health.
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
