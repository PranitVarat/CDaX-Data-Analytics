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
* CDaX Student Lifecycle Analysis
* CDaX Recommendation & Experimentation Plan
* CDaX Student Engagement Model
* CDaX Management Analytics
* CDaX Data Quality Audit

## Data Source

The data was prepared based on the available CDaX sample data and backend seed data. The data was organized and prepared in Excel according to the analytics requirements.

Some KPIs, funnel stages, and lifecycle stages do not have sample or seed data available, so those values have been left blank and documented accordingly.

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

## Student Lifecycle Analysis

The student lifecycle analysis tracks the complete CDaX student journey from registration until renewal, course switching, or exit.

The lifecycle stages include:

Registration → Demo → Enrollment → Learning → Projects → Completion → Certificate → Renewal / Switch / Exit

The analysis includes:

* Stage-wise student counts
* Stage-to-stage conversion rate
* Drop-off rate
* Average time between stages
* Student learning activity
* Number of courses taken
* Course switching
* Certificate completion
* Renewal behavior
* Student-level journey tracking
* Data availability and lifecycle gaps

The analysis is based only on the available CDaX sample and backend data. Where lifecycle data is not available, the stage has been documented as a data gap rather than using estimated values.

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

## Student Engagement Model

The student engagement model defines a systematic method to identify changes in student engagement using available CDaX data.

The model considers:

* Login activity
* Attendance
* Class participation
* Recording usage
* Learning streak
* Project activity
* Assessment activity

Each signal is scored and weighted to calculate an overall engagement score. Students are then categorized as:

Highly Engaged → Active → Declining → At Risk

The methodology is based on available backend data and is designed to help identify students who may need early support or intervention.

## Management Analytics

The management analytics framework identifies important business questions that management needs to understand from CDaX data.

It covers:

* Student registrations and active students
* Course performance and enrollment
* Student attendance
* Demo-to-enrollment conversion
* Subscription and plan selection
* Student drop-off
* Course switching
* Project and assessment performance
* Recording usage and learning activity
* Course completion and certificates
* Revenue and payments
* Student support

Each business question is mapped to the required metric, data source, and analysis method.

## Data Quality Audit

The CDaX Data Quality Audit checks whether the available data is accurate, complete, consistent, and usable for business analysis.

The audit covers:

* Missing student records
* Duplicate students
* Duplicate enrollments
* Incorrect course IDs
* Invalid payment records
* Missing attendance
* Impossible timestamps
* Inconsistent subscription status
* Missing course-switch information
* Incorrect or null project data
* Incorrect or null assessment data
* Frontend and backend data mismatch
* Tables and records that cannot be properly joined

The audit also documents identified data issues, data gaps, validation requirements, and the additional source data required for checks that cannot be fully validated.

## Power BI Dashboard

The Power BI dashboard was created using the prepared Excel data. It includes analysis of CDaX-related data, metrics, and trends.

## Files

* `CDAX_Data_Dictionary.xlsx` — CDaX Data Dictionary
* `CDaX PowerBI Data.xlsx` — Excel data used to create the Power BI dashboard
* `CDAX_KPI_Formula.xlsx` — KPI definitions and formulas
* `CDAX_Event_Tracking_Specification.xlsx` — CDaX event tracking specification
* `CDAX_Student_Funnel_Analysis.xlsx` — CDaX student funnel analysis
* `CDAX_Student_Lifecycle_Analysis.xlsx` — CDaX student lifecycle analysis from registration through renewal, switching, or exit
* `CDAX_Recommendation_Experimentation_Plan.xlsx` — CDaX recommendation and experimentation plan
* `CDAX_Student_Engagement_Model.xlsx` — CDaX student engagement scoring methodology
* `CDAX_Management_Analytics.xlsx` — CDaX management analytics framework
* `CDAX_Data_Quality_Audit.xlsx` — CDaX data quality audit
* `CDAX.pbix` — Power BI dashboard
