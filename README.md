# Cafe Sales Data Cleansing Project

## Project Objective
The goal of this project was to take a raw, unformatted, and error-ridden cafe sales dataset containing 10 transactions and transform it into a clean, accurate, and standardized data table ready for business analysis.

## Data Cleaning Checklist Completed:
* **Removed Duplicates:** Identifed and deleted duplicate entries for transaction ID `TXN_102`.
* **Standardized Formats:** Converted mismatched date strings into a uniform `YYYY-MM-DD` date format and standardized text string spacing using `=TRIM()`.
* **Fixed Data Anomaly Math:** Calculated missing quantities, total spent, and unit prices using logical spreadsheet formulas (`Revenue = Qty * Price`).
* **Categorized Inconsistent Inputs:** Used Find & Replace tools to bundle vague payment types (`UNKNOWN` and `None`) into a standardized `Other` category.
* **Professional Design:** Implemented executive-ready formatting, currency styles, and clean column alignments.

## Tools & Formulas Used
* Google Sheets / Microsoft Excel
* `TRIM()`
* Basic Mathematical Operators (`*`, `/`)
* Find & Replace
* Number & Currency Formatting Tools
