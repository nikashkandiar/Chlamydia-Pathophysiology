# CHLAMYDIA. — Pathophysiology & Reproductive Health Editorial

**Author:** Nikash Parasuraman  
**Module:** HBS3001 — Communicating Disease  
**Live Website:** [https://nikashkandiar.github.io/Chlamydia-Pathophysiology/](https://nikashkandiar.github.io/Chlamydia-Pathophysiology/)  
**Repository:** [https://github.com/nikashkandiar/Chlamydia-Pathophysiology](https://github.com/nikashkandiar/Chlamydia-Pathophysiology)

---

## Overview

**CHLAMYDIA.** is an interactive digital health and pathophysiology platform designed for **young women aged 15 to 25**. It translates the cellular and molecular biology of *Chlamydia trachomatis*—Singapore's most common legally notifiable sexually transmitted infection—into an accessible, non-stigmatizing visual narrative.

To balance effortless readability for a lay audience with complete academic rigor, the platform uses a **dual-layer pedagogical architecture**:
- **Primary Layer (Side A — Everyday Read):** Plain-English explanations, intuitive analogies, and custom 60fps 2D flat-vector cellular motion plates.
- **Secondary Layer (Side B — Cellular Science Unlocked):** Interactive flip-flashcards and a slide-out dual-level glossary that house the complete receptor, enzyme, cytokine, and tissue-remodeling mechanisms.

---

## How to Navigate the Website

### 1. Top Masthead & Global Controls
- **Reading Progress Bar:** A live horizontal indicator at the very top of the viewport tracks your progress through the 5 chapters.
- **Dark Mode / Light Mode Toggle:** Click the **Dark Mode** / **Light Mode** button in the top-right masthead to switch between the warm archival paper aesthetic (`#fcfbfa`) and the high-contrast obsidian dark theme (`#0D0B12`).
- **Word Translator & Glossary (`Glossary (9)`):** Click the **Glossary (9)** button in the header—or click any inline purple term button within the article text—to open the slide-out reference drawer. Every term includes both an **In Plain English** summary and a **Cellular Mechanism** definition, complete with live search filtering.

### 2. Chapter Directory (Desktop & Mobile)
- **Desktop View:** Use the sticky **Story Chapters** directory on the left column (paired with the **Visual Key**) to jump directly to any section.
- **Mobile & Tablet View:** Use the sticky 5-button navigation bar pinned to the bottom of the screen to switch chapters at any time:
  1. **Chapter 01 — Why Ages 15–25?:** Singapore CDA epidemiological data (`91.1 per 100,000`), the asymptomatic "silent" catch (`70–80%`), cervical ectopy, and the interactive **Anatomical to Cellular Bridge** map.
  2. **Chapter 02 — Healthy Baseline:** Interactive 3-tab explorer covering the cervical epithelium & mucus shield, fallopian tube ciliated & secretory peg cells, and baseline mucosal immunity.
  3. **Chapter 03 — Cellular Takeover:** Interactive 4-stage workbench detailing the biphasic life cycle of *Chlamydia trachomatis* (Elementary Body vs. Reticulate Body).
  4. **Chapter 04 — Clinical Pathology:** 4-outcome clinical matrix, 3-stage chronic inflammation & fibrosis motion plate, and an interactive **Days-to-Months Progression Timeline**.
  5. **Chapter 05 — Clinical Review:** 4-question interactive assessment quiz with instant scoring and cellular explanations.

---

## Interactive Modules & 2D Cellular Motion Plates

### Hero Plate: Intracellular Life Cycle (`Plate 0.1`)
- Demonstrates the continuous vertical cellular sequence: apical membrane invagination by an incoming Elementary Body (EB), internal inclusion pocket expansion, binary fission of coral Reticulate Bodies (RBs), condensation back into EBs, and basal hourglass extrusion.
- **Controls:** Click **01 Entry**, **02 Division**, **03 Condense**, or **04 Exit** at the bottom of the plate to lock and inspect a specific stage, click **Auto Scroll** to resume cycling, or click **Pause / Resume** to freeze the vector frame.

### Chapter 01: Anatomical to Cellular Bridge
- Click the numbered markers (**01**, **02**, **03**) directly on the reproductive tract vector diagram—or use the **Site 01 (Outer Cervix)**, **Site 02 (Inner Canal)**, and **Site 03 (Fallopian Tube)** buttons—to see how infection progresses from lower-tract entry to upper-tract tubal scarring.

### Chapter 02: Cervical Maturity & Fallopian Tube Simulators
- **System 01 (Cervical Gateway):** Toggle between **Ages 15–25 (Growing)** and **Mature Adult (26+)** to visualize how exposed single-layer columnar cells during cervical ectopy provide direct receptor targets for bacterial attachment.
- **System 02 (Fallopian Tube Transport):** Toggle between **Healthy Waving Cilia** and **Scarred & Blocked Tube** to compare synchronized ciliary ovum transport against post-inflammatory collagen occlusion.

### Chapter 03: 4-Stage Cellular Takeover & Dual-Exit Simulator
- Step through **Stage 01 (Attachment & Entry)**, **Stage 02 (Safe-Room & Cloning)**, **Stage 03 (Blocking Cell Death)**, and **Stage 04 (Dual Cellular Exit)**.
- In **Stage 04**, toggle between **1. Quiet Bubble (Extrusion)** and **2. Cell Burst (Lysis)** to compare non-lytic membrane pinching against host cell rupture.

### Chapter 04: Chronic Tissue Remodeling & Progression Timeline
- **Tissue Progression Plate:** Watch healthy blush epithelial cells progress through **01 Silent Stress** (rippling DAMP stress markers over a straight structural grid), **02 Immune Swelling** (clustering deep-plum leukocyte vectors and metaball cellular edema), and **03 Fibrotic Scarring** (contraction into rigid angular polygons that warp and tighten the surrounding structural grid).
- **Interactive Progression Timeline:** Click across **Days 1–3**, **Weeks 1–3**, **Months 1–4**, and **Months 6+** to compare outward symptoms against intracellular pathology.

### Dual-Sided Flip-Flashcards (Throughout Chapters 02–04)
- Every section defaults to **Flashcard Side A (Everyday Read)** for hassle-free comprehension.
- Click **Flip for Cellular Science** (or **Flip Card to Side B →**) on any card to reveal the underlying molecular mechanisms (HSPG/PDI binding, T3SS effectors, Inc proteins, ATP/lipid hijacking, CPAF apoptosis inhibition, DAMPs/TLR2/4, IL-8, TNF-α, and TGF-β-mediated fibroblast collagen deposition).

---

## Running Locally

This project is built as a zero-build, single-file production application (`index.html`) using React 18, Tailwind CSS, and mathematical 60fps SVG vector animations.

1. Clone the repository:
   ```bash
   git clone [https://github.com/nikashkandiar/Chlamydia-Pathophysiology.git](https://github.com/nikashkandiar/Chlamydia-Pathophysiology.git)