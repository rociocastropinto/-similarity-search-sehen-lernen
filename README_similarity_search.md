# Similarity Search — Interactive Learning Unit

An interactive tutorial and implementation guide for the **Similarity Search** feature on the [Sehen Lernen platform](https://sehenlernen.uni-goettingen.de), developed for the M.A. Digital Humanities programme at Georg-Augustus-Universität Göttingen.

**🔴 Live mockup:** [similarity-search-sehen-lernen.netlify.app](https://similarity-search-sehen-lernen.netlify.app/)  
**🎥 Mockup video:** [youtu.be/n-bnoCd0CDA](https://youtu.be/n-bnoCd0CDA)

---

## What this project is

A revised learning unit (Mar 2026) teaching students how to use image similarity search for art history research. The unit uses a case study comparing Early Expressionist portrait styles across male and female painters (1900–1920) to demonstrate how CNN and HOG feature methods produce different — and interpretable — results.

The interactive HTML prototype simulates the full learning experience across 5 tabs. It does not connect to the live Sehen Lernen database; search results in Tab 5 are simulated using methodological reasoning.

---

## Files

| File | Description |
|---|---|
| `similarity_search_mockup.html` | Full interactive prototype (open in browser) |
| `Rocio_Castro_Pinto_-_Similarity_Search_Übung_-_WiSe26.pdf` | Implementation guide and documentation (12 pp.) |

---

## Learning Unit Structure

The tutorial is structured across 5 tabs, following a Concept → Method → Metrics → Practice → Evaluation arc:

**Tab 1 — Concept: What Is Similarity Search?**  
Feature vectors, the library analogy, Human vs Computer Vision comparison table, Single vs All and Pairwise search modes. Basic + Advanced tracks.

**Tab 2 — Feature Methods**  
Five methods compared: CNN, HOG, SIFT, Histogram, Manuscript. Decision tree for method selection. Challenge: Breaking CNN.

**Tab 3 — Distance Metrics**  
Cosine, Euclidean, Manhattan distances. Interactive metric explorer. Key rule: scores are always relative to the dataset.

**Tab 4 — Practical Exercises**  
Three exercises (Basic × 2, Advanced × 1) with dataset, task, and evaluation criteria specified. Includes the "Can You Beat the Algorithm?" and "The Manuscript Hunt" challenges.

**Tab 5 — Case Study: Early Expressionism**  
Research question: do male and female Expressionist painters (1900–1920) produce visually distinguishable portrait styles under CNN and HOG? Dataset: 60 paintings from WikiArt.org, 6 artists, 10 portraits each. Three hypotheses tested: gender clustering (H1), contour divergence (H2), nationality as outlier factor (H3).

---

## Case Study: The Six Artists

| Artist | Nationality | Style signature |
|---|---|---|
| Paula Modersohn-Becker | DE | Simplified forms, warm muted tones |
| Käthe Kollwitz | DE | Heavy line, dark tones, grief and solidarity |
| Edvard Munch | NO | Psychological intensity, swirling vivid colour |
| Egon Schiele | AT | Hard black outlines, angular distortions |
| Oskar Kokoschka | AT | Agitated brushwork, surface tension |
| Ernst L. Kirchner | DE | Flat colour, heavy contour |

---

## Prototype Limitations

- Search results in Tab 5 are **simulated** — not actual algorithm output
- Orange visualisations (scatter plot, heat map) are referenced but not embedded
- Videos are Clipchamp placeholders; screen-recorded versions needed for live platform
- No live connection to the Sehen Lernen database

---

## Technical Stack

- Interactive HTML/CSS/JS prototype (single file, no dependencies)
- Deployed via Netlify
- Case study data sourced from WikiArt.org (open access)
- Orange Data Mining referenced for scatter plot and heat map visualisation

---

## What Changed in the Mar 2026 Revision

Applied professor feedback (Feb 24, 2026): consistent Concept → Method → Metrics → Exercise → Evaluation outline; TIP and KEY boxes as mnemonics; competency summary on cover; catchy exercise titles (*The Riddle of the Similar Stranger*, *Breaking CNN*); Human vs Computer Vision comparison table; Basic/Advanced split; research question moved to prominent banner; annotated screenshot instructions; Orange question cards per visualisation type.

---

## Author

**Rocío Castro Pinto**  
M.A. Digital Humanities (Computational Social Sciences)  
Georg-Augustus-Universität Göttingen · WiSe 2025/26  
[linkedin.com/in/rociocastropinto](https://linkedin.com/in/rociocastropinto)
