## Project Overview

This project provides the full research workflow and computational implementation for the study **“Optimalisasi Jumlah Saham untuk Diversifikasi Portofolio pada Indeks IDX80 Berdasarkan Single Index Model”**
The repository contains Python-based codes and analytical outputs used to evaluate how portfolio size affects risk, return, and performance when investing in Indonesian stocks listed in the IDX80 index during the January 2023– December 2024 period. The project emphasizes large-scale portfolio combination analysis to empirically determine the optimal number of stocks required for effective diversification.

## Research Objective
The main objective of this research is to determine the **optimal number of stocks** needed to achieve effective portfolio diversification in the Indonesian stock market. Specifically, the study aims to:
* Analyze how portfolio risk, expected return, and Sharpe Ratio change as the number of stocks increases.
* Identify the portfolio size that minimizes risk while maintaining competitive returns.
* Provide empirical evidence for practical diversification strategies within the IDX80 index using a technical (market-based) approach.

## Methodology

The study applies the **Single Index Model (SIM)** to construct and evaluate stock portfolios. Key methodological steps include:
* Collecting daily closing prices of IDX80 constituent stocks and the JKSE market index.
* Estimating return, risk, beta, alpha, and residual variance for each stock.
* Selecting candidate stocks using the **Excess Return to Beta (ERB)** and cut-off point criteria.
* Generating **all possible portfolio combinations** (524,487 combinations) from 1 to 19 stocks.
* Computing portfolio weights, expected return, risk, and Sharpe Ratio for each combination.
* Comparing average, minimum-risk, and maximum-performance portfolios across different portfolio sizes.
All computations are implemented using **Python**, ensuring scalability and computational transparency.

## Key Contributions
This project offers several important contributions:
* Provides one of the most exhaustive portfolio combination analyses for the IDX80 index.
* Demonstrates that **eight stocks** are sufficient to achieve optimal diversification based on Sharpe Ratio performance.
* Shows diminishing marginal risk reduction beyond a certain portfolio size, supporting efficient investment decision-making.
* Bridges academic portfolio theory with practical insights relevant to Indonesian investors and market practitioners.
* Supplies reproducible, code-based evidence rather than simulation-limited or sample-restricted approaches.

## Reproducibility
Reproducibility is a core principle of this repository:
* All data collection, preprocessing, portfolio construction, and evaluation steps are implemented in Python.
* The scripts are structured to allow users to rerun the analysis, adjust time periods, or apply the methodology to other stock indices.
* Data sources, assumptions, and calculation procedures are clearly documented to support transparency and verification.
* The repository is suitable for academic replication, methodological extension, and educational purposes.
