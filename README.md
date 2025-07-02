# 📊 Facebook Ad Click Analysis using Randomized Block Design (RBD)

This project analyzes how the **type of advertisement** and **user gender** influence the **number of ad clicks** on Facebook. The analysis uses a **Randomized Block Design (RBD)** to control for gender-based variability and assess the effect of ad interest categories on user engagement.

## 📁 Dataset

- **Source**: Kaggle
- **File**: `facebook_ads.csv`
- **Variables**:
  - `interest`: Ad category (Treatment)
  - `gender`: User gender (Block)
  - `Clicks`: Number of ad clicks (Response)

## 📊 Statistical Method

- **Design**: Randomized Block Design
- **Software**: R
- **Analysis**: ANOVA using `aov()` function

## 📈 Results Summary

- Both ad type and gender showed statistically significant effects on click counts (`p < 0.05`)
- Box plots were used to visualize differences across groups

## 🖼️ Visualization

![Box Plot](boxplot.png)

## 📂 Included Files

| File | Description |
|------|-------------|
| `report.docx` | Written report |
| `facebook_ads.csv` | Dataset |
| `analysis_code.R` | R script |
| `boxplot.png` | Graphical summary |

## 👨‍🎓 Author

Rami Mohammad
Yarmouk University – Department of Statistics  
📅 July 2025
