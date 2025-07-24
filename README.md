# Well Played, Mauer: The Triple Threat

Welcome to the companion repo for my blog series on Joe Mauer’s 2009 MVP season, hosted on [Substack](https://reachedonerror.substack.com/). 
This project includes data analysis, visualizations, and code supporting the articles.

---

## About This Series

The purpose of my blog is education. I use it to teach my subscribers about baseball history and sabermetric analysis, blending historical context with advanced statistics to make the content accessible yet thorough.

This repository will evolve as I publish new parts of the series. Each part explores different aspects of Joe Mauer's offensive performance using advanced baseball metrics. The goal is to teach those who are less familiar with these sabermetric concepts in a way that's approachable but still in-depth.


### Part 1: The Triple Threat  

An in-depth look at Joe Mauer’s **Triple Slash Line** (**AVG**, **OBP**, **SLG**) compared to league averages, including batted ball tendencies and peripheral stats visualized in an interactive Tableau dashboard, and what it informs us about a player's production. The article explores the idea of **run values** using the **Run Expectancy Matrix**, revealing how much each offensive outcome is worth in terms of runs, on average. Along the way, I delve into whether a player should prioritize chasing a high **AVG** over **OBP** or **SLG**, unpacking the implications for offensive value.

Article link: Check back Friday 7/25!

---

## Repository Structure

- **`data/`** — Contains raw and processed CSV datasets used in analysis.  
- **`notebooks/`** — Jupyter notebooks with data cleaning, transformation, and analysis code.  
- **`tableau/`** — Tableau workbook files and dashboard exports supporting the visualization parts.  
- **`assets/`** — Images, charts, and other media assets used in blog posts or dashboards.  
- **`.gitignore`** — Specifies files and folders ignored by Git.  
- **`requirements.txt`** — Lists Python package dependencies for reproducing the analysis environment.

---

## How to Use

1. Clone this repository.  
2. Use the `requirements.txt` to set up a Python environment:  
   ```bash
   pip install -r requirements.txt

