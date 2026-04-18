# Physical Organic Chemistry Internship
## Making organic chemistry concepts real using mass spectrometry

**Host:** CSOB group / IPCM / Sorbonne University  
**Location:** Campus Jussieu, 4 Place Jussieu, 75005 Paris  
**Duration:** 5 weeks, full time (7 hours/day, 5 days/week = 175 hours total)  
**Level:** L2 / L3 / early M1 (chemistry or related)  
**Supervisor:** Dr. Alexandra Tsybizova  
**Contact:** alexandra.tsybizova@sorbonne-universite.fr

---

## What this internship is about

You will study a reaction you already know from organic chemistry — the **retro-Diels-Alder (RDA) reaction** — using tandem mass spectrometry (MS/MS). The reaction happens inside the mass spectrometer: you activate a molecule with controlled energy and watch it fragment. By changing the energy, you can explore how reaction pathways depend on activation barriers.

This connects three things you may have seen separately:
- **Organic chemistry** — the retro-Diels-Alder mechanism, pericyclic reactions, Woodward-Hoffmann rules
- **Physical chemistry** — activation energy, kinetic vs. thermodynamic control, energy profiles
- **Analytical chemistry** — mass spectrometry, collision-induced dissociation, product ion spectra

By the end of the internship, you will have done a complete, small-scale research project: literature review, experiment, data analysis, computation, and a written report with oral presentation.

---

## The chemical system

The reaction studied is the **retro-Diels-Alder fragmentation of flavonoids** under collision-induced dissociation (CID). Flavonoids are natural polyphenolic compounds with a characteristic A/B/C ring structure. Under MS/MS conditions, the C ring undergoes retro-[4+2] cycloreversion, producing diagnostic fragment ions that allow identification of the compound class and substitution pattern.

This system is ideal because:
- The RDA reaction is taught in undergraduate organic chemistry
- The fragmentation is well-documented in the literature
- The barrier can be measured experimentally (breakdown curves) and computed (autodE/xTB)
- The orbital symmetry argument (Woodward-Hoffmann) applies directly

---

## Weekly structure

Each week has a concrete output that becomes one chapter of the final report.

| Week | Topic | Report chapter produced |
|------|-------|------------------------|
| 1 | Literature search and scientific writing | Background |
| 2 | MS/MS measurements and breakdown curves | Experimental |
| 3 | Data analysis and E₀ extraction | Results & Analysis |
| 4 | Quantum chemical calculations (autodE/xTB) | Computational Results |
| 5 | Final report assembly and oral presentation | Complete report + talk |

---

## Final deliverables

- **Written report** in LaTeX (Overleaf), assembled from the weekly chapters
- **Oral presentation** (~20 min + questions) at the end of week 5

---

## Repository structure

```
/
├── README.md                  ← this file
├── SUPERVISOR_NOTES.md        ← internal planning document (not for students)
├── STATUS.md                  ← current progress tracker
├── week1_literature/          ← instructions, templates, exercises
├── week2_ms_acquisition/      ← instructions, example data
├── week3_data_analysis/       ← instructions, analysis scripts
├── week4_computation/         ← instructions, autodE/xTB setup (reuses icc-2023 session 2)
└── week5_writing/             ← report template, presentation guidelines
```

---

## Prerequisites

Students should have completed basic undergraduate courses in organic, physical, and analytical chemistry. No prior experience with mass spectrometry, LaTeX, or quantum chemistry software is required — these are taught during the internship.
