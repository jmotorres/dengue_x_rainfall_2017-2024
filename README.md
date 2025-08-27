# Dengue_x_Rainfall_2017-2024
This data analysis project explores the relationship between dengue incidence and rainfall intensity across different provinces in the Philippines throughout the years 2017 to 2024.

The project is divided into four sections or notebooks. In each section, I applied statistical concepts and data visualization techniques to uncover patterns which help us form insights into the dynamics of dengue occurrence in the country. By examining historical data on population, rainfall, and dengue cases, this project aims to provide an evidence-based view on one of the key factors that influence disease spread and outbreak. Ultimately, I hope this project can serve as a tool to support better public health intervention and response strategies.

---

## Project Structure

| Notebook | Purpose |
|----------|---------|
| `1-Dengue data.ipynb`       | Exploration of raw dengue case counts |
| `2-Population data.ipynb`   | Preparation, projection, and analysis of population statistics |
| `3-Rainfall data.ipynb`     | Examination of rainfall intensity and variability over time |
| `4-Complete analysis.ipynb` | Comprehensive analysis of rainfall vs dengue incidence + dengue forecasting model |

---

## Data sources

All data were obtained from publicly accessible online portals.
There were three main datasets that were gathered, with each given their own data preprocessing, visualization, and analysis workflow.
CSV files of the datasets can be found on the `raw_data/` folder of this repository.

### Dengue data sources:
- https://data.humdata.org/dataset/philippine-dengue-cases-and-deaths
- https://www.foi.gov.ph/agencies/doh/monthly-number-of-dengue-cases-per-province-and-ncr-cities-in-the-philippines-from-years-2017-2024/

### Population data source:
- https://openstat.psa.gov.ph/PXWeb/pxweb/en/DB/DB__1A__PO/1001A6DTPG0.px/?rxid=92057030-cd50-40bd-954e-97a3c1cb2b65

### Rainfall data source:
- https://data.humdata.org/dataset/phl-rainfall-subnational

---

## How to Run the Project (Recommended: Google Colab)

Majority of the project can be simply viewed directly via the `.ipynb` files in the repository.
However, some parts include interactive plots, which cannot be rendered on GitHub.
To experience the full functionality, I recommend running and viewing the notebooks in Google Colab.
Just go to https://colab.research.google.com and load the notebooks.

### IMPORTANT NOTE!

In every notebook, local file paths were used to load data. This makes them impossible to run in any external environment.
As a workaround, you'll have to replace the read.csv URL with the raw GitHub URL of the corresponding dataset (found in the `raw_data` folder).

In addition, I highly recommend to run and view the project in order, as indicated by the notebook number.
The first three notebooks each generate a processed dataset (CSV) that is loaded in `4-Complete analysis.ipynb`.
Therefore, you cannot run the Complete analysis notebook without executing the first three.

---

## Contact

This work is a personal hobby project and is maintained by a single person.
If you have questions, suggestions, would like to collaborate, or just geek out over data, reach me at:

- Email: jeremymartintorres@gmail.com
- GitHub: github.com/jmotorres
- LinkedIn: linkedin.com/in/jeremymartintorres/
