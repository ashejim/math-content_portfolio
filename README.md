# Mathematics Content Portfolio — James Ashe

A curated collection of my mathematics teaching materials, research talks, and a
computational research project. Everything here I authored: lecture notes, course
materials, slides, exams and worked solutions (all typeset in LaTeX/LyX), research
presentations, and a grant-funded undergraduate research project.

The material spans **college-algebra through graduate-level abstract algebra**, plus
**research in circle packing / discrete conformal geometry** and an
**NP-hard optimization project** (the Thomson problem). It is meant to demonstrate
mathematical range, clarity of technical exposition, and the ability to produce
polished, reproducible content.

---

## Contents

| Section | What's inside |
|---|---|
| [`teaching/`](teaching/) | Full materials for 9 university courses — notes, slides, worksheets, exams, and worked solutions. |
| [`research/`](research/) | Talks on my research in **generalized branching for circle packings** (thesis defense, AMS Sectional, invited colloquium). |
| [`thomson-problem/`](thomson-problem/) | A grant-funded computational project modeling the **Thomson problem** with circle packings, including data and the conference poster. |

---

## Teaching

Nine courses I taught at **Johnson C. Smith University** (JCSU, 2012–2014) and
**Mars Hill University** (MHU, 2014), from introductory to advanced. Each folder is
organized into `lecture-notes/`, `assignments/`, `exams-and-reviews/`, and a syllabus.

| Course | Level | Highlights |
|---|---|---|
| [Topics in Algebra (MTH 439)](teaching/topics-in-algebra-mth439/) | Advanced undergrad | **Textbook-style lecture notes** on rings, ideals, factor rings, and homomorphisms — with `.tex` source. |
| [Abstract Algebra (MTH 335)](teaching/abstract-algebra-mth335/) | Advanced undergrad | Full course: groups through rings, with LaTeX-source notes. |
| [Linear Algebra (MTH 336)](teaching/linear-algebra-mth336/) | Undergrad | Complete exam/solution sets and lecture notes. |
| [Calculus III (MTH 331)](teaching/calculus-3-mth331/) | Undergrad | Multivariable calculus slides and worksheets. |
| [Calculus II (MTH 232)](teaching/calculus-2-mth232/) | Undergrad | Techniques of integration, series. |
| [Precalculus (MTH 137)](teaching/precalculus-mth137/) | Intro | |
| [College Algebra (MTH 131)](teaching/college-algebra-mth131/) | Intro | Large worksheet and practice-exam bank. |
| [Finite Math (MTH 107, MHU)](teaching/finite-math-mth107-mhu/) | Intro | Logic, sets, combinatorics, probability — full slide decks. |
| [Finite Math (MTH 132, JCSU)](teaching/finite-math-mth132-jcsu/) | Intro | |

See [`teaching/README.md`](teaching/) for a fuller description.

## Research

My research is in **circle packing** — a discrete analogue of conformal geometry.
A circle packing realizes any triangulation of a surface as a configuration of
mutually tangent circles; by the Koebe–Andreev–Thurston theorem such a packing exists
and is unique up to Möbius transformation. My work develops the theory of
**generalized branching** in these packings.

- [`research/thesis-defense/`](research/thesis-defense/) — thesis defense presentation.
- [`research/ams-sectional-2014/`](research/ams-sectional-2014/) — talk at the AMS Sectional Meeting, Knoxville, 2014 (LaTeX/Beamer source included).
- [`research/unca-colloquium-2014/`](research/unca-colloquium-2014/) — invited junior colloquium, UNC Asheville.
- [`research/jcsu-math-club-2013/`](research/jcsu-math-club-2013/) — expository talk for the JCSU math club.

## Computational project — the Thomson problem

The **Thomson problem** (number 7 on Smale's list of problems for the 21st century)
asks for the minimum-energy configuration of *N* electrons on a sphere. It is NP-hard
in general, so progress relies on computation. In this **HBCU-UP grant-funded**
undergraduate research project, we model the problem with **circle packings**,
obtaining discrete configurations that experimentally approximate — and appear to
converge to — the true energy minima, and we show how the models can be manipulated
combinatorially.

- [`thomson-problem/`](thomson-problem/) — conference poster, grant proposal, computed data sets, and a summary of results.

---

## About the source material

All documents were authored in **LaTeX** (via LyX). Where useful, the editable
`.tex` source is included alongside the compiled PDF (see the `latex-source/` folders
and the research/Thomson `.tex` files). The advanced-algebra lecture notes are
structured so they can be developed further into **Jupyter Books**.

## Author

**James Ashe** — mathematician and educator. Former mathematics faculty at
Johnson C. Smith University and Mars Hill University. Research in circle packing and
discrete conformal geometry.

*Contact: ashejim@gmail.com*

## License

Course materials and notes in this repository are shared for portfolio and educational
purposes. Please contact me before reusing them in your own courses or publications.
