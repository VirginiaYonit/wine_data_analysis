# Comparative Data Cleaning – Wine Quality Dataset

This repository showcases a two-part project focused on data cleaning and outlier analysis using both **R** and **Python**.  
The dataset contains physicochemical and sensory data for red and white wines from Portugal’s **Vinho Verde** region.
- [R notebook – Red wine data cleaning](01_data_cleaning_wine_R.ipynb)
- [Python notebook – Red wine data cleaning](02_data_cleaning_wine_Python.ipynb)

Data source:  
Originally published by the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)

---

## How to Use This Dataset

Download the dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)
and place the two `.csv` files in your project directory (`winequality-red.csv` and `winequality-white.csv`).

Alternatively, you can use the **Kaggle API** for automated downloading, as shown in the Python notebook.

---

## Project Structure

- `01_data_cleaning_wine_R.ipynb`  
  Comprehensive data cleaning workflow in **R**, integrating references to EU regulatory limits, winemaking styles, and a detailed variable-by-variable review.

- `02_data_cleaning_wine_Python.ipynb`  
  Follow-up analysis in **Python**, focusing on cross-validation, visualization, and enforcing legal/chemical constraints across both datasets.

---

## Objectives

- Explore the distribution of physicochemical variables  
- Identify and visualize potential outliers  
- Clean data based on legal thresholds and scientific plausibility  
- Preserve stylistic variation when justified  
- Build ready-to-use datasets for future modeling or BI use

---

## Topics Covered

- Outlier detection: IQR, standard deviation  
- Validation against EU & OIV standards  
- Contextual variable analysis (e.g., density, alcohol, SO₂)  
- Visual tools: boxplots, scatterplots, histograms  
- Environment cross-check: R vs Python  

---

## About the Author

I’m a 53-year-old career-changer with 25 years of experience in air transportation — a field that taught me precision, responsibility, and how to operate in complex, regulated environments.  

Today I work with Python and R, combining data analysis with domain awareness and legal context.  
I hold a diploma in Interior Design and bring with me a strong sense of structure, systems, and clarity.

I’m currently exploring business intelligence to better understand how data supports decision-making, but my goal remains the same: to deliver meaningful results with insight, clarity, and integrity.

📧 [virginiayonit@gmail.com](mailto:virginiayonit@gmail.com)

---

## Project Status

✔**Completed**: data cleaning, outlier handling, and documentation in R and Python  
**Coming soon**: exploratory modeling & dashboard integration

---

## References

 References and Regulatory Sources

- [VINHOS VERDES – Official Portal](https://portal.vinhoverde.pt/pt/produtos-regras-de-conformidade/GVVT)
- [OIV – International Code of Oenological Practices](https://www.oiv.int/en/technical-standards-and-documents)
- [EU Regulation 606/2009 on Oenological Practices](https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX:32009R0606)
- [Definition of Sweet Wines – EU Regulation](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019R0033)
- [NCBI – Wine Chemistry Reference](https://pmc.ncbi.nlm.nih.gov/articles/PMC10489813/#:~:text=According%20to%20Michlovsk%C3%BD%20%5B2%5D%2C,to%201.0138%20g/cm3.)
- [More Wine! – Must Testing](https://morewinemaking.com/articles/testing_wine_must#:~:text=The%20typical%20pH%20range%20for%20red%20wines%20is%20between%203.5%20and%203.8.)
- [IVES – International Viticulture and Enology Society](https://ives-openscience.eu/14307/)
- [The World of Fine Wine – Vinho Verde](https://worldoffinewine.com/news-features/vinho-verde-new-wave)
- [AEB – pH Determination in Wine](https://www.aeb-group.com/it/determinazione-del-ph-del-vino)
- [Wine acidification methods: a review](https://oeno-one.eu/article/view/7476)


---

## Data Consistency Note

The original datasets used in this project were sourced directly from the  
[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality),  
which provides clean, complete data with no missing values.

Note: This project resolves a known decimal locale issue affecting the `pH` variable. See notebook comments for full trace.
