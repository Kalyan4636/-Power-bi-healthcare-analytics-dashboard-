National Health Analysis 

A Power BI report exploring patient demographics, health trends, and treatment costs. 

File
Property	Value
File name	National_Health_Analysis__Demo_-_Copy.pbix
File type	Power BI Desktop report (.pbix)
File size	~5.9 MB
Built with	Power BI Desktop
Data connectivity	Connected live to a Power BI service dataset (the file references a remote dataset/report ID rather than storing all data locally — see Data Source below)
Overview

This report is a demo/sample analysis of health data, organized around patient profiles, health trend indicators, and treatment/cost outcomes. It is intended as a template or starting point for building out a full national health analytics dashboard.

Report Pages

The report contains 3 pages:

Patients Demographics — profile of the patient population (e.g., age, gender, geography, and related demographic breakdowns).
Key Trends — high-level trend indicators and KPIs across the dataset over time.
Treatment & Cost — treatment types, outcomes, and associated cost analysis.

Note: Each page uses a full-page themed background image, giving the report a custom, magazine-style visual layout rather than a standard grid dashboard.

Visuals

In addition to Power BI's native visuals, the report uses the following custom visuals (from the ZoomCharts family):

ZoomCharts Facet Chart (Free & Pro editions)
ZoomCharts Pie Chart (Pro)
ZoomCharts Drill Down Combo Bar (Pro)

Note on licensing: The Pro editions of these visuals require a valid ZoomCharts license to render with full functionality when opened or edited. Without a license, some visuals may display in a limited/preview mode.

Data Source

The report's Connections configuration points to a remote Power BI dataset (via dataset/report IDs), meaning this file is set up as a live connection report against a dataset published to the Power BI service, rather than a fully self-contained import-mode file. To refresh or fully interact with the data:

You will need access to the underlying Power BI service workspace/dataset the report connects to, or
You can convert the report to import mode and connect it to your own health dataset with a comparable schema (patients, demographics, treatments, costs, dates).
Requirements
Power BI Desktop (latest version recommended) to open and edit the .pbix file.
Internet access if the ZoomCharts custom visuals need to be validated/licensed, or if refreshing the live-connected dataset.
Appropriate permissions on the source Power BI workspace/dataset for data refresh.
How to Use
Open National_Health_Analysis__Demo_-_Copy.pbix in Power BI Desktop.
If prompted, sign in with an account that has access to the connected dataset.
Navigate between the Patients Demographics, Key Trends, and Treatment & Cost pages using the tabs at the bottom of the report.
Use any slicers/filters on each page to drill into specific patient segments, time periods, or treatment categories.
To publish your own copy, use File → Publish in Power BI Desktop (requires a Power BI account/workspace).
Suggested Repository Structure

If versioning this file in a repository, consider:

/reports
  └── National_Health_Analysis_Demo.pbix
/docs
  └── README.md
Disclaimer

This is a demo file — data, visuals, and metrics are for illustrative purposes only and should not be used for clinical, operational, or policy decision-making without validation against verified source data.

Last documented: September 2026
