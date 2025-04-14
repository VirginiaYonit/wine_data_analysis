# Comparative Data Cleaning – Wine Quality Dataset

This two-part project explores data cleaning, outlier detection, and contextual validation across red and white wines from Portugal’s Vinho Verde region. It is designed as both a technical deep dive and a professional case study in data integrity, with workflows implemented in **R** and **Python**.

---

## Project Description

The dataset includes physicochemical and sensory data for **red and white wines**, allowing for comparisons, quality assessment, and data reliability checks. A key focus was on understanding variable distributions, identifying inconsistencies, and applying European and OIV standards for plausible ranges.

This project marks an important step in my transition into the data analytics field. It reflects both technical progress and a deeper understanding of **structured thinking in project design**.

---

## Project Structure

- `01_data_cleaning_wine_R.ipynb`:  
  A comprehensive and structured workflow in **R**, covering:
  - variable-by-variable review,
  - detection of outliers,
  - references to **EU regulatory limits** and **oenological practices**,
  - decisions based on domain logic and stylistic variation.

- `02_data_cleaning_wine_Python.ipynb`:  
  A follow-up analysis in **Python**, focused on:
  - visualization tools,
  - cross-validation of earlier insights,
  - detecting inconsistencies,
  - integration of automated downloading via the **Kaggle API**.

---

## Objectives

- Explore the distribution of key physicochemical variables  
- Identify and visualize potential outliers  
- Clean data based on **legal thresholds** and **scientific plausibility**  
- Preserve stylistic variation where justifiable  
- Build ready-to-use datasets for future **modeling** or **BI applications**

---

## Tools & Techniques

- **R**: `tidyverse`, `ggplot2`, `readr`, `dplyr`  
- **Python**: `pandas`, `matplotlib`, `seaborn`  
- Visual tools: boxplots, scatterplots, histograms  
- Validation tools: IQR, standard deviation, domain constraints  
- Environment cross-check: R vs Python consistency

---

## What I Learned

- How to detect non-obvious important problems using visual summaries  
- The importance of **locale-specific parsing** in European datasets  
- How to clearly document each cleaning step for reproducibility  
- The value of **separating dataset analysis** before merging insights  
- Most importantly:  
  > **Planning the structure of a project before writing any code is essential.**  
  I initially approached the Python notebook “by instinct”, which led to fragmented results and time-consuming fixes.  
  In contrast, the R notebook was designed methodically from the start, yielding a cleaner, faster, and more readable process.  
  This experience helped me internalize a key concept from my Google Data Analytics course — one I had heard before, but only truly understood by doing.

---

## Next Steps

- Begin exploratory modeling of wine quality ratings  
- Develop an interactive **dashboard** for stakeholders  
- Extend the study with **international wine datasets** for comparison

---

## Dataset Source

The original data was retrieved from the **[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)**.  
The repository includes clean CSV files for:
- `winequality-red.csv`  
- `winequality-white.csv`  

> _Note: This project resolves a known **decimal locale issue** affecting the `pH` variable. See notebook comments for full trace._

---

## About the Author

I’m a 53-year-old career-changer with 25 years of experience in **air transportation** — a sector that taught me precision, safety, and how to operate in highly regulated environments.  
Today, I work with **Python and R**, integrating data analysis with **domain awareness**, **legal context**, and **user-focused storytelling**.

I hold a diploma in Interior Design and bring with me a deep sense of structure, system logic, and clarity in presentation.  
I’m currently exploring **Business Intelligence** to better understand how data supports decision-making — but my mission remains the same:  
to deliver **meaningful insights** with **integrity**, **clarity**, and **impact**.

📧 virginiayonit@gmail.com

---

## References & Regulatory Sources

- VINHOS VERDES – Official Portal  
- OIV – International Code of Oenological Practices  
- EU Regulation 606/2009 on Oenological Practices  
- Definition of Sweet Wines – EU Regulation  
- NCBI – Wine Chemistry Reference  
- IVES – International Viticulture and Enology Society  
- Wine Acidification Methods – A Review  
- AEB – pH Determination in Wine  
- The World of Fine Wine – Vinho Verde  
- More Wine! – Must Testing  

---

## Project Status

- ✔ Completed: data cleaning, outlier detection, regulatory validation  
- In Progress: exploratory modeling & dashboard development

