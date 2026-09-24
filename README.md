# CDaX-Data-Analytics

CDaX Data Analytics and Power BI Dashboard

## About

This repository contains the data analytics work prepared for the CDaX project.

## Work Included

* CDaX Data Dictionary
* Excel data prepared for Power BI
* KPI definitions and formulas
* Power BI dashboard
* CDaX Event Tracking Specification
* CDaX Student Funnel Analysis
* CDaX Recommendation & Experimentation Plan

## Data Source

The data was prepared based on the available CDaX sample data and backend seed data. The data was organized and prepared in Excel according to the analytics requirements.

Some KPIs and funnel stages do not have sample or seed data available, so those values have been left blank and documented accordingly.

## Data Dictionary

The data dictionary contains the CDaX entities and their related fields, including data types, descriptions, required/optional status, example values, sources, and relationships.

## KPI Analysis

The KPI file contains KPI definitions, formulas, data sources, frequency, and business purpose.

## Student Funnel Analysis

The student funnel analysis tracks the CDaX student journey through the following stages:

Visitor → Registration → Demo → Enrollment → First Class → Active Student → Project → Course Completion → Certificate

The analysis includes:

* Stage-wise student counts
* Conversion rate
* Drop-off rate
* Time between stages
* Cohort-level comparison
* Backend data source mapping
* Data availability and quality notes

Only available sample and backend data has been used. Where the required data is not available, the corresponding funnel value has been left blank.

## Event Tracking Specification

The event tracking specification defines the events required for the CDaX application, including triggers, required parameters, user ID, course ID, timestamp, session ID, device/platform, and relevant business attributes.

The specification covers pre-launch tracking requirements for registration, login, demo booking, demo attendance, course viewing, course enrollment, class attendance, recording usage, project activity, assessment activity, subscription, course switching, certificate generation, and support requests.

## Recommendation & Experimentation Plan

The recommendation and experimentation plan defines data-driven recommendations for CDaX students, including:

* Alternative courses
* Recommended projects
* Recommended learning content
* Mentor/support intervention
* Related courses
* Upsell/upgrade opportunities

The plan follows the approach:

Recommendation → Student Action → Outcome

Experiments use control and test groups to measure whether recommendations improve the desired outcomes. The plan includes success metrics and mapping to the available CDaX backend data.

## Power BI Dashboard

The Power BI dashboard was created using the prepared Excel data. It includes analysis of CDaX-related data, metrics, and trends.

## Files

* `CDAX Data Dictionary.xlsx` — CDaX Data Dictionary
* `CDaX PowerBI Data.xlsx` — Excel data used to create the Power BI dashboard
* `CDAX_KPI_Formula.xlsx` — KPI definitions and formulas
* `CDAX_Event_Tracking_Specification.xlsx` — CDaX event tracking specification
* `CDAX_Student_Funnel_Analysis_Final.xlsx` — CDaX student funnel analysis
* `CDAX_Recommendation_Experimentation_Plan.xlsx` — CDaX recommendation and experimentation plan
* `CDAX.pbix` — Power BI dashboard
