# The Thomson Problem via Circle Packings

A grant-funded (**HBCU-UP**) undergraduate research project applying circle packings
to a classical optimization problem.

## The problem

The **Thomson problem** asks for the configuration of $N$ electrons on the unit sphere
that minimizes the electrostatic (Coulomb) energy

$$E = \sum_{i \lt j} \frac{1}{\lvert p_i - p_j \rvert}.$$

It is **number 7 on Smale's list** of problems for the 21st century. Exact solutions
are known only for a few special values of $N$; in general the problem is **NP-hard**,
so progress relies on computational methods. The best known minima for most $N \lt 1000$
have been found numerically.

## Our approach

We model the Thomson problem with **circle packings**. Each candidate configuration is
represented by a triangulation of the sphere, realized as a circle packing whose
tangency structure encodes the arrangement of points. These discrete models:

- are experimentally found to be **good approximations** of the minimum-energy
  configurations, appearing to **converge** to the true energy as $N$ grows;
- can be **manipulated combinatorially** (by local moves on the triangulation), which
  we conjecture can be used to search for energy minima.

## Contents

| File / folder | Description |
|---|---|
| [`Thomson_problem_Poster_HBCUP_project.pdf`](Thomson_problem_Poster_HBCUP_project.pdf) | Conference poster (with `.tex` source). |
| [`mini-grant_proposal_Thomson_problem.pdf`](mini-grant_proposal_Thomson_problem.pdf) | Funded grant proposal. |
| [`mini-grant_Thomson_problem_abstract.pdf`](mini-grant_Thomson_problem_abstract.pdf) | Extended abstract of the project and mathematical background. |
| [`Circle_Packing_Project_Thomson_data.pdf`](Circle_Packing_Project_Thomson_data.pdf) | Summary of computed results. |
| [`data/`](data/) | Computed configurations and energies — 53 data sets for point counts from 15 up to 20,000 (`*l` = from a low/minimizing start, `*r` = from a random start; `*_low` / `*_rand` likewise). |
| `data.csv`, `testdata.csv` | Tabulated results. |
| `biblatex_jashe.bib` | Bibliography. |

## Data format

The files in [`data/`](data/) contain point configurations and their computed energies
produced during the project. Filenames encode the number of points (e.g. `2000l`,
`10kr`, `525_low.txt`) and the initialization used (`l`/`low` = low-energy start,
`r`/`rand` = random start), supporting comparison of how the circle-packing model
converges from different starting conditions.
