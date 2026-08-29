# PreAuthIQ (v2.0 Clinical Edition)

**AI-powered surgical prior authorization, gap analysis, and medical necessity appeal studio.**

PreAuthIQ empowers surgeons, practice administrators, and clinical teams to overcome insurance claim denials and expedite pre-authorizations with zero friction.

---

## ⚡ Core Capabilities

- 🏥 **Comprehensive 60-Carrier Payer Knowledge Base:** Exhaustive medical policies across National Commercial (Aetna CPB 0743, Anthem CG-SURG-71/72/83, UHC 2023T0559U, Cigna 0263, Humana SUR-020), Regional Blue Cross Blue Shield plans (Premera, Regence, Blue Shield CA, IBX, Highmark, Florida Blue, HCSC, Horizon), Original Medicare LCDs & MACs (Noridian, Novitas, Palmetto, First Coast, NGS, CGS), Medicare Advantage, Medicaid MCOs (CHPW, Coordinated Care Evolent CG-1766/1759, Molina, Centene), Workers' Compensation Boards (WA L&I WAC 296-20, CA SCIF MTUS/ACOEM, Texas DWC, NYS WCB MTGs, FECA OWCP), Military/VA (TRICARE, VA CCN TriWest/Optum, UMP/PEBB), and universal utilization engines (InterQual, MCG).
- 🔍 **Real-Time Payer Gap Analysis Matrix:** Side-by-side verification of physical therapy duration, diagnostic imaging concordance (MRI/CT), dynamic flexion/extension instability (>= 3mm), validated functional outcome measures (ODI >= 40%, VAS >= 6/10), and acute emergency waivers (progressive motor weakness Grade <= 3/5, cauda equina, cervical myelopathy).
- 📋 **Dual-Mode Generation:** 
  1. **MS Copilot / ChatGPT Prompt Synthesizer:** 1-click tailored prompt generation citing exact policy numbers and peer-to-peer defense arguments.
  2. **1-Click Direct Letter Generator:** In-browser instant synthesis and editable letter drafting.
- 📄 **1-Click EMR Note Merger:** Automatically stitches the original clinical note + insurance verification header + medical necessity letter ready for pasting straight into Epic, Cerner, AthenaHealth, or NextGen.
- 🔒 **Zero-Leakage Local HIPAA Shield:** 100% client-side computation with one-click PHI de-identification.
- 🖨️ **Print & Clean PDF Export:** Instant letterhead formatting for faxing or portal upload.

---

## 🚀 Deployment (Netlify & Vercel)

PreAuthIQ is engineered as a high-performance, zero-dependency standalone web app.

### Deploy to Netlify
1. Push to your GitHub repository: `alexmohit825/preauthIQ`.
2. Connect repository in Netlify.
3. Publish directory: `.` (root).

### Local Preview
Open `index.html` directly in any modern web browser or run:
```bash
npx serve .
```

---

## 📜 Architecture & Isolation
PreAuthIQ is fully independent and isolated from `NecessityIQ` and other projects. All insurance guidelines and parser engines operate strictly within this repository.
