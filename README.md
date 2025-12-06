# Impact of Digital Learning on Mathematics Achievement 📊

A statistical analysis project investigating the effectiveness of digital learning platforms on Grade 9 mathematics achievement using hypothesis testing.

## 📋 Table of Contents
- [Overview](#overview)
- [Research Question](#research-question)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Contributors](#contributors)

## 🎯 Overview

This project examines whether digital learning tools significantly improve mathematics test scores compared to traditional classroom instruction. The analysis employs independent samples t-test to compare achievement between two groups of Grade 9 students.

**Key Findings:** Digital learning students scored **6.80 points higher** on average (p < 0.0001, Cohen's d = 1.15), representing a large and statistically significant effect.

## ❓ Research Question

**Does digital learning result in significantly higher mathematics scores compared to traditional classroom methods for Grade 9 students?**

## 📊 Dataset

- **Total Students:** 60
- **Digital Learning Group:** 30 students
- **Conventional Learning Group:** 30 students
- **Variables:** Student ID, Group, Math Score, Gender, Attendance (%)
- **File:** `Marks.csv`

## 🔬 Methodology

### Statistical Test
**Independent Samples t-Test** (One-tailed)

### Hypotheses
- **H₀:** μ_digital = μ_conventional (no difference)
- **H₁:** μ_digital > μ_conventional (digital is better)
- **Significance Level:** α = 0.05

### Assumptions Checked
1. ✅ Independence of observations
2. ✅ Normality (Shapiro-Wilk test)
3. ✅ Homogeneity of variance (Levene's test)

## 📈 Results

| Metric | Digital Group | Conventional Group |
|--------|---------------|-------------------|
| **Mean** | 80.90 | 74.10 |
| **SD** | 5.32 | 6.47 |
| **Range** | [71, 91] | [61, 88] |

**Test Statistics:**
- t-statistic: 4.4479
- p-value: < 0.0001 ⭐
- Cohen's d: 1.1484 (Large effect)
- 95% CI: [3.80, 9.80]

**Conclusion:** ✅ Reject H₀ - Digital learning significantly improves math scores


## 📁 Project Structure

```
digital-learning-analysis/
│
├── data/
│   └── Marks.csv                  # Dataset
│
├── code/
│   ├── Hypothesis Testing.ipynb     
│
├── output/
│   ├── analysis_v1.png
│   ├── analysis_v2.png
│   └── analysis_v3.png
│
├── docs/
│   ├── Technical_Report.pdf
│   ├── Presentation.pdf
│
├── README.md
└── LICENSE
```

## 📦 Dependencies

```
pandas >= 1.3.0
numpy >= 1.21.0
scipy >= 1.7.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
```

## 👥 Contributors

- **Usama Umer** - MSDS25044
- **Muhammad Ahmed** - MSDS25048
- **Saad Ali** - MSDS25066

**Course:** Statistical and Mathematical Methods for Data Analysis  
**Institution:** Information Technology University (ITU)  
**Instructor:** Muhammad Ali Murtaza


## 🙏 Acknowledgments

- ITU Faculty for guidance and support
- Course instructor for valuable feedback
- Open-source community for excellent libraries

## 📧 Contact

For questions or feedback, please open an issue or contact:
- Email: msds25044@itu.edu.pk
-Email: msds25048@itu.edu.pk
-Email: msds25066@itu.edu.pk
---


