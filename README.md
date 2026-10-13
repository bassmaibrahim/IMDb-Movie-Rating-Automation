# IMDb Movie Rating Automation

A UiPath RPA project that automates movie data processing by reading movie titles from Excel and interacting with IMDb through browser automation.

## Overview

This project demonstrates how UiPath can automate repetitive tasks involving Excel data and browser interactions. The workflow reads movie titles from an Excel file, searches for the corresponding IMDb entries, and is designed to organize the collected ratings into a structured output file.

## Technologies Used

- UiPath Studio
- Microsoft Excel
- UiPath UI Automation activities
- DataTables
- Variables and control-flow activities
- Browser automation and selectors

## Workflow

1. Read movie titles from the input Excel file.
2. Iterate through the movie records.
3. Search for each movie on IMDb using browser automation.
4. Extract the IMDb rating, where implemented.
5. Store the processed information in an Excel output file, where implemented.

## Project Structure

```text
IMDb-Movie-Rating-Automation/
├── project/
│   ├── project.json
│   └── Main.xaml
├── sample-data/
│   └── Movies.xlsx
├── screenshots/
├── demo/
└── README.md
```


## Prerequisites

- Windows
- UiPath Studio
- A compatible browser supported by your UiPath setup
- Microsoft Excel or a compatible spreadsheet application

## How to Run

1. Clone or download this repository.
2. Open UiPath Studio.
3. Open the project using its `project.json` file.
4. Restore the required dependencies if prompted.
5. Check the input Excel file path and update it if necessary.
6. Run the main workflow.
7. Review the processed data and output files.


## Demo

[Watch the project demo](https://drive.google.com/file/d/1cgAR2_pkPE_YiCslHY-W-18iMl-sUjvF/view?usp=sharing)

## Skills Demonstrated

- Excel automation and data processing
- DataTables and iteration
- Browser automation
- UI selectors
- Structured workflow design

## Future Improvements

- Add robust handling for missing movies and failed searches.
- Add retries and logging for unexpected errors.
- Generate a processing summary for successful and failed records.
- Make file paths configurable for easier reuse.

## Disclaimer

This is an educational automation project. IMDb is a third-party website; website structure and access restrictions may change. Use the automation responsibly and respect the website's applicable terms.
