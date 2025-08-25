# NumPy for Machine Learning — Project Log (Full)

This document captures the full context of building the **NumPy for Machine Learning — 15-Minute Daily Lessons** project, 
including book creation, repository setup, licensing, publishing workflow, and the complete README and index.md content.

---

## 📘 Project Overview
- Created 18 lessons + intro (Lesson 00–18) as Colab-ready notebooks.
- Packaged as book (PDF + EPUB) with cover page.
- Published to GitHub: [erickkendall/numpy-ml-lessons](https://github.com/erickkendall/numpy-ml-lessons).
- Goal: Free educational resource, optionally published on KDP.

---

## 📝 Key Files

### README.md
```markdown
# NumPy for Machine Learning — 15-Minute Daily Lessons

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](
https://creativecommons.org/licenses/by/4.0/)

Short, Colab-ready notebooks that cover **NumPy essentials for machine learning** in ~15 minutes per lesson.

---

## About
This series is a practical, hands-on introduction to NumPy for readers who want to review or strengthen
their understanding of **basic NumPy functionality** and its use in **ML workflows**.  
Each lesson is runnable in Google Colab and includes short exercises.

- 18 lessons + an intro
- ~15 minutes each
- Beginner-friendly, Python-first

---

## 📚 Lessons

| Lesson | Notebook | Open in Colab |
|--------|----------|----------------|
| 00 — Book Intro | `Lesson_00_Book_Intro.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_00_Book_Intro.ipynb) |
| 01 — Arrays & Basics | `Lesson_01_Arrays_Basics.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_01_Arrays_Basics.ipynb) |
| 02 — Indexing, Slicing & Masking | `Lesson_02_Indexing_Slicing_Masking.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_02_Indexing_Slicing_Masking.ipynb) |
| 03 — Boolean Indexing (New Dataset) | `Lesson_03_Boolean_Indexing_NewDataset.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_03_Boolean_Indexing_NewDataset.ipynb) |
| 04 — CSV, Headers & Sampling | `Lesson_04_CSV_Headers_Sampling.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_04_CSV_Headers_Sampling.ipynb) |
| 05 — Stacking & Combining | `Lesson_05_Stacking_Combining.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_05_Stacking_Combining.ipynb) |
| 06 — Statistical Summaries | `Lesson_06_Stats_Summaries.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_06_Stats_Summaries.ipynb) |
| 07 — NumPy vs Python Lists + Drills | `Lesson_07_Lists_vs_Numpy_Boolean_Drills.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_07_Lists_vs_Numpy_Boolean_Drills.ipynb) |
| 08 — Scaling & Standardization | `Lesson_08_Scaling_Standardization.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_08_Scaling_Standardization.ipynb) |
| 09 — Split, Concat & Reshape | `Lesson_09_Split_Concat_Reshape.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_09_Split_Concat_Reshape.ipynb) |
| 10 — Outliers (Z-score & IQR) + Viz | `Lesson_10_Outliers_Z_IQR_Viz.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_10_Outliers_Z_IQR_Viz.ipynb) |
| 11 — Linear Algebra Basics | `Lesson_11_Linear_Algebra_Basics.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_11_Linear_Algebra_Basics.ipynb) |
| 12 — Broadcasting Deep Dive | `Lesson_12_Broadcasting_Deep_Dive.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_12_Broadcasting_Deep_Dive.ipynb) |
| 13 — Aggregations, Grouping & Batching | `Lesson_13_Aggregations_Grouping_Batching.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_13_Aggregations_Grouping_Batching.ipynb) |
| 14 — Randomness & Reproducibility | `Lesson_14_Randomness_Reproducibility.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_14_Randomness_Reproducibility.ipynb) |
| 15 — Performance Tips | `Lesson_15_Performance_Tips.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_15_Performance_Tips.ipynb) |
| 16 — Advanced Indexing | `Lesson_16_Advanced_Indexing.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_16_Advanced_Indexing.ipynb) |
| 17 — Saving & Loading | `Lesson_17_Saving_Loading.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_17_Saving_Loading.ipynb) |
| 18 — Capstone: NumPy-Only ML Pipeline | `Lesson_18_Capstone_NumPy_Pipeline.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erickkendall/numpy-ml-lessons/blob/main/lessons/Lesson_18_Capstone_NumPy_Pipeline.ipynb) |

---

## 📖 Download the Book
- **PDF (with cover):** [book/Numpy_Lessons_Book_with_Cover.pdf](book/Numpy_Lessons_Book_with_Cover.pdf)  
- **EPUB (with cover):** [book/Numpy_Lessons_Book_with_Cover.epub](book/Numpy_Lessons_Book_with_Cover.epub)

---

## License
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](
https://creativecommons.org/licenses/by/4.0/)  

Content is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** License.  
You are free to share and adapt with attribution to **Erick Kendall**.

---

## Contributing
Improvements welcome! Open a PR or file an issue.

---

## Author
**Erick Kendall**  
Published to support learners who want a concise NumPy ramp-up for machine learning.
```

---

### index.md (GitHub Pages landing page)
```markdown
---
title: NumPy for Machine Learning — 15-Minute Daily Lessons
---

# NumPy for Machine Learning — 15-Minute Daily Lessons

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Short, Colab-ready notebooks that cover **NumPy essentials for machine learning** in ~15 minutes per lesson.

---

## About
This series is a practical, hands-on introduction to NumPy for readers who want to review or strengthen
their understanding of **basic NumPy functionality** and its use in **ML workflows**.  
Each lesson is runnable in Google Colab and includes short exercises.

- 18 lessons + an intro
- ~15 minutes each
- Beginner-friendly, Python-first

(lesson table identical to README.md)

---

## 📖 Download the Book
- **PDF (with cover):** [book/Numpy_Lessons_Book_with_Cover.pdf](https://github.com/erickkendall/numpy-ml-lessons/raw/main/book/Numpy_Lessons_Book_with_Cover.pdf)  
- **EPUB (with cover):** [book/Numpy_Lessons_Book_with_Cover.epub](https://github.com/erickkendall/numpy-ml-lessons/raw/main/book/Numpy_Lessons_Book_with_Cover.epub)
```

---

## 🔗 Links
- Repo: https://github.com/erickkendall/numpy-ml-lessons
- GitHub Pages (after enabling): https://erickkendall.github.io/numpy-ml-lessons/

---

## ✍️ Author
**Erick Kendall**  
Prepared with assistance from ChatGPT.
