# Textual Analysis of Monetary Policy Trends (2005–2024)

##  Repository structure

The project is modularized to ensure a reproducible and scalable workflow:

* **monetory master file.qmd**: The primary controller script that executes the full data pipeline.
* **monetory policy documents.qmd**: Handles data ingestion, text cleaning, and corpus preprocessing.
* **Topic_model.qmd**: Implements **Latent Dirichlet Allocation (LDA)** to discover hidden thematic structures across two decades of policy discourse.
* **co_occurrence_network.qmd**: Builds and visualizes semantic networks to analyze relationships between key terms like inflation, interest rates, and growth.
* **NLP monetory.qmd**: Performs advanced NLP tasks including N-gram extraction and sentiment scoring.

##  Technical capabilities

* **Unsupervised Learning**: Utilizes LDA modeling to identify structural breaks in policy focus without prior labeling.
* **Network Visualization**: Maps word co-occurrences to visualize the evolution of the central bank's linguistic priorities.
* **High-Dimensional Data**: Built to process and clean large-scale institutional text datasets with high precision.
* **Modern Stack**: Leverages **R**, **Quarto**, and professional-grade libraries for cutting-edge text mining and reporting.

##  Research impact

This framework provides a data-driven approach to understanding central bank communication. By quantifying the "tone" and "themes" of policy statements, researchers can better correlate qualitative shifts in communication with quantitative macroeconomic outcomes like inflation targets and exchange rate stability.

**Author:** Said Abbas  
**Specialization:** Econometrics & NLP Textual Data Analysis
