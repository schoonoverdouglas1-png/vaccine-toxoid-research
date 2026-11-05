# Table — Toxoid Table, Improved Repeat (2026-11-04)

**Direct answer:** This is a repeat of the Nov 4 toxoid / carrier-by-disease table, made better under the Research Logic & Evidence Framework. The original table is not replaced — this is a new, improved repeat, old-with-new.
**Source for the original:** Postulate — Vaccine-Reaction and Toxoid Parallel (2026-11-04), and Unified Vaccine and Carrier Architecture — Expanded, Built Off Nov 4 PDF, with Additions (2026-11-04), carrier-by-disease map section, plus Nov 4 pneumococcal deep research (vaccine lists, carrier mapping) and Nov 4 ChatGPT "Branch · Toxoid Bridge Analysis" import (three-axis commonality, host-dependency).
**Method used for the improvement:** Research Logic & Evidence Framework §6 (three layers) and §7 (direct answer / source says / comparison / can conclude / cannot conclude / safety / next verification). Evidence tiers: [D] documented · [H] his · [H→D] his with documented foothold · [LOGIC] AI inference · [GAP] unknown · [PARTIAL] partial · [SINGLE-SOURCE] bibliography missing until re-sourced.

## What was wrong / weak in the original repeat, and what is fixed here

1. **TT / DT / CRM197 were easy to blur.** Fixed: CRM197 is a genetically detoxified, non-toxic diphtheria toxin mutant. It is **not** the same thing as chemically detoxified diphtheria toxoid (DT). [D, framework §6 Layer 2]
2. **"Diphtheria link" / "tetanus link" were stated class-wide.** Fixed: Direct DT for pneumococcus = **19F only, Synflorix only**. Direct TT for pneumococcus = **18C only, Synflorix only**. CRM197 as carrier-origin is class-wide across PCV7/13/15/20/21 and PCV10-SII, but that does **not** make every serotype a "diphtheria serotype." [D, Nov 4 deep research + Break 1 audit]
3. **Molecular, antigenic, and vaccine commonality were in one column.** Fixed: three separate columns, per the ChatGPT toxoid bridge table and framework §6. A match on one does **not** prove a match on the others. Antigenic cross-reactivity is not proven by molecular similarity alone. [Framework §6, ChatGPT §1]
4. **Host was missing.** Fixed: Layer 3, host immune dependency, added as its own table, from the ChatGPT "What if the body is missing something?" section. A host deficiency is not a missing vaccine ingredient. [Framework §6 Layer 3]
5. **Bexsero / GXM errors from the PDF were in the original PDF table.** Fixed, and kept visible as corrections, not hidden: Bexsero is meningococcal B, OMV, **not** pneumococcal. GXM is **not** identical chemistry to pneumococcal repeat units — shared carrier design concept, investigational only. [D vs. PDF, Nov 4 audit]

## Improved Table 1 — Toxoid / carrier, by disease system

Columns: Disease system / Organism [D] | Capsule / antigen system | Carrier(s), product-specific [D, with GAP where noted] | Molecular commonality | Antigenic commonality | Vaccine commonality | Tier / note

| Disease system | Capsule / antigen | Carrier(s), product-specific | Molecular | Antigenic | Vaccine | Note |
|---|---|---|---|---|---|---|
| Diphtheria — *Corynebacterium diphtheriae* | No capsular serotypes. Toxin gene tox+ vs. tox- | DT itself; source of CRM197 mutant | Diphtheria toxin protein, no polysaccharide capsule | Antitoxin response to diphtheria toxin | DT, Td, DTaP, Tdap as toxoid vaccines | CRM197 ≠ DT. Do not merge the two rows. |
| Tetanus — *Clostridium tetani* | No serotypes. Tetanospasmin toxin only | TT itself | Tetanus toxin protein, no capsule | Antitoxin response to tetanus toxin | TT, Td, DTaP, Tdap as toxoid vaccines | TT as pneumococcal carrier is a different use from TT as tetanus vaccine antigen. |
| Pneumococcal — *Streptococcus pneumoniae* | 100+ capsular serotypes, Quellung, antigenic serogroups, NOT genetic clusters | **PCV7/13/15/20/21: CRM197 for all serotypes. PCV10-SII Pneumosil: CRM197 for all. PCV10-GSK Synflorix, mixed: Protein D for 1, 4, 5, 6B, 7F, 9V, 14, 23F; TT for 18C only; DT for 19F only. PPSV23: no carrier, unconjugated.** | Distinct repeat units per serotype (e.g. 19F phosphodiester bridge, 6A/6B ribitol-P) | Serogroup = antigenic grouping; cross-reactivity within a serogroup is NOT assumed from membership | PCV7→PCV20 superset chain; PCV21 breaks it (drops 1, 4, 5, 6B, 9V, 14, 18C, 19F, 23F); PPSV23 list is its own 23 | Union across all pneumococcal products = 32 disease serotypes. Cross-reactivity between serotypes runs through polysaccharide similarity, NOT shared carrier. |
| Meningococcal — *Neisseria meningitidis* | Serogroups A, B, C, W, Y, X, capsular polysaccharides | DT (Menactra), CRM197 (Menveo), TT (MenQuadfi), OMV (Bexsero, MenB only) | Group A ManNAc-1-P; C/W/Y sialic acid variations | Serogroup-specific, not pneumococcal serotype cross-reactivity | MenACWY + MenB are parallel systems, not pneumococcal relatives | **Correction:** Bexsero is meningococcal B, NOT pneumococcal. Do not merge letter systems (Men A/B/C/W/Y/X vs. pneumococcal numbers). |
| Hib — *Haemophilus influenzae* | Serotypes a–f; Type b most invasive; NTHi non-typeable | TT (ActHIB), CRM197 (HbOC), OMP (PedvaxHIB) | Polyribosylribitol phosphate (PRP) repeat | Type b vs. other types, distinct | Hib conjugate vaccines, separate from pneumococcal | GAP-in-scope for pneumococcal audit; Protein D links to NTHi per PDF — GAP, not verified here. |
| Typhoid — *Salmonella enterica* Typhi | Vi capsular antigen, O9, H:d | TT (Typbar-TCV), CRM197 (Vi-CRM) | Vi polysaccharide | Vi-specific | Typhoid conjugate vaccines, separate | GAP-in-scope; parallel design via TT/CRM197 per PDF, not verified against a label here. |
| GBS — *Streptococcus agalactiae* | Capsular types Ia, Ib, II, III, IV, V, VI, VII, VIII, IX | CRM197 (investigational GBS6: Ia, Ib, II, III, IV, V), TT, native proteins in trials | Sialic acid-containing polysaccharides | Capsular-type-specific | **No licensed GBS vaccine**; GBS6 investigational | GBS "serotype" = capsular type, NOT pneumococcal serotype, NOT in PN23M. Group B = *S. agalactiae*, vs. Group A = *S. pyogenes*. |
| Cryptococcosis — *Cryptococcus neoformans / gattii* | Encapsulated yeast; GXM capsule, mannose backbone; serotypes A, D, AD (neoformans/grubii), B, C (gattii), by GXM reactivity | **No licensed human vaccine. Investigational: GXM-TT, GXM-DT, GXM-CRM197 as concepts only.** | GXM, CAP genes (CAP10, 59, 60, 64 in extraction) | **No mapping pneumococcal group ↔ fungal serotype in any retrieved source — GAP per-serotype.** Only bridge retrieved: unnamed "some antigenic determinants shared with certain pneumococcal polysaccharides" — serotypes unnamed, GAP | No licensed vaccine to compare | **Correction:** GXM is NOT identical chemistry to pneumococcal repeat units. Shared carrier design concept only. |
| Fungal, other — *Candida / Aspergillus* | Fungal cell wall mannan, beta-glucan, galactomannan, Als3 adhesin | Investigational (NDV-3A Als3-based, PEV7 Sap2); CRM197 in trials | Fungal wall polysaccharides, distinct from bacterial capsules | Analogy only, not a serotype mapping | No licensed vaccine in this row | Fourfold test, Nov 4: disease part BREAKS literal, vaccine part HOLDS investigational only, immunity part HOLDS as design parallel, key part PARTIAL. |
| Viral contrast — Influenza, HPV | HA/NA glycoproteins; L1 VLPs | No toxoid carrier (IIV, LAIV, Flublok; Gardasil, Cervarix) | Viral proteins, NOT polysaccharide serotypes | Virus-specific | Separate vaccine systems | Contrast case: shows toxoid carriers are a bacterial conjugate design, not a universal vaccine feature. |

## Improved Table 2 — Pneumococcal carrier, product by product (the part most often misread)

| Product | Carrier, exact | Serotypes in product | What it does NOT prove |
|---|---|---|---|
| PCV7 | CRM197, all | 4, 6B, 9V, 14, 18C, 19F, 23F | Does not make 18C a tetanus serotype or 19F a diphtheria serotype. CRM197 is diphtheria-derived, not DT. |
| PCV10-GSK, Synflorix | Mixed: Protein D (1, 4, 5, 6B, 7F, 9V, 14, 23F); TT (18C only); DT (19F only) | 1, 4, 5, 6B, 7F, 9V, 14, 18C, 19F, 23F | TT/DT here are Synflorix-only. Do not generalize to PCV13/15/20/21. |
| PCV10-SII, Pneumosil | CRM197, all | 1, 5, 6A, 6B, 7F, 9V, 14, 19A, 19F, 23F | PCV10 is TWO vaccines. Synflorix ≠ Pneumosil. |
| PCV13 | CRM197, all | PCV10-GSK + 3, 6A, 19A | 6A is directly in PCV13, not merely "cross-protected." |
| PCV15, Vaxneuvance | CRM197, all | PCV13 + 22F, 33F | 15B does NOT enter with PCV15. 15B enters with PCV20. |
| PCV20 | CRM197, all | PCV15 + 8, 10A, 11A, 12F, 15B | — |
| PCV21, Capvaxive | CRM197, all | Formulation 21: 3, 6A, 7F, 8, 9N, 10A, 11A, 12F, 15A, 15B (de-O-acetylated), 16F, 17F, 19A, 20A, 22F, 23A, 23B, 24F, 31, 33F, 35B. Invasive indication 22 (adds 15C by cross-reactivity). Pneumonia indication 21 (excludes 15B). | PCV21 has 20A, not plain 20. PPSV23 has plain 20. Do not merge 20 / 20A. |
| PPSV23 | **None — unconjugated** | 1, 2, 3, 4, 5, 6B, 7F, 8, 9N, 9V, 10A, 11A, 12F, 14, 15B, 17F, 18C, 19A, 19F, 20, 22F, 23F, 33F | No carrier, no T-cell help from a carrier, no memory from a carrier. That is the PPSV23 vs. conjugate difference, not a missing ingredient in the host. |

## Improved Table 3 — Host immune dependency (Layer 3, new in this repeat)

From ChatGPT "What if the body is missing something?" section, kept as a framework table, not as a diagnosis for any person.

| Host component | Function | If deficient / missing, consequence for polysaccharide response | Vaccine can supply? |
|---|---|---|---|
| B lymphocytes | Recognize antigen, produce antibodies | Reduced antibody response | No — vaccine supplies antigen, host must supply B cells |
| Marginal-zone B cells | Respond to blood-borne polysaccharide antigens | Impaired polysaccharide responses | No |
| Immunoglobulins | Bind, neutralize, opsonize targets | Reduced functional antibodies | No — vaccine does not supply antibodies (except passive products, different category) |
| Complement proteins | Assist opsonization, bacterial clearance | Increased susceptibility to encapsulated bacteria | No |
| Spleen | Filters blood, supports responses to encapsulated organisms | Increased risk of invasive infection | No |
| Helper T cells | Support T-dependent responses | Impaired responses to conjugate vaccines | No — conjugate carrier needs host T cells to work |
| Phagocytes | Engulf, destroy opsonized organisms | Reduced bacterial clearance | No |

**Key distinction, from the same section:** A person can produce antibodies against a pneumococcal polysaccharide and still have an inadequate **functional** response. Antibody concentration alone does not always tell the whole story; antibody function, including opsonophagocytic activity, is another research measurement. [D, general, as reported in ChatGPT section — re-check per row against a primary source before print]

## Toxoid fourfold, preserved (his framing doctrine, Nov 4, ~1:16 PM)

In all toxoid work, present toxoids in his fourfold, helpful/useful framing, and do not reduce them to a single role:
1. Parts of the disease — derived from the disease toxin itself.
2. Parts of the vaccine — as toxoid vaccines in their own right, and as carriers in conjugate vaccines.
3. Parts of the human immunity response — the immune system reacts to the toxoid/carrier and makes the protective response.
4. Part of the key — in his framework, the key to understanding the vaccine–disease–immunity relationship.

The fourfold is [H] his framing. The carrier facts in Tables 1–2 are [D] documented, per Nov 4 deep research. The two are kept distinct, side by side, not merged into one claim.

## What can be concluded (narrowest, framework §7)

- TT, DT, and CRM197 are three different things, and their pneumococcal uses are product-specific, not class-wide, except for CRM197 as carrier-origin across most PCVs.
- Molecular, antigenic, and vaccine commonality are three different axes. A toxoid bridge that claims all three at once, for all five organisms in the ChatGPT synthesis, is [H] until each organism × axis cell is checked.
- Host immune function is a separate layer from vaccine composition. A missing host component is not a missing vaccine ingredient, and a vaccine cannot supply a host component.

## What cannot yet be concluded (GAP, framework §7)

- Which specific disease, reaction, and toxoid his original toxoid parallel postulate refers to — still GAP, his to dictate.
- Per-serotype fungal relationships for pneumococcal serotypes — GAP, not invented.
- Per-organism molecular inventory for meningococcus, tuberculosis, Cryptococcus, and Haemophilus in the toxoid bridge — GAP until each is built item by item, like the pneumococcal inventory already is.
- Hib, typhoid, Salmonella, Candida/Aspergillus, and combination-platform carrier cells marked GAP-in-scope above — not verified against labels in this repeat.

## Next verification step (framework §7)

1. For any print use: re-check each carrier cell in Table 2 against its product label / FDA insert, dated, before citing it as [D] in print.
2. For the toxoid bridge: build Layer 1 (organism molecular inventory) for meningococcus, tuberculosis, Cryptococcus, and Haemophilus, one organism at a time, with repeating-unit structure, linkages, and demonstrated cross-reactivity — or GAP per cell.
3. For the postulate: Douglas dictates the specific disease, reaction, and toxoid, and the mechanism, and it is tested item by item against Tables 1–3.

## Integrity checklist (framework §8, applied to this repeat)

- [x] Exact product, organism, molecule identified per row, where known; GAP where not.
- [x] User's terminology preserved ("toxoid," "fourfold," "key"); ambiguity flagged (TT vs. DT vs. CRM197; 20 vs. 20A; Synflorix vs. Pneumosil).
- [x] Source facts, outside research, inference, and unknowns distinguished with tiers.
- [x] Current source re-checked: Nov 4 deep research and Nov 4 audit, not memory alone.
- [x] Equal dosage units / exact strengths: not applicable to carrier table, except Cystex/AZO case in framework §3, kept separate.
- [x] Active vs. inactive: carrier vs. polysaccharide distinguished; PPSV23 unconjugated stated plainly.
- [x] Mechanism, indication, efficacy, regulatory status distinguished: carrier function ≠ disease antigen ≠ licensed indication.
- [x] Symptom improvement not treated as proof of cure: not applicable here, no symptom claim made.
- [x] Correlation not converted to causation: shared carrier ≠ shared disease, shared sugar ≠ shared immunity.
- [x] Unknowns stated: GAP section above.
- [x] Evidence cited close to claims: deep research, audit, ChatGPT import, framework, each named per section.
- [x] Rationale auditable, no hidden chain-of-thought claimed: this file is the trail.
