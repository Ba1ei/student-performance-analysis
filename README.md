# 📊 Student Performance Analysis

## 📖 Overview

The main goal of this project is to analyze how different factors influence students' final grade (G3).

---

## 🎯 Objectives

* Analyze the relationship between all variables and the final grade (G3)

---

## 📊 Correlation Heatmap

![Correlation](images/corrplot_full.png)

---

## 🔍 Key Insights

### 1. Previous Failures Have the Strongest Impact on G3
Failures show the strongest negative relationship with the final grade (G3). Students with a higher number of past failures tend to achieve significantly lower final grades.

---

### 2. Parental Education Has a Positive Influence
Both mother's (Medu) and father's (Fedu) education levels show a slight positive relationship with G3, suggesting a supportive home environment may contribute to better performance.

---

### 3. Study Time Has a Weak Relationship with G3
Study time shows only a weak positive correlation with G3, indicating that increased study time alone does not strongly guarantee higher performance.

---

### 4. Age Has an Indirect Negative Effect
Age appears to have a negative relationship with G3. However, further analysis suggests this is an indirect effect, as older students tend to have more previous failures, which impacts performance.

---

### 5. Absences and Social Life Show Minimal Impact
Variables such as absences and going out (goout) show very weak relationships with G3, indicating limited direct influence on final grades.

---

### 6. Removing Prior Grades Reveals True Influencing Factors
Including G1 and G2 creates misleadingly strong correlations with G3. After removing them, the analysis provides a clearer understanding of the actual factors affecting student performance.

---

## 🛠️ Tools Used

* R
* dplyr
* corrplot

---

## 👩‍💻 Author
(Bayan Almalawi)
