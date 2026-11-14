# Time Series CSV Summary Explorer

An interactive HTML tool for visualising time-series CSV summary data as heatmaps, with filters and split-by options for any field.

## Features

- Drag and drop one or more CSV files.
- Filter by field values and time range.
- Split the heatmap by selected dimensions.
- Explore summary trends and counts visually.
- Export filtered results as PNG or CSV.

## Usage

1. Open `SummaryExplorer.html` in a browser.
2. Drag in one or more compatible CSV files.
3. Use the controls at the top to filter values and adjust the view.
4. Explore the heatmap and summary charts.

## CSV format

The app expects CSV files with:

- one or more filter columns
- one or more date/time columns in `YYYY-MM-DD` or `DD/MM/YYYY` format
- values that can be aggregated by count over time

## Notes

This project is designed as a lightweight, self-contained browser app with no build step.
