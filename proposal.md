Final Project Proposal
================
Xiaobo Shen, Harrison Wei, Yikai Lu, Jiaqi Xie
2026-11-13

# Maternal Smoking During the First Trimester and Infant Birth Weight in the United States, 2023–2025

## Group Members

- Xiaobo Shen (xs2635)
- Harrison Wei (hw3206)
- Yikai Lu (YL6375)
- Jiaqi Xie (jx2724)

## Motivation and Research Questions

We will examine how infant birth weight varies with reported
first-trimester cigarette use among U.S. singleton live births from 2023
through 2025. Mean birth weight describes the average difference in
grams, while the percentage of infants weighing less than 2,500 grams
tells us how often each group experiences low birth weight. Considering
both measures allows us to compare overall differences in birth weight
as well as differences in the prevalence of a clinically important
adverse birth outcome.

Our project will address three main research questions:

1.  How does mean infant birth weight differ between mothers who
    reported smoking during the first trimester and mothers who reported
    no cigarette use during the first trimester?

2.  How does the percentage of low-birth-weight infants, defined as
    birth weight below 2,500 grams, differ between these two groups?

3.  For each year, what is the percentage-point difference in
    low-birth-weight prevalence between infants born to mothers with
    reported first-trimester smoking and infants born to mothers with no
    reported first-trimester smoking, and how does this difference
    change from 2023 to 2025?

## Data Source and Study Population

We will use the 2023, 2024, and 2025 U.S. natality public-use files from
the Centers for Disease Control and Prevention / National Center for
Health Statistics (CDC/NCHS) Vital Statistics system. Each row
represents an individual registered live birth and contains information
on the infant, maternal characteristics, pregnancy-related factors, and
reported maternal health behaviors.

We have combined the 2023–2025 natality files into a preliminary dataset
of 10,528,168 singleton birth records and created indicators for
reported first-trimester smoking and low birth weight, defined as birth
weight below 2,500 grams.

Mothers reporting zero cigarettes during the first trimester will be
classified as having no reported first-trimester smoking, while mothers
reporting a positive number of cigarettes will be classified as having
reported first-trimester smoking. Records with unknown or not-stated
smoking information will not be classified as non-smokers.

The remaining coding challenge is to verify that unknown smoking and
birth-weight values were handled consistently across all three years.
For each year, we will report how many records have both a known smoking
status and a recorded birth weight and are therefore eligible for
comparison.

## Planned Analysis and Visualizations

We will calculate mean birth weight and the percentage of
low-birth-weight infants for the two smoking groups, both overall and
separately for 2023, 2024, and 2025.

For each year, a paired-dot plot will show the percentage of singleton
infants weighing less than 2,500 grams in each smoking group. We will
connect the two points and label the percentage-point difference,
calculated as the percentage among births with reported first-trimester
smoking minus the percentage among births with no reported
first-trimester smoking. This visualization will allow us to compare
both the size of the smoking-group difference within each year and
whether that difference changes across the three study years.

A companion table will report the number of eligible births and mean
birth weight in grams for each smoking group and year. Additional
visualizations may be used to describe the distribution of birth weight
if they help clarify the results.

We will interpret the observed group differences as descriptive
associations rather than causal effects. Reported cigarette use may be
misclassified, and the smoking groups may also differ in other maternal
characteristics, such as maternal age and education.

## Intended Final Products

The final project will include a reproducible written report, a project
website presenting the motivation, data, analysis, visualizations, and
main findings, and a short narrated screencast highlighting the most
important results. The project website will also provide access to the
complete report and GitHub repository.

## Planned Timeline

- **November 13:** Finalize the proposal, research questions, and
  preliminary dataset.
- **November 16–20:** Attend the project review meeting and revise the
  analysis plan based on feedback.
- **Late November:** Verify data cleaning across all three years and
  finalize the analytic dataset.
- **Early December:** Complete descriptive analyses, tables, and
  visualizations.
- **December 6–10:** Draft and revise the written report and project
  website.
- **December 10–12:** Finalize the screencast, reproducibility checks,
  and all project deliverables.
