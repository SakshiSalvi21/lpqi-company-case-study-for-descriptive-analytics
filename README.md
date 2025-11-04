# LPQI Descriptive Analytics

This repository packages the deliverables for the LPQI case study (Case Study 02): Excel workbooks, a Power BI report, a presentation, and a meeting recording. 

## Repository Structure
```
project-2-lpqi-descriptive-analytics/
├─ excel/                # data dictionaries, modeling workbooks
├─ data/
│  ├─ raw/               # source inputs 
│  └─ processed/         # clean, analysis-ready CSVs 
├─ reports/              # Power BI (.pbix) and slides (.pptx)
├─ analysis/             # notes, methodology, assumptions
├─ .gitignore
├─ .gitattributes        # Git LFS for large binaries
└─ README.md
```

## Key Files
- `excel/LPQI Actors, Interactions, Data - Initial file.xlsx`  
- `excel/LPQI Final Case Study.xlsx`  
- `reports/LPQI Case Study.pbix` (Power BI)  
- `reports/LPQI Case Study.pptx` (presentation)  

## How to View
1. Open the Power BI report `reports/LPQI Case Study.pbix` for interactive dashboards.
2. Use `excel/LPQI Final Case Study.xlsx` and the actors/interactions workbook for source and supporting tables.
3. Review `reports/LPQI Case Study.pptx` for a concise executive summary.

## Analysis Flow
1. Validate data scope (days, shifts, line focus).  
2. Create descriptive pivots: weekly and daily views of profit loss and uninspected parts.  
3. Build capacity-utilization visuals vs. received vs. backlog.  
4. Summarize bottlenecks and propose priority queuing and capacity adjustments.

## Watch the full tour video (Google Drive link)
https://drive.google.com/file/d/1wN5QxjpBK9U346Kdry1TnzWYtMUQ3xku/view?usp=drive_link

## License
MIT License.
