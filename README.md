# Mathematics Content Portfolio — James Ashe

A curated collection of my mathematics teaching materials, research talks, expository
talks for general audiences, and a computational research project. Everything here I
authored: lecture notes, course materials, slides, exams and worked solutions (all
typeset in LaTeX/LyX), research presentations, and a grant-funded undergraduate
research project.

The material spans **college-algebra through graduate-level abstract algebra**, plus
**research in circle packing / discrete conformal geometry** and an
**NP-hard optimization project** (the Thomson problem) — from full university course
archives to **recent (2023) activity-style practice materials** authored at WGU. It
is meant to demonstrate mathematical range, clarity of technical exposition, and the
ability to produce polished, reproducible content.

---

## Contents

| Section | What's inside |
|---|---|
| [`recent-work/`](recent-work/) | **Recent (2023) practice sets and reference sheets** authored at WGU — concise, activity-style materials with answer keys, all with `.tex` source and a shared house style file. |
| [`teaching/`](teaching/) | Full materials for 9 university courses — notes, slides, worksheets, exams, and worked solutions. |
| [`research/`](research/) | Talks on my research in **generalized branching for circle packings** (thesis defense, AMS Sectional, invited colloquium). |
| [`expository-talks/`](expository-talks/) | **Deep mathematics for general audiences** — Cauchy rigidity, the Art Gallery Theorem, circle packing, Cantor's infinities — with animated slide sequences. |
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

## Recent work (2023) — WGU practice materials

Concise, self-study worksheets and reference sheets authored as a course
instructor at **Western Governors University** (competency-based, online):
targeted practice sets with answer keys for discrete mathematics and
algorithms, designed for students preparing for objective competency
assessments. All include editable LaTeX source and share a house style file
for a consistent worksheet format. See [`recent-work/`](recent-work/).

## Professional assessment authoring

Beyond the classroom materials in this repository, I have authored and revised
assessment content professionally (the content itself is proprietary and not
reproduced here):

- **Standardized exam item writing** — authored full rewrites/parallel forms
  of official standardized mathematics exams, including the **ETS Praxis 5003**
  (elementary mathematics) and the **NES II** exam series, in LaTeX with
  complete answer keys — item writing, distractor design, and form parallelism
  to specification.
- **Competency-based performance assessments** at WGU, including assessments
  with objective quality gates for the **BS in AI Engineering** program.
- **Original evaluation design for AI systems** — a
  [math-reasoning benchmark](https://github.com/ashejim/eval-benchmark)
  pairing objective answer keys with step-level rubrics for grading
  mathematical reasoning.

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

## Expository talks

Four talks that bring real mathematics to general audiences — faculty seminars and
student outreach events. Each folder has the full slide deck (PDF), **animated GIFs of
the key overlay sequences** (the arguments unfold visually, one move at a time), and
self-contained LaTeX/Beamer source.

| Talk | One-line pitch |
|---|---|
| [Cauchy's Rigidity Theorem](expository-talks/cauchy-rigidity-theorem/) | Why a convex polyhedron cannot flex — a 200-year-old proof with a famous bug in it. |
| [The Art Gallery Problem](expository-talks/art-gallery-problem/) | How many guards does a gallery need? Fisk's one-slide triangulation + 3-coloring proof. |
| [Circle Packing: A Visual Introduction](expository-talks/circle-packing/) | My research area with no prerequisites — every idea shown as a picture. |
| [What is a Proof? …What is Math?](expository-talks/what-is-a-proof-what-is-math/) | Proof, infinity, and Cantor's diagonal argument, for people who don't think they like math. |

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
