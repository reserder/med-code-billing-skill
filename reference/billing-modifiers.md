# Complete Billing Modifiers Reference 2026

## CPT Modifiers

| Modifier | Name | Usage | Payment Impact |
|---|---|---|---|
| 22 | Increased Procedural Services | Unusual complexity. Requires documentation | +20-30% |
| 24 | Unrelated E/M During Postop | E/M unrelated to surgery during global period | Bypasses global |
| 25 | Significant Separately Identifiable E/M | Same day as procedure | Separate payment |
| 26 | Professional Component | Physician interpretation only | Split billing |
| 27 | Multiple Outpatient Hospital E/M | Multiple E/M same date | Hospital use |
| 33 | Preventive Service | ACA-required preventive | No cost share |
| 47 | Anesthesia by Surgeon | Regional anesthesia by operating surgeon | Separate payment |
| 50 | Bilateral Procedure | Identical procedure both sides same session | 150% of single |
| 51 | Multiple Procedures | Additional procedures same session | 50% reduction |
| 52 | Reduced Services | Service less than typically described | Reduced payment |
| 53 | Discontinued Procedure | Stopped after anesthesia due to risk | Reduced payment |
| 54 | Surgical Care Only | Surgery only, no pre/post care | Split global |
| 55 | Postoperative Management Only | Post-op care only | Split global |
| 56 | Preoperative Management Only | Pre-op care only | Split global |
| 57 | Decision for Surgery | E/M day before/day of major surgery | Separate E/M |
| 58 | Staged/Related Procedure | Planned staged procedure in global period | Separate payment |
| 59 | Distinct Procedural Service | Distinct/independent procedure | Bypasses bundling |
| 62 | Two Surgeons | Co-surgery required | 62.5% each |
| 63 | Procedure on Infant <4kg | Significant additional complexity | Variable |
| 66 | Surgical Team | Highly complex requiring team | Team billing |
| 73 | Discontinued Outpatient Before Anesthesia | Hospital/ASC use | Reduced |
| 74 | Discontinued Outpatient After Anesthesia | Hospital/ASC use | Reduced |
| 76 | Repeat Procedure Same Physician | Same procedure same day | Separate payment |
| 77 | Repeat Procedure Different Physician | Same procedure same day different MD | Separate payment |
| 78 | Unplanned Return to OR | Related procedure during global | Intraop only |
| 79 | Unrelated Procedure During Postop | Unrelated to original surgery | Full payment |
| 80 | Assistant Surgeon | Full assistant | 16% of primary |
| 81 | Minimum Assistant Surgeon | Minimal assistance | Reduced |
| 90 | Reference Lab | Outside lab | Passthrough |
| 91 | Repeat Clinical Diagnostic Lab | Repeat test same day | Separate |
| 95 | Synchronous Telemedicine | Real-time audio/video telehealth | Per payer policy |
| 93 | Asynchronous Telemedicine | Store-and-forward | Per payer policy |
| 99 | Multiple Modifiers | More than 2 modifiers needed | Informational |

## X{EPSU} Modifiers (Preferred over 59)
| Modifier | Meaning |
|---|---|
| XE | Separate encounter |
| XP | Separate practitioner |
| XS | Separate structure |
| XU | Unusual non-overlapping service |

## Anesthesia Modifiers (HCPCS)
| Modifier | Description |
|---|---|
| AA | Anesthesia personally performed by anesthesiologist |
| AD | Medical supervision >4 concurrent procedures |
| G8 | Monitored anesthesia care (MAC) for deep complex procedure |
| G9 | MAC for patient with history of severe cardiopulmonary condition |
| QK | Medical direction 2-4 concurrent procedures |
| QS | MAC services |
| QX | CRNA with medical direction |
| QY | Medical direction of one CRNA |
| QZ | CRNA without medical direction |

## Anatomical/Laterality Modifiers
| Modifier | Meaning |
|---|---|
| LT | Left side |
| RT | Right side |
| 50 | Bilateral |
| E1-E4 | Eyelids (upper/lower, left/right) |
| FA-F9 | Fingers |
| TA-T9 | Toes |
| LC | Left circumflex coronary artery |
| LD | Left anterior descending coronary artery |
| RC | Right coronary artery |

## Modifier Stacking Rules
1. Payment modifiers listed FIRST (26, TC, 50, 51, 52, 62)
2. Informational modifiers listed SECOND
3. Never stack conflicting modifiers (e.g., 26 + TC on same claim)
4. Check NCCI modifier indicators before applying (0 = cannot bypass, 1 = modifier allowed)
5. Modifier 25 requires documented significant, separately identifiable E/M service
6. Modifier 59 should be replaced with X{EPSU} modifiers when possible

## High-Risk Modifier Combinations (Audit Flags)
- 25 + procedure on same date: ensure E/M is truly separate
- 22 without documentation of extraordinary circumstances
- 50 when laterality is not documented
- 51 exempt codes (do not append 51 to add-on codes or modifier 51 exempt codes)
- 59/XU when codes are in the same NCCI PTP column as column 2 with indicator 0
