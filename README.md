# DataStory_KEYWORD: Where do international students study in Germany?

Data story for *Visual Communication and Data Storytelling*.

**Team: Christina Tannous, Judith Rotich** 
**Keyword:#StudentGeography** 

## Question
How unevenly are students with foreign nationality distributed across Germany's higher education institutions and federal states?

## Data
Destatis (Federal Statistical Office), GENESIS table 21311-0002, students by institution and nationality, winter semester 2025/26. Cleaned version in `data/destatis_21311-0002_clean.xlsx` (state, institution type, private and distance-learning flags added by us; see the Notes sheet). Planned: table 21311-0005 for the time trend and a check of the state assignment.

## Target audience
University decision-makers and student support staff in Germany, prospective international students, and curious general readers.

## Main insights
1. The foreign-national share ranges from 10.8% (Schleswig-Holstein) to 27.8% (Brandenburg); Germany overall: 18.0%.
2. Share and absolute numbers differ: NRW has the most (113,075) but a below-average share (15.9%).
3. Institutions vary far more than states: from 0% to 99%.

## Contents
- `index.qmd`: report with the visuals (map, state bars, institution scatter, rankings)
- `presentation.qmd`: slide deck (in progress)
- `data/`: cleaned data

## Reproduce
Open the project in Positron or RStudio and run `quarto render`.
