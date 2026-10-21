# CDaX-Data-Analytics

CDaX Data Analytics and Power BI Dashboard

## About

This repository contains the data analytics work prepared for the CDaX project using available backend seed data, sample data, Excel, SQL, and Power BI.

## Work Included

* CDaX Data Dictionary
* Excel Data Preparation for Power BI
* Power BI Dashboard
* KPI Definitions and Formulas
* Event Tracking Specification
* Student Funnel Analysis
* Student Lifecycle Analysis
* Recording Consumption Analysis
* Course Switching Analysis
* Recommendation & Experimentation Plan
* Student Engagement Model
* Student Value Segmentation
* Management Analytics
* Data Quality Audit
* Revenue Forecasting Model
* Course Demand Forecasting Model
* Attendance Pattern Analysis
* Certificate & Completion Analysis
* Notification Effectiveness Analysis
* Mentor Allocation Model
* Live Class Capacity Model
* Pricing Scenario Simulator
* Learning Outcome Measurement Model
* Assessment Question Quality Analyzer

## Data Source

The analysis uses available CDaX sample data and backend seed data. Missing or unverified information is left blank or documented as a data gap. Forecasts and proposed scenarios are distinguished from actual results.

## Data Dictionary

Documents CDaX entities, fields, data types, descriptions, required/optional status, examples, sources, and relationships.

## Power BI Dashboard

Uses prepared Excel data to present available CDaX metrics, business performance, and trends.

## KPI Analysis

Defines KPIs, formulas, data sources, reporting frequency, and business purpose.

## Student Funnel Analysis

Tracks the student journey:

Visitor → Registration → Demo → Enrollment → First Class → Active Student → Project → Course Completion → Certificate

Includes stage-wise counts, conversion rates, drop-offs, time between stages, cohort comparisons, and data gaps. Unavailable values are left blank.

## Student Lifecycle Analysis

Tracks the student journey:

Registration → Demo → Enrollment → Learning → Projects → Completion → Certificate → Renewal / Switch / Exit

Analyzes stage conversions, drop-offs, learning activity, course participation, switching, completion, renewal, and lifecycle data gaps.

## Recording Consumption Analysis

Analyzes recording starts, watch duration, completion percentage, repeat viewing, downloads, popular recordings, viewing patterns, and student engagement. Missing recording events and timestamps are documented as data gaps.

## Course Switching Analysis

Examines course switches, original and new courses, switching dates, time to switch, switching paths, available reasons, and course-level patterns. Unavailable switching records are not estimated.

## Event Tracking Specification

Defines application events, triggers, required parameters, user IDs, course IDs, timestamps, session details, and business attributes for registration, demos, enrollment, classes, recordings, projects, assessments, subscriptions, switching, certificates, and support.

## Recommendation & Experimentation Plan

Defines recommendations for alternative courses, projects, learning content, mentor support, related courses, and upgrades.

Uses the approach:

Recommendation → Student Action → Outcome

Includes experiment design, control and test groups, success metrics, and available data mappings.

## Student Engagement Model

Evaluates student engagement using login activity, attendance, participation, recording usage, streaks, projects, and assessments.

Defines the engagement categories:

Highly Engaged → Active → Declining → At Risk

Missing activity data is documented rather than treated as confirmed engagement.

## Student Value Segmentation

Evaluates student value using course participation, subscription duration, renewals, switching, projects, completion, support usage, and revenue.

Defines High, Medium, and Low Value profiles using a proposed scoring framework. Students with insufficient verified information are classified as **Insufficient Data**.

## Management Analytics

Maps business questions to metrics, data sources, and analysis methods.

Covers registrations, active students, course performance, attendance, demo conversion, subscriptions, drop-offs, switching, projects, assessments, recordings, certificates, revenue, payments, and support.

## Data Quality Audit

Checks data accuracy, completeness, and consistency, including:

* Missing and duplicate records
* Incorrect IDs and invalid payments
* Missing attendance and timestamps
* Subscription and course-switching issues
* Recording, project, and assessment gaps
* Frontend/backend mismatches
* Table relationships and join issues

Documents identified issues, validation requirements, and unavailable source data.

## Revenue Forecasting Model

Forecasts future revenue using student growth, subscription pricing, renewals, and cancellations.

Includes monthly forecasts and Best-case, Base-case, and Worst-case scenarios. Missing historical revenue or subscription data is documented separately from forecast assumptions.

## Course Demand Forecasting Model

Forecasts potential demand for individual courses using available enrollment history and other verified signals.

Analyzes expected enrollments, demand trends, seasonal changes, and course capacity requirements. Missing historical data is documented rather than invented.

## Attendance Pattern Analysis

Analyzes attendance consistency, declining attendance, selective class attendance, weekday versus weekend patterns, class timings, holiday effects, and the relationship between attendance and course completion.

Unavailable attendance records and scheduling information are documented as data gaps.

## Certificate & Completion Analysis

Tracks the journey:

Enrollment → Learning → Assessment → Project → Completion → Certificate

Analyzes completion rates, certification rates, time to certification, course-wise results, and students who complete learning without obtaining certificates.

Available sample data indicates 3 enrolled students, 1 student with observed learning activity, and 0 students with 100% course completion. Actual certificate records are unavailable in the reviewed sample, so certification metrics cannot currently be calculated.

## Notification Effectiveness Analysis

Evaluates App, Email, SMS, and Push Notifications and their potential impact on student returns, attendance, recording consumption, and project activity.

Includes notification tracking, effectiveness metrics, student behavior, and data availability. Missing notification records are documented as data gaps.

## Mentor Allocation Model

Helps determine how mentors should be allocated across students and courses.

Analyzes:

* Student volume and course difficulty
* Attendance and support requirements
* Project and mentor workload
* Response time and workload balance
* Recommended mentor allocation

Missing mentor data is documented, and proposed allocations are distinguished from actual assignments.

## Live Class Capacity Model

Evaluates whether available live-class capacity can meet student demand.

Analyzes:

* Student enrollment and class demand
* Existing classes and class capacity
* Attendance and capacity utilization
* Required number of classes
* Capacity gaps and planning recommendations

Missing or unverified information is documented rather than presented as actual results.

## Pricing Scenario Simulator

Compares alternative pricing options and their potential business impact.

Analyzes:

* Current and alternative pricing
* Subscription and enrollment assumptions
* Monthly and annual revenue projections
* Best-case, Base-case, and Worst-case scenarios
* Revenue comparisons across pricing options

Unverified prices and historical revenue are documented as data gaps. Scenario assumptions are clearly distinguished from actual results.

## Learning Outcome Measurement Model

Evaluates whether students are achieving the intended learning outcomes from CDaX courses.

Analyzes:

* Learning objectives and course outcomes
* Assessment scores and student performance
* Pre-assessment and post-assessment comparisons, where available
* Course-wise and topic-wise learning progress
* Learning improvement and outcome achievement
* Students requiring additional learning support
* Data gaps affecting outcome measurement

Uses available assessment and learning data. Missing baseline scores, assessment results, or learning outcome mappings are documented rather than estimated. Learning improvement can only be measured where the required data is available.

## Assessment Question Quality Analyzer

Evaluates the quality, difficulty, and effectiveness of questions used in CDaX quizzes, tests, and examinations.

Analyzes:

* Question difficulty
* Percentage of students answering correctly
* Correct and incorrect response patterns
* Question-wise student performance
* Assessment and topic-wise performance
* Questions that may be too easy or too difficult
* Questions requiring review based on available evidence

Uses available question, assessment, and student response data. Metrics such as percentage correct, difficulty classification, and question discrimination require sufficient response-level data. Missing question IDs, answer keys, student responses, or marks are documented as data gaps rather than replaced with assumed results.

## Files

* `CDAX_Data_Dictionary.xlsx` — CDaX data dictionary
* `CDaX PowerBI Data.xlsx` — Excel data prepared for Power BI
* `CDAX.pbix` — Power BI dashboard
* `CDAX_KPI_Formula.xlsx` — KPI definitions and formulas
* `CDAX_Event_Tracking_Specification.xlsx` — Event tracking specification
* `CDAX_Student_Funnel_Analysis.xlsx` — Student funnel analysis
* `CDAX_Student_Lifecycle_Analysis.xlsx` — Student lifecycle analysis
* `CDAX_Recording_Consumption_Analysis.xlsx` — Recording consumption analysis
* `CDAX_Course_Switching_Analysis.xlsx` — Course switching analysis
* `CDAX_Recommendation_Experimentation_Plan.xlsx` — Recommendation and experimentation plan
* `CDAX_Student_Engagement_Model.xlsx` — Student engagement scoring model
* `CDAX_Student_Value_Segmentation.xlsx` — Student value segmentation
* `CDAX_Management_Analytics.xlsx` — Management analytics framework
* `CDAX_Data_Quality_Audit.xlsx` — Data quality audit
* `CDAX_Revenue_Forecasting_Model.xlsx` — Revenue forecasting model
* `CDAX_Course_Demand_Forecast.xlsx` — Course demand forecasting model
* `CDAX_Attendance_Pattern_Analysis.xlsx` — Attendance pattern analysis
* `CDAX_Certificate_Completion_Analysis.xlsx` — Certificate and completion analysis
* `CDAX_Notification_Effectiveness_Analysis.xlsx` — Notification effectiveness analysis
* `CDAX_Mentor_Allocation_Model.xlsx` — Mentor allocation and workload planning
* `CDAX_Live_Class_Capacity_Model.xlsx` — Live-class capacity planning
* `CDAX_Pricing_Scenario_Simulator.xlsx` — Pricing scenario comparison and revenue simulation
* [CDAX_Learning_Outcome_Measurement_Model.xlsx](https://github.com/PranitVarat/CDaX-Data-Analytics/blob/main/CDAX_Learning_Outcome_Measurement_Model.xlsx) — Learning outcome measurement and student progress analysis
* [CDAX_Assessment_Question_Quality_Analyzer.xlsx](https://github.com/PranitVarat/CDaX-Data-Analytics/blob/main/CDAX_Assessment_Question_Quality_Analyzer.xlsx) — Assessment question difficulty and quality analysis
