# SEO Analysis Script with PHP and Web Scraping/Curl Techniques

This repository presents an experimental effort conducted for the purpose of a publication in an international journal. The script, built using PHP function programming and web scraping/curl techniques, takes a list of URLs as input, fetches their source code, and performs checks to identify which of the 18 predefined SEO techniques each page follows.

## Features

- Accepts a list of URLs for analysis
- Extracts the source code of each URL
- Performs SEO checks based on 18 predefined techniques
- Integrates with third-party APIs to fetch various SEO metrics:
  - Domain Authority (MOZ API)
  - Website Speed (PageSpeed Insights API - Google)
  - Webpage Responsiveness (Mobile-Friendly Test API - Google)

## Usage

1. Clone the repository to your local machine.
2. Ensure you have PHP and necessary dependencies installed.
3. Add the list of URLs you want to analyze in the appropriate format.
4. Run the script and view the analysis results for each URL.

## Improvements

This approach is experimental and could be optimized by refining individual functions or grouping them into classes for better organization and maintainability.

Feel free to contribute and improve the script further!
