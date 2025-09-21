# Well-being-of-Vulnerable-Female-Migrant-Head-Porters-Kayaye-in-Urban-Ghana-Evidence-from-Kumasi

📄 Full Report: [View Analysis](Well-being of Vulnerable Female Migrant Head-Porters (Kayaye) in Urban Ghana_ Evidence from Kumasi.pdf)

## Overview
This mixed-methods study investigates the well-being of 237 vulnerable female migrant head-porters (Kayaye) in Kumasi, Ghana, focusing on vulnerability levels, life satisfaction, contributing factors, and social capital's role. Findings reveal moderate vulnerability (VI mean=4.46/10), driven by health issues (mean=0.618) and housing insecurity (mean=0.598), with 49.4% in upper-mid to high categories. Life satisfaction is moderate (mean=5.98/10), negatively correlated with health expenditure (r=-0.228) and children (r=-0.288), but positively influenced by sense of belonging (β=0.544). Social capital is low (SCI mean=3.90/10), with weak direct correlation to satisfaction (r=0.002), but significant in controls (β=0.406). fsQCA identifies pathways like high social support and low vulnerability for better outcomes. Policy recommendations include NHIS drives, vocational training, and safe housing to mitigate risks and enhance resilience.

## Objectives
- Assess the current level of vulnerability among Kayaye (RQ1).
- Determine the level of life satisfaction among Kayaye (RQ2).
- Identify factors contributing to life satisfaction (RQ3).
- Examine how social capital influences well-being (RQ4).

## Dataset Summary
- **Source**: Primary survey data from Kayaye in Kumasi, Ghana (2024).
- **Sample Size**: 237 respondents.
- **Key Variables**: Demographics (age, marital status, education, children); economic (income, savings, hours); health (issues, expenditure, access); housing (safety, satisfaction); social (support, belonging); vulnerability index (VI); social capital index (SCI); life satisfaction (0–10).

## Methods
- Descriptive statistics (means, frequencies, percentages) and visualizations (histograms, box plots) for profiling demographics and distributions.
- Correlation analysis (Pearson's r) for relationships (e.g., health expenditure vs. satisfaction, r=-0.228).
- Factor analysis (Varimax, 4 factors explaining 51.3% variance) for well-being dimensions.
- Multiple regression for predictors (best R²=0.723, e.g., belonging β=0.544, p=0.001).
- Fuzzy-set Qualitative Comparative Analysis (fsQCA) for causal configurations (e.g., high support + low vulnerability → well-being).

## Key Findings
- Demographics: Young (mean age=24.9, 49.4% single), low education (36.3% none), married (48.1%), mean 2.4 children.
- Vulnerability (RQ1): Mean VI=4.46/10 (moderate); health (0.618), housing safety (0.598) dominant; 49.4% upper-mid/high; widowed highest (7.08).
- Life Satisfaction (RQ2): Mean=5.98/10 (moderate); 40.1% low; younger/single higher (6.16/6.17).
- Factors (RQ3): Belonging (β=0.544, p=0.001), savings (β=0.362, p=0.004) positive; health expenditure (β=-0.578, p<0.001), children (β=-0.557, p=0.007) negative; R²=0.723.
- Social Capital (RQ4): SCI mean=3.90/10 (low-moderate); weak direct r=0.002, but β=0.406 (p=0.039) in controls; relational support strongest.
- fsQCA: High support + low vulnerability → better well-being.



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, psych (factor analysis), QCA (fsQCA)

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "psych", "QCA"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). Well-being of Vulnerable Female Migrant Head-Porters (Kayaye) in Urban Ghana: Evidence from Kumasi.
