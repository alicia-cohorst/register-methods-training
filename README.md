# Register Methods Training

Independent self-training in the analytic methods used in register-based
epidemiology, done in R. The goal is to build practical skills in cohort
construction, survival analysis, confounding adjustment, and reproducible
workflows, using publicly available datasets and simulated data. No real
patient or register data are used.

## Plan (8 weeks)

| Weeks | Topic | Datasets |
|---|---|---|
| 1-2 | Data wrangling and joins | `nycflights13`, simulated register-style tables |
| 3-4 | Survival analysis, time-varying covariates, competing risks | `survival` package datasets |
| 5-6 | Confounding adjustment and propensity scores | `MatchIt::lalonde`, `causaldata::nhefs` |
| 7 | Missing data and sensitivity analyses | `mice::nhanes` |
| 8 | Reproducibility and a capstone report | Simulated data |

## Progress

- Week 1: joins, grouping and summaries, correlation, group comparisons
  (in progress)

## Structure

- `weeks/`: one Quarto document per week
- `R/`: reusable functions
- `output/`: figures and tables
- `notes/`: reading notes

## How to run

Open the project in RStudio, then render any file in `weeks/`.
Required packages are loaded at the top of each document.

## Author

Alicia Cohorst

Habit to build now:
At the end of each session: render the .qmd, commit with a specific message 
(“week 1: joined flights to planes, computed delays by airline”), and push. 
That gives you a dated progress log with no extra effort.

