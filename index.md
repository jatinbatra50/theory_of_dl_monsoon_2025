---
layout: page
title: "CSS.428.1 – Introduction to Theory of Deep Learning (Monsoon 2025)"
permalink: /
---

> **How to edit:** Change the *Topic* text for each week and, once you upload the PDF to `assets/notes/`, the **Notes (PDF)** link will work automatically. See **How to upload lecture notes** below.

**Instructor:** Jatin Batra  
**Schedule:** Thursdays, 2:00–3:30 PM  
**Room:** A-238  
**Email:** [jatinbatra50@gmail.com](mailto:jatinbatra50@gmail.com)  
**Textbook:** *Learning theory from first principles* — Francis Bach (Chapter 9 and relevant parts of Chapters 3, 4, 5, 7, 8, 12, 14).

## Course Description

This mini-course serves as a take-off point for research in theory of deep learning,
with neural networks as the prototypical setup. We will rigorously cover basics
of three important aspects of this theory:

1. **Approximation theory.** In this part, we will answer the question “How
   well do neural network architectures approximate functions we want to
   model?”

2. **Implicit bias of overparameterized models.** Generalization power
   of modern deep learning cannot be easily explained as the number of pa-
   rameters is often of the same order as the number of training samples. In
   this part, we will initiate an understanding of implicit bias which captures
   additional properties enjoyed by natural training procedures for overpa-
   rameterized models that are not captured explicitly, and which could hold
   the key to generalization.

3. **(Non)-convex optimization.** Training procedures for modern deep
   learning require non-convex optimization. In this part, we will study
   their convergence, which requires going beyond classical understanding
   of convex optimization.

## Weekly Outline (edit me)

> **Tip:** Keep the filenames `week-01.pdf`, `week-02.pdf`, … `week-15.pdf` in `assets/notes/` for zero‑config links.

| Week | Topic (edit me) | Notes |
|:---:|:-----------------|:-----:|
| 01 | Topic | [Notes (PDF)](assets/notes/week-01.pdf) |
| 02 | Topic | [Notes (PDF)](assets/notes/week-02.pdf) |
| 03 | Topic | [Notes (PDF)](assets/notes/week-03.pdf) |
| 04 | Topic | [Notes (PDF)](assets/notes/week-04.pdf) |
| 05 | Topic | [Notes (PDF)](assets/notes/week-05.pdf) |
| 06 | Topic | [Notes (PDF)](assets/notes/week-06.pdf) |
| 07 | Topic | [Notes (PDF)](assets/notes/week-07.pdf) |
| 08 | Topic | [Notes (PDF)](assets/notes/week-08.pdf) |
| 09 | Topic | [Notes (PDF)](assets/notes/week-09.pdf) |
| 10 | Topic | [Notes (PDF)](assets/notes/week-10.pdf) |
| 11 | Topic | [Notes (PDF)](assets/notes/week-11.pdf) |
| 12 | Topic | [Notes (PDF)](assets/notes/week-12.pdf) |
| 13 | Topic | [Notes (PDF)](assets/notes/week-13.pdf) |
| 14 | Topic | [Notes (PDF)](assets/notes/week-14.pdf) |
| 15 | Topic | [Notes (PDF)](assets/notes/week-15.pdf) |

## How to upload lecture notes (PDF)

1. In your GitHub repository, create the folder: `assets/notes/` (same level as `index.md`).  
   – If you already cloned locally, just make that folder on your machine.  
2. Name your files exactly as: `week-01.pdf`, `week-02.pdf`, … `week-15.pdf`.  
3. Upload using either method:  
   - **GitHub web UI:** Click **Add file → Upload files**, drag the PDFs into `assets/notes/`, and **Commit**.  
   - **Git (local):**
     ```bash
     mkdir -p assets/notes
     cp /path/to/your/week-01.pdf assets/notes/
     git add assets/notes/week-01.pdf
     git commit -m "Add notes for week 01"
     git push origin main
     ```
4. That’s it — the links in the table above (e.g., `assets/notes/week-01.pdf`) will work on both GitHub and GitHub Pages.  
   If you ever change the folder or filenames, just update the links in the table.

---

*Last updated: {{ site.time | date: "%-d %b %Y" }}*
