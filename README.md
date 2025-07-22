# freshness-analysis-ETL
Developed a modular, Python-powered ETL pipeline in a Jupyter Notebook to analyze ingredient shelf-life for two pizzeria locations. The workflow programmatically:

Generates synthetic storage-time datasets with NumPy (configurable means and variances per ingredient and site).

Transforms and aggregates the data using pandas to produce clean, analysis-ready tables.

Computes distributional statistics (mean, median, variance, IQR, percentiles) via SciPy and native pandas methods.

Visualizes comparative boxplots with Matplotlib/Seaborn—annotated with best-performing site indicators.

Outputs data-driven QC directives, automatically calculating optimal reorder points and maximum safe storage windows.

Every step is parameterized for full reproducibility, version-controlled, and easily extensible for additional ingredient categories or pizzeria sites.
