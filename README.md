# med-code-billing-skill

> World-class advanced medical coding & billing Claude skill

---

## What This Skill Does

This is an advanced Claude AI skill that transforms Claude into the most capable medical coding and billing assistant available. It covers:

- **ICD-10-CM/PCS** (FY2026 + interim updates)
- **CPT** (2026 code set)
- **HCPCS Level II** (quarterly updates)
- **NCCI Edits** (PTP, MUE, AOC)
- **E/M Leveling** (2021 AMA guidelines)
- **Denial Management** (CO/PR codes + appeal language)
- **Revenue Cycle** (front-end to back-end)

---

## File Structure

```
med-code-billing-skill/
├── SKILL.md                        # Main skill definition
├── README.md                       # This file
└── reference/
    ├── billing-modifiers.md        # Complete CPT/HCPCS modifier guide
    ├── 2026-cpt-updates.md         # 2026 CPT changes (288 new, 84 deleted)
    ├── 2026-icd-updates.md         # FY2026 ICD-10-CM/PCS changes
    └── ncci-edits.md               # NCCI PTP, MUE, AOC, global surgery rules
```

---

## How to Install in Claude Console

1. Download this repo as a ZIP:
   - Click the green **Code** button above
   - Select **Download ZIP**
2. Go to [Claude.ai](https://claude.ai) → Settings → Skills
3. Upload the ZIP file
4. The skill will auto-trigger on medical coding/billing topics

---

## Skill Capabilities

### Coding Systems Covered
| System | Version | Source |
|---|---|---|
| ICD-10-CM | FY2026 | CDC/CMS |
| ICD-10-PCS | FY2026 + April interim | CMS |
| CPT | 2026 | AMA |
| HCPCS Level II | Current quarterly | CMS |
| NCCI PTP | Current quarterly | CMS |
| NCCI MUE | Current quarterly | CMS |
| MS-DRG | v43 FY2026 | CMS |
| APC | FY2026 | CMS |

### Output Format (Every Response)
- Diagnosis codes table (ICD-10-CM) with sequencing notes
- Procedure codes table (CPT/HCPCS) with modifiers and RVUs
- NCCI edit status (pass/fail)
- Denial risk assessment (Low/Medium/High)
- Alternative coding options (conservative vs aggressive)
- Documentation recommendations

### Self-Update Logic
- Always anchors code selection to date of service
- Treats most recently published official source as ground truth
- Learns from user corrections
- Flags codes that may have changed in the last 90 days

---

## Download ZIP (Direct Link)

https://github.com/reserder/med-code-billing-skill/archive/refs/heads/main.zip

---

## Built for Amora Healthcare
Developed to power the Amora Healthcare RCM automation platform.

---

## License
For internal use. All coding guidelines sourced from AMA, CMS, CDC, and AAPC official publications.
