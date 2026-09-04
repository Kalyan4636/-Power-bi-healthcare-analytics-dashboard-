# National Health Analysis — Power BI Report

## Document Purpose

This document provides an overview of the `National_Health_Analysis__Demo_-_Copy.pbix` Power BI report, including its structure, data connectivity, dependencies, and instructions for use. It is intended for analysts, developers, and stakeholders who need to open, maintain, or extend this report.

---

## 1. File Summary

| Attribute | Detail |
|---|---|
| File name | `National_Health_Analysis__Demo_-_Copy.pbix` |
| File type | Power BI Desktop report (`.pbix`) |
| Approximate size | 5.9 MB |
| Authoring tool | Power BI Desktop |
| Report format version | 1.28 |
| Connectivity mode | Live connection to a published Power BI service dataset |

---

## 2. Overview

The report presents a national-level health analysis, structured around three focus areas: patient demographics, key health trends, and treatment outcomes with associated costs. It is designed as a demonstration report and may serve as a template for a production health analytics solution.

---

## 3. Report Structure

The report consists of three pages:

| Page | Description |
|---|---|
| **Patients Demographics** | Summarizes the patient population, including demographic segmentation such as age, gender, and geography. |
| **Key Trends** | Presents high-level indicators and trend analysis across the reporting period. |
| **Treatment & Cost** | Analyzes treatment categories, outcomes, and associated cost metrics. |

Each page uses a full-page background image as part of its visual design, consistent with a presentation-style report layout rather than a standard dashboard grid.

---

## 4. Visual Components

In addition to native Power BI visuals, this report incorporates the following third-party custom visuals from the ZoomCharts visual suite:

- ZoomCharts Facet Chart (Free and Pro editions)
- ZoomCharts Pie Chart (Pro edition)
- ZoomCharts Drill Down Combo Bar (Pro edition)

## 5. Dashboard Presentation : 

<img width="951" height="379" alt="National Health Analysis — Power BI Report 5" src="https://github.com/user-attachments/assets/89ee0428-5e07-4371-a06b-ff01e8f8ceda" />

<img width="956" height="399" alt="National Health Analysis — Power BI Report 4" src="https://github.com/user-attachments/assets/554d3cda-c2fc-4dfd-be74-4520ec98b1de" />

<img width="959" height="366" alt="National Health Analysis — Power BI Report 3" src="https://github.com/user-attachments/assets/43746d46-e376-4ee6-8b4a-51c561a2147f" />

<img width="959" height="437" alt="National Health Analysis — Power BI Report 2" src="https://github.com/user-attachments/assets/e7e1c311-a4ef-490e-beb7-b7384db12265" />

<img width="947" height="398" alt="National Health Analysis — Power BI Report 1" src="https://github.com/user-attachments/assets/d1ed7d21-24fb-4ff1-a1fd-530374939cb6" />

<img width="938" height="331" alt="National Health Analysis — Power BI Report 6" src="https://github.com/user-attachments/assets/d4422214-42b8-40ce-b3ed-ccee3e703797" />

<img width="739" height="440" alt="National Health Analysis — Power BI Report  7" src="https://github.com/user-attachments/assets/71b31541-fafc-4f29-b73c-2caed0d69bfb" />



























**Licensing requirement:** The Pro editions of these visuals require a valid ZoomCharts license for full functionality. Reports opened without an active license may display these visuals in a restricted or preview state.

---

## 5. Data Source and Connectivity

This report is configured as a **live connection** to a dataset published in the Power BI service, referenced internally by dataset and report identifiers. It does not operate as a self-contained, import-mode file.

To work with the underlying data, one of the following is required:

1. Access to the Power BI service workspace hosting the connected dataset, with appropriate viewer or contributor permissions; or
2. Reconfiguration of the report to import mode, connecting it to an alternative dataset with a compatible schema (patient, demographic, treatment, and cost dimensions).

---

## 6. Prerequisites

- Power BI Desktop (current version recommended)
- Valid credentials for the connected Power BI service workspace
- Internet connectivity, required for dataset refresh and custom visual licensing validation
- A ZoomCharts license, if editing or refreshing the Pro-tier visuals

---

## 7. Usage Instructions

1. Open `National_Health_Analysis__Demo_-_Copy.pbix` in Power BI Desktop.
2. Sign in with an account authorized to access the connected dataset, when prompted.
3. Navigate between the **Patients Demographics**, **Key Trends**, and **Treatment & Cost** pages using the page tabs.
4. Apply available slicers and filters to analyze specific patient segments, time periods, or treatment categories.
5. To publish a copy to a Power BI workspace, use **File → Publish** within Power BI Desktop.

---

## 8. Recommended Repository Structure

```
/reports
  └── National_Health_Analysis_Demo.pbix
/docs
  └── README.md
```

---

## 9. Governance and Disclaimer

This file is designated as a **demonstration report**. All data, metrics, and visualizations are illustrative and have not been validated for clinical, operational, or policy use. Any production deployment should undergo data validation, security review, and access control configuration consistent with organizational governance standards.

---

## 10. Document Control

| Field | Value |
|---|---|
| Prepared | September 2026 |
| Status | Draft |
| Owner | *(assign report owner)* |
| Review cycle | *(assign review cadence)* |
