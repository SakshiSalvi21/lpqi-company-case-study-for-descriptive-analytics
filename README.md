# LPQI Descriptive Analytics – Project 2

This repository packages the deliverables for the LPQI case study (Case Study 02): Excel workbooks, a Power BI report, a presentation, and a meeting recording. The structure is beginner-friendly and upload-ready for GitHub.

## Repository Structure
```
project-2-lpqi-descriptive-analytics/
├─ excel/                # data dictionaries, modeling workbooks
├─ data/
│  ├─ raw/               # source inputs (add here as needed)
│  └─ processed/         # clean, analysis-ready CSVs (optional)
├─ reports/              # Power BI (.pbix) and slides (.pptx)
├─ analysis/             # notes, methodology, assumptions
├─ media/                # meeting/voice/video artifacts
├─ .gitignore
├─ .gitattributes        # Git LFS for large binaries
└─ README.md
```

## Key Files
- `excel/LPQI Actors, Interactions, Data - NOT FINAL - 250518 (Sakshi Salvi).xlsx`  
- `excel/8136 CS2 DataSet B.xlsx`  
- `reports/Case Study 02.pbix` (Power BI)  
- `reports/Case Study 02.pptx` (presentation)  
- `media/Meeting with Sakshi Sandeep Salvi-20250804_175642-Meeting Recording.mp4`

> Note: GitHub blocks single files >100 MB if you upload through the website. This repo includes Git LFS rules for `.xlsx`, `.pptx`, `.pbix`, and `.mp4`. If you install Git LFS locally later, large files will push cleanly.

## How to View
1. Open the Power BI report `reports/Case Study 02.pbix` for interactive dashboards.
2. Use `excel/8136 CS2 DataSet B.xlsx` and the actors/interactions workbook for source and supporting tables.
3. Review `reports/Case Study 02.pptx` for a concise executive summary.

## Suggested Analysis Flow
1. Validate data scope (days, shifts, line focus).  
2. Create descriptive pivots: weekly and daily views of profit loss and uninspected parts.  
3. Build capacity-utilization visuals vs. received vs. backlog.  
4. Summarize bottlenecks and propose priority queuing and capacity adjustments.

## Publishing on GitHub (Web Upload)
1. Create a new repo named `project-2-lpqi-descriptive-analytics`.
2. Click **Add file → Upload files**.
3. Drag the **contents** of the unzipped folder (not the folder itself) into the upload area.
4. Commit with “initial upload”.

## License
Add one if sharing publicly (MIT is a simple default).
