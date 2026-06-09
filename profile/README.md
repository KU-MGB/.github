<div align="center">

# 🧬 Microbial Genomics & Biodegradation
### KU‑MGB · University of Copenhagen

**Computational discovery of enzymes that break the strongest bond in organic chemistry — the carbon–fluorine bond of PFAS.**

[![Location](https://img.shields.io/badge/📍_Copenhagen-Denmark-901A1E?style=flat-square)](https://www.ku.dk/english/)
[![Institution](https://img.shields.io/badge/University_of_Copenhagen-PLEN-002e5f?style=flat-square)](https://plen.ku.dk/english/)
[![Focus](https://img.shields.io/badge/Focus-PFAS_Defluorination-1B7837?style=flat-square)](#-research-focus)
[![Website](https://img.shields.io/badge/🌐_Website-KU--MGB-0072B2?style=flat-square)](https://ku-mgb.github.io)

</div>

---

## 🔍 About us

We are a research group at the **Department of Plant and Environmental Sciences (PLEN), University of Copenhagen**, working at the interface of microbial genomics, enzymology and machine learning. We build reproducible, physics‑aware AI pipelines that mine microbial sequence space for enzymes capable of degrading **PFAS** ('forever chemicals') and other persistent halogenated pollutants.

Our central question: *which natural enzymes already encode the geometry needed to cleave a C–F bond — and can we find them computationally, at scale, before a single experiment?*

## 🧠 Research focus

- **PFAS‑degrading enzymes & biocatalysts** — fluoroacetate dehalogenases (FAcD), haloacid dehalogenases (HAD) and related hydrolases.
- **Mechanism‑first enzyme screening** — we rank candidates by catalytic geometry (Sɴ2 near‑attack conformation, active‑site fidelity), not by binding affinity alone.
- **AI structure prediction & molecular simulation** — Boltz‑2 complex prediction, molecular dynamics and QM/MM reaction‑coordinate analysis.
- **Environmental biotechnology** — translating computational hits toward sustainable, enzymatic remediation.

## ⚙️ Our approach

Every pipeline we build shares one mechanism‑first philosophy:

```
Input sequences + PFAS panel  →  sanitise & align to a reference enzyme
   →  AI complex prediction (Boltz‑2)  →  active‑site & Sɴ2 geometry scoring
   →  tiered mechanistic ranking (Perfect → Poor)  →  MD + QM/MM validation
   →  ranked, interpretable candidate enzymes
```

Before its score counts, a candidate must **reproduce the catalytic machinery** — nucleophile, carboxylate clamps, catalytic base/acid and the halide/fluorine stabilisers. We keep every threshold in a single configuration source, so our results are fully reproducible.

## 🧩 Key projects

| Repository | What it does | Stack |
|---|---|---|
| [**FAcDs_PFAS‑27_Defluorination**](https://github.com/KU-MGB/FAcDs_PFAS-27_Defluorination) | Mechanism‑aware screening of **fluoroacetate dehalogenase (FAcD)** variants against a 27‑compound PFAS panel — Boltz‑2 prediction, Sɴ2/NAC geometry, tiered ranking, MD & QM/MM validation. | Python |
| [**HADs_PFAS‑27_Defluorination**](https://github.com/KU-MGB/HADs_PFAS-27_Defluorination) | The same physics‑aware pipeline retargeted to **haloacid dehalogenases (HAD)**; fully UniProt‑ID‑driven so any reference enzyme can be screened. | Python |
| [**Whole_Proteome_TFA_Defluorination**](https://github.com/KU-MGB/Whole_Proteome_TFA_Defluorination) | Proteome‑wide search for enzymes that defluorinate **trifluoroacetate (TFA)**, the terminal PFAS dead‑end metabolite. | Python |
| [**KU‑MGB.github.io**](https://github.com/KU-MGB/KU-MGB.github.io) | Group website and interactive result dashboards. | TypeScript |

> Several research repositories are currently **private** while under review, and will be opened on publication.

## 🛠️ Methods & tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Boltz-2](https://img.shields.io/badge/Boltz--2-Structure_Prediction-5A2D82?style=flat-square)
![Schrödinger](https://img.shields.io/badge/Schrödinger-Desmond_·_QSite-EE3124?style=flat-square)
![HMMER](https://img.shields.io/badge/HMMER_·_BLAST-Homology-0072B2?style=flat-square)
![Foldseek](https://img.shields.io/badge/Foldseek_·_MMseqs2-Structure_Search-1B7837?style=flat-square)
![ESM-2](https://img.shields.io/badge/ESM--2_·_UMAP-Embeddings-D55E00?style=flat-square)
![pandas](https://img.shields.io/badge/pandas_·_NumPy-Data-150458?style=flat-square&logo=pandas&logoColor=white)

## 👥 Team

| | |
|---|---|
| **Shaban Ahmad** | Lead developer — AI‑driven bioinformatics & pipeline architecture · [Research profile](https://researchprofiles.ku.dk/en/persons/shaban-ahmad/) |
| **Benedetta Togni** | MSc dissertation — environmental biotechnology |
| **Tue K. Nielsen** | Principal supervisor · [Research profile](https://researchprofiles.ku.dk/en/persons/tue-kj%C3%A6rgaard-nielsen/) |

## 🌐 Get in touch

🔗 **Website:** [ku-mgb.github.io](https://ku-mgb.github.io)  ·  ✉️ **Contact:** [shaban.ucph@gmail.com](mailto:shaban.ucph@gmail.com)

<div align="center">
<sub>Department of Plant and Environmental Sciences · University of Copenhagen · Denmark</sub>
</div>
