# Global Olympic Sports Performance Analysis (1992–2026)

Skill Wallet Virtual Internship Portfolio Project — Data Analytics with Tableau.

## Project Overview
This project presents a data-driven analysis of historical Olympic performance from 1992 to 2026 across medal counts, regional efficiency, and national sports investments.

## Repository Structure
- `data/`: Cleaned CSV dataset files (`athletes.csv`, `medal_results.csv`, `sports_investment.csv`).
- `tableau/`: Tableau workbook configurations (`Olympic_Performance_Analysis.twb`).
- `index.html`: Interactive web dashboard application for live GitHub Pages deployment.

## Key Calculated Fields
- **Average Medals per Athlete**: `SUM([Total Medals]) / COUNTD([Athlete ID])`
- **Medal Efficiency Percentage**: `(SUM([Total Medals]) / SUM([Sports Investment M USD])) * 100`

## GitHub Pages Deployment
1. Initialize local Git repository: `git init`
2. Add and commit all files: `git add . && git commit -m "Initial commit"`
3. Push to main branch: `git push -u origin main`
4. Enable Pages in **Repository Settings -> Pages** (Source: `main` branch, `/` root directory).
