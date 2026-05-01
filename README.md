# Disk Usage Analyzer

**Name:** Mudansuru Auwalu Garba  
**SAP ID:** 66292  
**Course:** Operating System  
**Instructor:** Sir. Yawar Abbas  

---

## Features
- Scan any local folder recursively
- Auto-detect USB / removable drives
- Tree view of all folders with sizes
- Summary: total size, file count, folder count
- Top 15 largest files list
- Bar Chart & Pie Chart visualization
- Export full report to .txt

## Requirements
- Python 3.10+
- matplotlib

## Setup

```bash
pip install -r requirements.txt
python main.py
```

## File Structure

```
DiskUsageAnalyzer/
├── main.py                  # Entry point
├── requirements.txt
├── README.md
├── core/
│   ├── __init__.py
│   ├── disk_scanner.py      # Scanning + USB detection logic
│   └── reporter.py          # Report export
└── gui/
    ├── __init__.py
    ├── app.py               # Main Tkinter window
    └── chart_window.py      # Matplotlib bar/pie charts
```
