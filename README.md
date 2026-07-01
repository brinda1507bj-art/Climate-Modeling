# Climate-Modeling
This repository contains scipts and data models designed to simulate atmospheric changes and analyze historical climate patterns.
# Markdown
# 🌊 Station D5GN6 Marine Climate Analytics & Forecasting Terminal

An end-to-end data science pipeline and interactive web terminal engineered to ingest granular NOAA National Centers for Environmental Information (NCEI) Common Marine Format data, perform rigorous Exploratory Data Analysis (EDA), and project long-term marine Dry Bulb Temperature (`DB`) trends 30 years into the future.

# 🚀 Core Features

*   **Granular CMF Parser:** Custom temporal ingestion mapping directly onto the NOAA Common Marine Format schemas.
*   **Comprehensive EDA Framework:** Multi-variable statistical distribution graphics built on `Seaborn` exploring relations across Sea Level Pressure (`SLP`), Wind Speed (`SPD`), and Temperature (`DB`).
*   **30-Year Structural Forecasting Engine:** Combines Ordinary Least Squares (OLS) linear drift tracking with deterministic macro-sinusoidal seasonal wave simulation to create highly stable multi-decade projections.
*   **Decoupled Architecture:** Fully operational inline within a Jupyter Notebook environment OR run as a standalone, multi-threaded production browser web server.

# Core Pipeline Architecture

├── 1. Data Cleaning & Parsing ──> 2. Statistical Exploratory Analysis (EDA)
                                                    │
                                                    ▼
├── 4. Production Gradio UI UI <── 3. Hybrid Linear Trend & Seasonality Model

# Libraries Used

python (v3.8+), pandas, numpy, scikit-learn, seaborn, matplotlib, gradio (v6.19)
