# Olympic Performance Analysis

**Portfolio website for Mayank Lavvanshi**  
Medi-Caps University · SmartBridge Skill Wallet — Data Analytics with Tableau

This Flask website brings three interactive Tableau Public views into one responsive page. It is a custom website presentation; the visualizations and their analysis remain in the published Tableau workbooks.

## Tableau views

- [Global Olympic Performance dashboard](https://public.tableau.com/app/profile/mayank.lavvanshi/viz/Olympic_Performance_AnalysisDashBoard1/01GlobalOlympicPerformance?publish=yes)
- [Efficiency & Performance dashboard](https://public.tableau.com/app/profile/mayank.lavvanshi/viz/Olympic_Performance_AnalysisDashBoard2/02EfficiencyPerformance?publish=yes)
- [The Olympic Story](https://public.tableau.com/app/profile/mayank.lavvanshi/viz/Olympic_Performance_AnalysisStory/TheOlympicStory?publish=yes)

The site embeds the published views directly from Tableau Public. An internet connection is needed to load the dashboards and story.

## Project report

[Olympic Performance Analysis report](output/pdf/olympic_performance_analysis_report_FINAL_Mayank_Lavvanshi.pdf)

## Run locally

```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
py -m pip install -r requirements.txt
py app.py
```

Open `http://127.0.0.1:5000` in a browser.

## Deployment

The `Procfile` is configured for a Flask-compatible host such as Render.  
Live website: **to be added after deployment**.  
Demo video: **placeholder — to be added**.

## Source note

The underlying Olympic CSV datasets and packaged Tableau workbook are available in the [source repository by Mayank Tanwani](https://github.com/mtanwani353-blip/olympic-performance-analysis/). They are not bundled in this website repository; the page loads the three views published under Mayank Lavvanshi's Tableau Public profile.
