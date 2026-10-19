# AI-Assisted-Data-Preprocessing-Integrity-Check
Project Overview:
Detection of Out of Specification (OOS) anomalies in laboratory and patient data, imputation of missing data using statistical methods, and structuring raw datasets for machine learning model pipelines.

Standard Operating Procedure (SOP):

Data Ingestion & Inspection: Importing raw data via the Pandas library to identify systemic anomalies and corrupted entries.

Handling Missing Values: Imputing missing data points (NaN) in critical columns (e.g., Age, Hemoglobin levels) utilizing the statistical median method.

Outlier Elimination: Ensuring data integrity by filtering out biologically impossible (OOS) limits (e.g., age values below 0 or above 100).

Noise Reduction: Dropping irrelevant features (e.g., Eye Color) to optimize the dataset for predictive modeling.

Methodology Note:
The data manipulation workflow in this project was architected leveraging a modern "AI-Assisted Programming" framework. Code generation was offloaded to LLM assistants via strictly constrained Prompt Engineering techniques, while the underlying system architecture, logical boundaries, and overall data quality were meticulously designed and validated by myself.
