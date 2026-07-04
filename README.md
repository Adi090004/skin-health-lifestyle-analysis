# skin-health-lifestyle-analysis
Statistical analysis of how diet, lifestyle, water intake, and seasonal factors affect skin health — using ANOVA, regression, and correlation in R.
# Habits and Lifestyle Affecting Skin Health

A statistical study examining how diet, lifestyle habits, water intake, skincare 
routines, and seasonal variation impact skin health, based on survey data from 
98 respondents.

## 📊 Overview
Skin health is increasingly affected by lifestyle habits and environmental factors. 
This project analyzes survey data to identify which behavioral and environmental 
factors are statistically linked to skin health outcomes.

## 🎯 Objectives
1. Skincare routine distribution by gender
2. Impact of diet habits on skin health
3. Effect of lifestyle factors (exercise, sleep, stress, skincare) on skin health
4. Relationship between skin product usage and skin health
5. Effect of water intake on skin health
6. Impact of seasonal variation on skin condition
7. Influence of lifestyle factors on skin satisfaction

## 🔬 Methods & Tools
- **Language:** R
- **Statistical tests used:**
  - Two-way ANOVA (diet habits, lifestyle factors)
  - Spearman's Rank Correlation (product usage, water intake)
  - Linear Regression (water intake → skin health)
  - Pearson's Chi-square Test of Independence (season → skin condition)

## 📈 Key Findings
| Factor | Test | Result |
|---|---|---|
| Diet habits (junk food, drinks) | Two-way ANOVA | Significant effect (p < 0.001) |
| Lifestyle (exercise, sleep, stress, skincare) | Two-way ANOVA | All significant; exercise had the strongest effect |
| Skin product usage | Spearman correlation | No significant correlation (p = 0.19) |
| Water intake | Linear regression / Spearman | Significant positive effect (p < 0.001) |
| Season | Chi-square test | Significant association (p = 0.021) |

**Conclusion:** A healthy lifestyle — regular exercise, good diet, adequate water 
intake, and sufficient sleep — is strongly linked to better skin health and 
satisfaction.

## 📁 Files
- `skin_health_analysis.R` — full R script with all statistical tests
- `Habits_and_Lifestyle_Affecting_Skin_Health.pdf` — presentation summary of findings
- `data/` — survey dataset (if shareable)

## 🚀 How to Run
```r
# Clone repo, open in RStudio
data <- read.csv("skin_health_data.csv")
source("skin_health_analysis.R")
