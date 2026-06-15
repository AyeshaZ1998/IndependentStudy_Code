# Cross-Country Study on Culture and Economic Incentives

This repository contains the R analysis code from an independent research project examining how cultural factors relate to economic incentives and outcomes across countries. The study consolidates data from a range of published datasets into a single harmonized cross-country panel, then estimates relationships between cultural measures and economic outcomes using regression analysis.

## About this repository

**This is a coding sample, not a complete replication package.** It is intended to demonstrate my approach to data harmonization, cleaning, statistical analysis, and reproducible workflows in R. The underlying raw datasets are not distributed here, so the notebooks are provided as rendered HTML (`.nb.html`) that display the code alongside its output, tables, and figures rather than as a runnable end-to-end pipeline.

## Contents

Each file is an R Notebook showing code and results.

| File | Description |
|------|-------------|
| `1.Master_Data.nb.html` | Data consolidation and cleaning. Merges all source datasets into a single harmonized panel, reconciling country names and codes across sources, recoding variables, and handling and flagging missing values. |
| `2.Correlation_Graphs.nb.html` | Correlation analysis and visualizations exploring relationships between the key cultural and economic variables. |
| `3.Regression_Tables.nb.html` | The main statistical analysis, producing regression tables for the four outcomes studied: shirk intolerance and bonus culture prevalence (both derived from the World Management Survey), total factor productivity (TFP), and labour supply elasticity. |
| `4.Responsibilism_Graphs.nb.html` | Visualizations relating to the responsibilism (shirk intolerance) measures. |
| `4.WMS_Graphs.nb.html` | Visualizations based on the World Management Survey data. |
| `5.Bilingual_Study.nb.html` | A supplementary analysis examining bilingualism. |
| `6.Elasticity_Graphs.nb.html` | Visualizations relating to the labour supply elasticity measures. |
| `7.TFP_Graphs.nb.html` | Visualizations relating to total factor productivity (TFP). |

## Data sources

The analysis draws on data consolidated from the following published datasets and global data sources. Raw data files are not included in this repository; please refer to the original providers for access.

| Dataset | Source |
|---------|--------|
| Work hour / labour supply elasticity | Bick, Fuchs-Schündeln, and Lagakos (2017), "How Do Hours Worked Vary with Income? Cross-Country Evidence and Implications" |
| Cultural distance | Muthukrishna et al. (2020), "Beyond WEIRD Psychology: Measuring and Mapping Scales of Cultural and Psychological Distance" |
| Management practices | World Management Survey (WMS) |
| Cultural tightness (non-industrial societies) | Jackson, Gelfand, and Ember (2020), "A Global Analysis of Cultural Tightness in Non-Industrial Societies" |
| GDP per capita and income classifications | World Bank |
| Cultural tightness (industrial societies) | Gelfand et al. (2011), "Differences Between Tight and Loose Cultures: A 33-Nation Study" |
| Economic preferences | Falk et al. (2018), "Global Evidence on Economic Preferences" |
| Responsibilism scores | (source to be added) |

Country names across datasets were standardized using manually created translation tables to ensure consistent merging.

## Tools and methods

R · R Markdown · tidyverse · Panel data construction · Data harmonization and cleaning · Missing-data handling · Regression analysis with robust and clustered standard errors · Data visualization (ggplot2) · Reproducible workflows
