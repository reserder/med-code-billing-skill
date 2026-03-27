# NCCI Edits Reference 2026
## National Correct Coding Initiative

---

## 1. Procedure-to-Procedure (PTP) Edits

### What Are PTP Edits?
PTP edits define pairs of CPT/HCPCS codes that should not be billed together by the same provider for the same patient on the same date of service.

### Column 1 / Column 2 Structure
| Column | Meaning |
|---|---|
| Column 1 | Primary code (always paid) |
| Column 2 | Component code (bundled into Column 1) |

### Modifier Indicator
| Indicator | Meaning |
|---|---|
| 0 | Modifier NOT allowed — codes cannot be unbundled under any circumstance |
| 1 | Modifier allowed — can append modifier 59/XE/XP/XS/XU to bypass edit |

### Common PTP Edit Examples
| Column 1 | Column 2 | Modifier Indicator | Rationale |
|---|---|---|---|
| 43239 (EGD with biopsy) | 43235 (EGD diagnostic) | 0 | Diagnostic included in surgical |
| 99213 (E/M) | 99000 (specimen handling) | 0 | Specimen handling not separately billable |
| 27447 (total knee arthroplasty) | 27310 (knee arthrotomy) | 0 | Arthrotomy included in arthroplasty |
| 93000 (ECG) | 93005 (ECG tracing only) | 0 | Cannot bill both components |
| 99214 (E/M) | 36415 (venipuncture) | 1 | Separate if distinct service |

### How to Apply PTP Edits
1. List all CPT codes being billed for the encounter
2. Check each pair against current CMS PTP table (updated quarterly)
3. If edit exists with indicator 0: remove the Column 2 code
4. If edit exists with indicator 1: append appropriate modifier if clinically justified
5. Document medical necessity for modifier bypass

---

## 2. Medically Unlikely Edits (MUEs)

### What Are MUEs?
MUEs define the maximum units of service (UOS) that a provider would report for a single beneficiary on a single date of service under most circumstances.

### MUE Adjudication Indicator (MAI)
| MAI | Meaning | Claim Processing |
|---|---|---|
| 1 | Date of service edit: claim line | Line-by-line review |
| 2 | Date of service edit: absolute | Never exceed regardless of documentation |
| 3 | Date of service edit: per claim | Medical review may allow more with documentation |

### Common MUE Examples
| Code | MUE Value | MAI | Notes |
|---|---|---|---|
| 99213 | 1 | 2 | Max 1 E/M per provider per day |
| 36415 | 1 | 2 | Max 1 routine venipuncture per day |
| 27447 | 1 | 2 | Max 1 total knee per extremity |
| 93000 | 1 | 2 | Max 1 ECG per day |
| 11042 | 1 | 3 | Debridement — may document for more |
| 97110 | 4 | 3 | Therapeutic exercise — up to 4 units |
| 99232 | 1 | 3 | Subsequent hospital care per day |

### When Units Exceed MUE
- MAI 2: NEVER bill above MUE — absolute limit
- MAI 3: May bill above MUE with documentation and -59 modifier on separate line
- Always append modifier on 2nd line when billing above MUE for MAI 3

---

## 3. Add-On Code (AOC) Edits

### Rules for Add-On Codes
1. Add-on codes (designated with + in CPT) are NEVER reported alone
2. Must always be reported with the primary parent code
3. Add-on codes are exempt from modifier 51 (multiple procedures)
4. Do not append modifier 51 to add-on codes

### Common Add-On Code Examples
| Add-On Code | Parent Code(s) | Description |
|---|---|---|
| +99417 | 99205, 99215 | Prolonged office visit, each 15 min |
| +93571 | 93570 | Intravascular Doppler velocity |
| +11001 | 11000 | Debridement of skin, each additional 10% |
| +22614 | 22600-22612 | Arthrodesis, additional interspace |
| +90461 | 90460 | Immunization admin, each additional component |
| +96368 | 96365-96367 | Concurrent infusion |

---

## 4. Modifier Bypass Rules

### Valid Reasons to Use Modifier 59/X{EPSU}
- Procedure performed at a different anatomic site
- Procedure performed during a different session/encounter
- Procedure performed by a different provider
- Procedure not ordinarily performed together but medically necessary

### Documentation Required for Modifier Bypass
- Clearly document the distinct nature of each service
- Separate operative reports if different procedures
- Note different anatomical sites explicitly
- Medical necessity statement

### Modifiers That Can Bypass NCCI Edits (indicator 1 only)
| Modifier | When to Use |
|---|---|
| 59 | General distinct procedure (use X modifiers when possible) |
| XE | Separate encounter same day |
| XP | Different provider |
| XS | Different anatomical structure |
| XU | Unusual service not normally done together |
| LT/RT | Bilateral procedures on different sides |
| 91 | Repeat lab test (not duplicate) |

---

## 5. Global Surgery Package Rules

### What's Included in Global Package
- Preoperative visits (day before major, day of minor surgery)
- All intraoperative services
- Complications not requiring return to OR
- Postoperative visits during global period
- Miscellaneous services (dressings, suture removal)

### Global Periods
| Type | Period |
|---|---|
| 000 | Endoscopy/minor, day of surgery only |
| 010 | Minor surgery, 10-day postop |
| 090 | Major surgery, 90-day postop |
| MMM | Maternity codes |
| YYY | Unlisted/by report |
| ZZZ | Add-on code (relates to primary) |

### What Is NOT Included in Global Package
- Treatment of unrelated conditions
- Staged procedures (modifier 58)
- Repeat procedures for complications requiring OR (modifier 78)
- Unrelated procedures (modifier 79)
- E/M visits with significant separately identifiable service (modifier 24)

---

## 6. Quarterly Update Schedule 2026
| Quarter | Effective Date | Action Required |
|---|---|---|
| Q1 2026 | January 1, 2026 | Review all PTP/MUE updates |
| Q2 2026 | April 1, 2026 | ICD-10-PCS interim + PTP updates |
| Q3 2026 | July 1, 2026 | HCPCS + PTP/MUE updates |
| Q4 2026 | October 1, 2026 | ICD-10 FY2027 + full code set update |

---

## 7. RAC and OIG Audit High-Risk NCCI Patterns
- E/M + procedure same day without modifier 25
- Bilateral procedures billed as two separate unilateral codes without modifier 50
- Lab panels unbundled into component codes
- Evaluation services bundled in global period without exception modifiers
- Upcoded E/M levels not supported by MDM or time documentation
- Therapy services exceeding MUE without documentation
