# README

## Overview
This project is a single-page web app that generates all required files for a GitHub Pages site and provides direct Open/Download links for each. It includes:
- ashravan.txt: A 300–400 word short story about Ashravan after his restoration.
- dilemma.json: Two autonomous-vehicle ethical scenarios with rationale.
- about.md: Exactly three words describing the developer.
- pelican.svg: A valid SVG of a pelican riding a bicycle, plus an on-page LLM-style rating.
- restaurant.json: A Kolkata restaurant recommendation with coordinates and a signature dish.
- prediction.json: A reasonable forecast of the Fed Funds rate by December 2025.
- LICENSE: MIT License text.
- uid.txt: Populated by you with the provided UID attachment.

The index page links to all assets via data URIs so you can download and commit them into your repository.

## Setup
1. Open index.html in your browser (or host it via GitHub Pages).
2. Optional: Paste your UID content into the UID section so the generated uid.txt matches your attachment.
3. Click “Download all as .zip” to get a bundle of all files, or download each file individually.

## Usage
- Commit the downloaded files to the root of your public GitHub repository.
- Ensure GitHub Pages is enabled (Settings → Pages).
- Verify:
  - LICENSE contains MIT text.
  - about.md has exactly three words.
  - ashravan.txt is 300–400 words.
  - dilemma.json matches the specified schema.
  - pelican.svg renders correctly and is valid SVG.
  - restaurant.json looks consistent for Kolkata.
  - prediction.json has a rate between 0 and 1.
  - uid.txt exactly matches the provided attachment.

Tip: Use the built-in checks panel on index.html to quickly verify constraints before committing.

## If Round 2
N/A for Round 1. In a subsequent round, improvements would include:
- Auto-publishing via GitHub API (with a token) directly from the browser.
- Schema validation UI and downloadable checks report.
- Editable fields for scenario parameters and prediction assumptions.