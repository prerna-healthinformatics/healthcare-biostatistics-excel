# 📐 Biostatistics for Healthcare Data (Excel)

Applied biostatistics on hospital datasets, including patient age, length of stay (LOS), DRG, charges, and Medicare payments. The project runs from data cleaning through descriptive statistics, hypothesis testing, ANOVA, and regression, with **every calculation built in Excel** using formulas, PivotTables, and charts.

*Coursework, MS in Health Care Informatics, University of San Diego*

---

## 🔎 Highlights

| Analysis | Question | Result |
|---|---|---|
| **One-way ANOVA** | Do average patient costs differ across four hospitals? | **Yes.** F = 3.73, p = 0.013. Mean cost ranged from **$5,716** (Dare) to **$9,381** (Catawba) |
| **Regression with a dummy variable** | Do costs differ for women vs. men? | **No.** Women averaged $229 more, but p = 0.89 (R² ≈ 0.0003) |
| **Correlation** | Which variables have a linear relationship? | Charges vs. Medicare payment had the strongest relationship (**r ≈ 0.66**), while Age vs. Charges had almost none (r ≈ 0.11) |
| **Descriptive statistics** | What do the patient data look like? | Mean age 77.7; LOS mean 5.1 vs. median 4 days and charges mean $5,798 vs. median $4,940, both **right-skewed** |
| **Distribution of LOS** | How is length of stay spread around the mean? | **74%** of patients fell within ±1 standard deviation (SD = 3.35 days) |

---

## 📁 Workbooks

| # | Workbook | What it shows |
|---|---|---|
| 01 | [`data_import_and_cleaning`](workbooks/01_data_import_and_cleaning.xlsx) | Imported a text file of 100 patient records; fixed two-digit birth years; calculated age and LOS; recoded sex for analysis |
| 02 | [`frequency_distributions_and_pivot_tables`](workbooks/02_frequency_distributions_and_pivot_tables.xlsx) | Age frequency distribution using `FREQUENCY()`; histogram, frequency polygon, bar, pie, and scatter charts; PivotTables by sex and LOS category |
| 03 | [`descriptive_statistics`](workbooks/03_descriptive_statistics.xlsx) | Mean, median, skew, variance, and standard deviation, calculated by hand formula and checked against Excel functions |
| 04 | [`los_standard_deviation_distribution`](workbooks/04_los_standard_deviation_distribution.xlsx) | LOS grouped into standard-deviation intervals around the mean, with a chart |
| 05 | [`confidence_intervals`](workbooks/05_confidence_intervals.xlsx) | Exact 95% confidence intervals using the t-distribution, showing how sample size and standard error change the interval width |
| 06 | [`hypothesis_testing_t_tests`](workbooks/06_hypothesis_testing_t_tests.xlsx) | One-sample t-tests (1- and 2-tailed): t-values, p-values, and reject / fail-to-reject decisions |
| 07 | [`one_way_anova`](workbooks/07_one_way_anova.xlsx) | Cost comparison across four hospitals: between- and within-group sums of squares, F-statistic, and p-value, all calculated step by step |
| 08 | [`correlation_scatter_charts`](workbooks/08_correlation_scatter_charts.xlsx) | Scatter charts with trendlines; correlation, R², slope, and intercept; interpretation of best and worst linear fit |
| 09 | [`regression_dummy_variable`](workbooks/09_regression_dummy_variable.xlsx) | Linear regression with `LINEST`, using a 0/1 dummy variable to test cost differences by sex |

---

## 🧪 Statistical Methods
- **Data preparation:** text import, date correction, calculated fields, variable recoding
- **Descriptive statistics:** central tendency, dispersion, skewness, frequency distributions
- **Inferential statistics:** confidence intervals, one-sample t-tests (1- and 2-tailed)
- **Group comparison:** one-way analysis of variance (ANOVA)
- **Relationships:** correlation, simple linear regression, dummy-variable regression

## 🛠️ Excel Skills
`AVERAGE` · `MEDIAN` · `VAR` · `STDEV` · `FREQUENCY` · `CORREL` · `SLOPE` · `INTERCEPT` · `LINEST` · `TINV` · `TDIST` · `FDIST` · `DEVSQ` · PivotTables · Histograms · Scatter charts with trendlines

---

## 💡 Why It Matters in Healthcare
- **ANOVA** is how analysts test whether cost or quality differences between hospitals are real or just random variation.
- **Regression** helps separate actual cost drivers from noise, for example showing that sex was *not* a cost driver here.
- **Skewed LOS and charge data** explain why healthcare analysts often report the median instead of the mean.

---

👩‍💻 **Prerna Sinha** · [LinkedIn](https://www.linkedin.com/in/prerna-sinha-health-informatics/) · [ePortfolio](https://sites.google.com/view/prernasinha/home)
