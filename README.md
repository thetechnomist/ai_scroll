# Welcome to the timeline of AI

This code is a modification of the following gist: https://gist.github.com/jillianjean98/ee419f3a69e26d3ef4bddf6bd6d43d4e

This project visualizes the history of Artificial Intelligence (AI) using Plotly, D3.js, and data from multiple CSV files. The chart displays significant AI developments, n-gram data, and Google Trends popularity over time.

## Files and Data

* `datasort.csv`: Contains historical AI events, including the year, category, and description.
* `ngram_updated.csv`: Contains n-gram data with AI-related term frequencies over the years.
* `google_trends.csv`: Contains AI popularity data from Google Trends over the years.

## Visualization Features

* Scatter Plot: Displays AI developments categorized as Creative Work, Foundational Research, Important Paper, Physical Device or Technology, and Philosophy or Theory.
* Line Plot: Shows n-gram data trends and Google Trends AI popularity data.
* Hover Tooltips: When hovering over a point, the tooltip shows all events and n-gram values for that year.
* *AI Winters: Vertical dashed lines indicate AI Winter years (periods of reduced AI funding and interest).

## How to Use

1. Ensure the *datasort.csv, ngram_updated.csv, and google_trends.csv* files are in the data directory.
2. Open the HTML file in a web browser (you can run a `python3 -m http.server` )
3. Hover over data points to see detailed information about AI events and trends for each year.

## Contribution

Please feel free to update the data, especially the events and add the ngrams (PRs are welcome)!