# Descriptive Statistical Analysis of IMDb Audience Reviews: A Case Study of 3 Idiots

This project applies **descriptive statistical analysis** to IMDb audience reviews of *3 Idiots* to quantitatively evaluate audience reception.

Using descriptive statistical measures such as central tendency, dispersion, skewness, frequency distributions, and review-length analysis, the study explores how audience ratings reflect viewer perception, consensus, and engagement.

---

## 🔎 Research Questions

* Is *3 Idiots* generally liked by audiences?
* Are audience opinions consistent or divided?
* Which rating values dominate audience opinion?
* What does the rating distribution reveal about viewer behavior?
* Do review-writing patterns support the statistical findings?

---

## 📂 Dataset

* **Source:** IMDb Audience Reviews
* **Original Dataset Size:** 1,086 Reviews
* **Clean Dataset Size:** 1,042 Reviews
* **Retention Rate:** 96%
* **Rating Scale:** 1-10

### Feature Schema

| Feature      | Description                              |
| ------------ | ---------------------------------------- |
| Username     | Reviewer identifier                      |
| Rating       | Numerical score assigned by the reviewer |
| Review Title | Short summary of audience sentiment      |
| Review Text  | Full textual review                      |

---

## 🚀 Analysis Pipeline

1. Data Collection through automated review scraping.
2. Data Cleaning and preprocessing.
3. Rating distribution analysis.
4. Central tendency analysis (Mean, Median, Mode).
5. Dispersion analysis (Range, Variance, Standard Deviation).
6. Distribution shape analysis using Skewness.
7. Frequency and interval analysis.
8. Review-length analysis across rating groups.
9. Statistical visualization and interpretation.

---

## 📊 Statistical Dashboard

| Metric                | Value  |
| --------------------- | ------ |
| Mean Rating           | 8.67   |
| Median Rating         | 9      |
| Mode Rating           | 10     |
| Range                 | 9      |
| Variance              | 4.287  |
| Standard Deviation    | 2.07   |
| Skewness              | -2.199 |
| Ratings Between 7-10  | 88.6%  |
| Perfect 10/10 Ratings | 49.3%  |

---

## 📌 Key Insights

### 1. Strong Audience Approval

The mean (8.67), median (9), and mode (10) are all concentrated near the upper end of the rating scale, indicating widespread positive reception.

### 2. Ratings Are Highly Concentrated

Nearly 89% of all ratings fall between 7 and 10, showing strong audience approval and relatively limited disagreement.

### 3. Perfect Scores Are Common

Almost half of all reviewers awarded the film a perfect 10/10 rating, highlighting exceptionally strong audience satisfaction.

### 4. Negative Skewness

The skewness value of -2.199 indicates that ratings are heavily concentrated near the maximum rating, with a smaller number of low-rating reviews forming the left tail of the distribution.

### 5. Review Length Reflects Opinion Complexity

Moderately rated reviews tend to be longer and more detailed, suggesting that mixed opinions require greater explanation. In contrast, extremely positive or negative reviews are generally shorter and more direct.

---

## 📌 Conclusion

The statistical analysis indicates that *3 Idiots* received overwhelmingly positive audience reception. High central tendency values, strong concentration of ratings in the 7-10 range, and a large proportion of perfect scores collectively demonstrate broad audience approval and long-term popularity.

---

## 🛠 Tech Stack

* **Data Wrangling & Core Operations:** `Python`, `Pandas`, `NumPy`
* **Statistical Inference Engine:** `SciPy` (`scipy.stats` for Skewness and Gaussian Kernel Density Estimation)
* **Visualization Matrix:** `Matplotlib` (Custom styled sheets configured for professional reporting layouts)
* **Pipeline Automation:** `Playwright` (Async dynamic page-scrolling) & `BeautifulSoup` (DOM structure extraction)

---

## 📁 Repository Structure

```text
.
├── 3_Idiots_Statistical_Analysis.ipynb
├── parsing.py
├── 3_idiots_review.csv
├── Kingshuk_Movie_Review_Analysis_PPT.pdf
└── README.md
```

---

## 📈 Key Findings at a Glance

* ⭐ Average Rating: **8.67 / 10**
* 🎯 Median Rating: **9 / 10**
* 🏆 Most Common Rating: **10 / 10**
* 📊 Positive Ratings (7-10): **88.6%**
* 💯 Perfect Scores: **49.3%**
* 📉 Skewness: **-2.199**

These findings collectively indicate a highly favorable audience response toward *3 Idiots*, with ratings strongly concentrated at the upper end of the scale.
