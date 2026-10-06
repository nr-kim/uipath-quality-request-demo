# UiPath Quality Request Demo

A simple UiPath demo for automating quality request processing.

The workflow reads request data from a CSV file, filters requests by status and priority, enters the relevant data into a web form, and saves the processed results to a CSV file.

## Demo Video
You can watch the workflow in action at this link.
**[https://youtu.be/TqYezQofDWA]**

## Features

- Reads quality request data from CSV
- Filters requests with:
  - Status = Open
  - Priority = High
- Automatically enters request data into a web form
- Submits each request using UiPath browser automation
- Saves processed requests to a result CSV
- Includes basic error handling

## Demo Web Form

The test web form is hosted with GitHub Pages:

https://nr-kim.github.io/uipath-quality-request-demo/

## Requirements

- UiPath Studio
- Google Chrome
- UiPath browser extension

## How to Run

1. Download or clone this repository.
2. Open the project in UiPath Studio.
3. Open `Main.xaml`.
4. Run the workflow.
5. The workflow automatically opens the demo web form and processes the matching CSV entries.

## Project Files

- `Main.xaml` – Main UiPath workflow
- `project.json` – UiPath project configuration
- `automotive_quality_requests.csv` – Sample input data
- `processed_requests.csv` – Example output
- `index.html` – Demo web form used by the automation

## Workflow

CSV Data  
→ Filter Open & High Priority Requests  
→ Open Web Form  
→ Enter Request Data  
→ Submit Request  
→ Save Processed Results

## Purpose

This project was created as a small practical exercise to explore browser automation and CSV-based data processing with UiPath.
