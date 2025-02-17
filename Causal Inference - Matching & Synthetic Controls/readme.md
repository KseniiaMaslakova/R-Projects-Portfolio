# Causal Inference Analysis: Darfur Conflict and Peace Attitudes

This project explores the causal impact of direct harm on peace attitudes during the Darfur conflict using advanced causal inference techniques in R.

## **Project Overview**
Leveraging data from the `sensemakr` package, this analysis applied Genetic Matching to control for confounders like age, gender, occupation, past voting, household size, and village. The study found that individuals directly harmed by violence showed a significant increase in pro-peace attitudes.

## **Key Methods & Tools**
- **Genetic Matching** for dynamic covariate balance optimization.
- **Sensitivity Analysis** using `sensemakr` to assess robustness.
- **R Libraries:** `sensemakr`, `MatchIt`, `rgenoud`, `cobalt`.

## **Findings**
Direct harm positively influenced peace attitudes, with sensitivity analysis confirming the robustness of results even when accounting for unobserved confounders.

## **Project Files**
- `darfur_analysis.ipynb` – Full R analysis notebook (Google Colab).
- `darfur_report.pdf` – Project discussion and detailed explanation.

## **How to Run**
Clone the repository, open the `.ipynb` in Google Colab, and install required R libraries (`sensemakr`, `MatchIt`, `rgenoud`).

## **Contact**
Feel free to reach out for collaboration or questions!
