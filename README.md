# Systematic Analysis of Critical Factors for Value Management in Cybersecurity

**Journal:** IEEE Latin America Transactions
**Manuscript ID:** 10932

**Authors:**
- Vicente Merchán-Rodríguez — [ORCID](https://orcid.org/0000-0002-4456-0689) — vrmerchan@espe.edu.ec
- Danny Zambrano-Vera — [ORCID](https://orcid.org/0000-0002-5920-0790) - dizambrano@espe.edu.ec

**Affiliation:**
Universidad de las Fuerzas Armadas ESPE, Sangolquí, Ecuador
- V. Merchán-Rodríguez — Department of Computer Science
- D. Zambrano-Vera — Department of Economics and Business

---

## About this repository

This repository contains the revised manuscript files and publication-ready graphical assets for the systematic literature review (SLR) *"Systematic Analysis of Critical Factors for Value Management in Cybersecurity."* The study applies the PRISMA methodology across the Semantic Scholar, IEEE Digital Library, Scopus, and ScienceDirect databases (950 records screened down to 49 studies) to identify the critical success factors (CSF) underpinning value management in the cybersecurity strategies of telecommunications organizations.

The files here reflect the editorial revision cycle for the journal: manuscripts with reviewer-requested layout fixes (two-column figure rescaling, descriptive captions, table restructuring) and a full set of the article's figures rebuilt as scalable vector graphics (SVG) for high-quality reproduction in print and online.

---

## 📁 Repository structure

```
├── manuscript/     # PDF manuscript and graphical abstract images
├── figures/        # Vector (SVG) versions of all article figures
├── code/   # Code and DataBase
```

---

## 📄 Manuscript files

| File | Description |
|---|---|
| `10932 - Article text.pdf | **Latest revised manuscript.** 
| `10932 - Graphical Abstract.png | **Latest graphical abstract images.** 

---

## 🖼️ Figures (vector SVG)

All figures were rebuilt as native SVG (editable text, shapes, and paths — not embedded raster images) to guarantee crisp reproduction at any print size and to allow direct color/label edits in any vector editor (Inkscape, Illustrator, Figma, etc.).

| File | Figure | Description |
|---|---|---|
| `Fig_1_Phases_of_the_systematic_review_of_the_literature.svg` | Fig. 1 | Three-phase SLR process (planning, execution, reporting), adapted from Kitchenham & Charters. |
| `Fig_2_PRISMA_Flow_Diagram.svg` | Fig. 2 | PRISMA flow diagram (identification → screening → eligibility → included), 950 → 49 studies. |
| `Fig_3_Temporal_distribution.svg` | Fig. 3 | Temporal distribution of the 49 included studies by publication year (2020–2025). |
| `Fig_4_Productive authors.svg` | Fig. 4 | Productive authors. |
| `Fig_5_Journal_Distribution.svg` / `.png` | Fig. 5 | Distribution of the 49 studies across publishing journals (donut chart with legend). |
| `Fig_6_Distribution_of_citations.svg` | Fig. 6 | Histogram and density curve of citation counts across the 49 studies. |
| `Fig_7_Correlation_analysis.svg` | Fig. 7 | Scatter plot and linear regression of publication year vs. citation count. |
| `Fig_8_Impact_by_category.svg` | Fig. 8 | Average citation count per critical success factor (CSF) category — single-line labels. |
| `Fig_9_Evolution_of_CSF_by_year.svg` | Fig. 9 | Heat map of publication counts per CSF category and year — single-line labels. |
| `Fig_10_World_cloud.svg` | Fig. 10 | Word cloud of the most frequent terms in the titles of the included studies. |
| `Fig_11_Publication_clustering.svg` | Fig. 11 | K-means clustering of studies by publication year and citation count. |
| `Fig_12_Emerging_topics_Discovery.svg` | Fig. 12 | Frequency of key phrases identified through text mining — single-line labels. |

---

## 🎨 code

| File | Description |
|---|---|
| `10932 - Codigo Python` | Code: the complete bibliometric analysis and figure-generation pipeline for the article "Systematic Analysis of Critical Factors for Value Management in Cybersecurity.". |
| `DataBase - CSF de la gestion del valor` | DataBase: CSV bibliographic export containing metadata—authors, titles, abstracts, citations, DOIs—for the systematic review's included studies. |

---

## 💻 Requirements

- **Manuscript files:** any PDF viewer (for `.pdf`).
- **Figures:** any modern web browser or vector editor (Inkscape, Adobe Illustrator, Figma) to view or edit the `.svg` files; no special software is required to view `.png` files.
- **Code:** Software environment: Python 3.x with Jupyter/Colab, plus the libraries pandas, matplotlib, seaborn, numpy, wordcloud, and scikit-learn installed via pip. For file format conversion: the code expects an .xlsx file via pd.read_excel, so the CSV must either be converted to Excel or the loading line changed to pd.read_csv.

---

## License

This repository is proposed for academic and research purposes only.

---

## ✉️ Contact

For questions about the manuscript or replication of the review methodology:
**vrmerchan@espe.edu.ec**
