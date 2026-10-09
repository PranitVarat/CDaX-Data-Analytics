# CDaX-Data-Analytics

CDaX Data Analytics and Power BI Dashboard

## About

This repository contains the data analytics work prepared for the CDaX project.

## Work Included

* CDaX Data Dictionary
* Excel data prepared for Power BI
* Power BI dashboard
* KPI definitions and formulas
* CDaX Event Tracking Specification
* CDaX Student Funnel Analysis
* CDaX Student Lifecycle Analysis
* CDaX Recording Consumption Analysis
* CDaX Course Switching Analysis
* CDaX Recommendation & Experimentation Plan
* CDaX Student Engagement Model
* CDaX Student Value Segmentation
* CDaX Management Analytics
* CDaX Data Quality Audit
* CDaX Revenue Forecasting Model
* CDaX Course Demand Forecasting Model
* CDaX Attendance Pattern Analysis
* CDaX Certificate & Completion Analysis
* CDaX Notification Effectiveness Analysis

## Data Source

The data was prepared based on the available CDaX sample data and backend seed data. The data was organized and prepared in Excel according to the analytics requirements.

Some KPIs, funnel stages, lifecycle stages, student value dimensions, subscription records, revenue-related data, recording consumption data, course-switching data, attendance records, assessment records, project activity, and certificate records do not have sample or seed data available or fully verified. Therefore, those values have been left blank or documented as data gaps accordingly.

## Data Dictionary

The data dictionary contains the CDaX entities and their related fields, including data types, descriptions, required/optional status, example values, sources, and relationships.

## Power BI Dashboard

The Power BI dashboard was created using the prepared Excel data. It includes analysis of CDaX-related data, metrics, and trends.

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

## Recording Consumption Analysis

The recording consumption analysis is designed to understand how students consume recorded learning content.

The analysis covers:

* Recording starts
* Watch duration
* Completion percentage
* Repeat watching
* Download activity
* Time between download and viewing
* Most watched recordings
* Least watched recordings
* Recordings where students frequently stop watching
* Student-level recording consumption
* Recording-level engagement patterns
* Data availability and tracking gaps

The analysis helps identify which recorded content is being consumed effectively and where students are dropping off during recordings.

The analysis is based on available CDaX recording and backend data. Where recording start, watch duration, completion, repeat viewing, download, or viewing timestamps are not available or fully verified, the corresponding values have been left blank and documented as data gaps.

## Course Switching Analysis

The course switching analysis is designed to understand student course-switching behavior within CDaX.

The analysis covers:

* Number of course switches
* Students who switched courses
* Original course
* New course
* Course-switch date
* Time between enrollment and switching
* Most common course-switching paths
* Courses with higher switching activity
* Reasons for course switching where available
* Student-level switching history
* Course-switching patterns and trends
* Data availability and tracking gaps

The analysis helps identify which courses students switch from and to, and can support course improvement, student recommendations, retention analysis, and business decision-making.

Only available CDaX sample and backend data has been used. Where course-switch records, switch reasons, timestamps, or related enrollment information are not available or fully verified, the corresponding values have been left blank and documented as data gaps.

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

## Student Value Segmentation

The student value segmentation analysis identifies which types of students can create the most long-term value for CDAX.

The analysis considers:

* Number of courses taken
* Subscription duration
* Renewals
* Course switching
* Project activity
* Course completion
* Support usage
* Revenue generated

The analysis includes:

* Student value dimensions
* Student-level value analysis
* High, Medium, and Low Value profile definitions
* Weighted value scoring framework
* Student value profiles
* Backend data mapping
* Data availability and gaps

The value scoring framework assigns weights across the major value dimensions to support future student segmentation.

The defined segments are:

High Value → Multiple courses, longer subscription, renewals, project activity, high completion, and higher revenue

Medium Value → Moderate course usage, active learning, some completion/project activity, and limited repeat activity

Low Value → Single course, low learning activity, low completion, and limited repeat activity

Where required student-level backend data is not available or fully verified, the student is classified as:

Insufficient Data

No revenue, renewal, subscription, project, switching, or support values have been invented where the required records were not verified.

## Management Analytics

The management analytics framework identifies important business questions that management needs to understand from CDAX data.

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
* Missing or incomplete recording consumption data
* Incorrect or null project data
* Incorrect or null assessment data
* Frontend and backend data mismatch
* Tables and records that cannot be properly joined

The audit also documents identified data issues, data gaps, validation requirements, and the additional source data required for checks that cannot be fully validated.

## Revenue Forecasting Model

The revenue forecasting model is designed to estimate future CDaX revenue based on student growth and subscription behavior.

The model includes:

* Student growth assumptions
* Subscription mix and pricing
* Renewal assumptions
* Cancellation assumptions
* Monthly revenue forecast
* Best-case, Base-case, and Worst-case scenarios

The model uses the available CDaX data and defined subscription pricing. Where historical subscription or revenue data is not available or fully verified, the values are documented as data gaps or forecast assumptions rather than using invented historical values.

## Attendance Pattern Analysis

The attendance pattern analysis goes beyond basic attendance percentage and is designed to understand student attendance behavior and engagement patterns.

The analysis covers:

* Students consistently attending
* Students gradually reducing attendance
* Students attending only certain classes
* Weekday versus weekend attendance
* Class timing patterns
* Attendance before and after holidays
* Attendance and course completion relationship
* Available learning and engagement signals
* Attendance data availability and tracking gaps

The analysis is designed to help CDAX understand attendance behavior, identify potential engagement issues, and support decisions related to class scheduling and student engagement.

Where student-level attendance records, class dates, class timings, holiday information, or attendance-linked completion data are not available or fully verified, the corresponding analysis has been documented as Not Calculable rather than using estimated values.

## Certificate & Completion Analysis

The certificate and completion analysis is designed to understand what happens between enrollment and certification.

The analysis follows the journey:

Enrollment → Learning → Assessment → Project → Completion → Certificate

The analysis covers:

* Certification rate
* Time to certification
* Course-wise certification
* Students who complete learning but do not obtain certificates
* Students who obtain certificates without completing expected activities, where applicable
* Completion rate
* Certification data availability
* Assessment and project data gaps
* Barriers between learning, completion, and certification

The analysis is based only on the available CDAX sample and backend data.

The current available data confirms:

* 3 enrolled students
* 1 student with observed learning activity based on watched content
* 0 students reached 100% course completion
* Course completion rate is 0%
* Actual certificate records are not available in the reviewed sample
* Assessment completion cannot be confirmed
* Project activity records are not available

The observed learning activity count should not be interpreted as learning completion. It represents a student with recorded learning activity such as watched content.

Because actual certificate records are unavailable, certification rate, time to certification, course-wise certification, learning-completed-without-certificate analysis, and certificate validation against expected activities cannot currently be calculated.

## Notification Effectiveness Analysis

The notification effectiveness analysis evaluates App, Email, SMS, and Push Notifications to understand their impact on student returns, class attendance, recording consumption, and project activity.

The analysis includes notification tracking, student behavior, effectiveness metrics, and data gaps. Where notification records are unavailable or unverified, the corresponding metrics are documented as Not Available or Not Calculable.


## Files

* `CDAX_Data_Dictionary.xlsx` — CDaX Data Dictionary
* `CDaX PowerBI Data.xlsx` — Excel data used to create the Power BI dashboard
* `CDAX.pbix` — Power BI dashboard
* `CDAX_KPI_Formula.xlsx` — KPI definitions and formulas
* `CDAX_Event_Tracking_Specification.xlsx` — CDaX event tracking specification
* `CDAX_Student_Funnel_Analysis.xlsx` — CDaX student funnel analysis
* `CDAX_Student_Lifecycle_Analysis.xlsx` — CDaX student lifecycle analysis from registration through renewal, switching, or exit
* `CDAX_Recording_Consumption_Analysis.xlsx` — CDaX recording consumption analysis
* `CDAX_Course_Switching_Analysis.xlsx` — CDaX course switching analysis
* `CDAX_Recommendation_Experimentation_Plan.xlsx` — CDaX recommendation and experimentation plan
* `CDAX_Student_Engagement_Model.xlsx` — CDaX student engagement scoring methodology
* `CDAX_Student_Value_Segmentation.xlsx` — CDaX student value segmentation analysis
* `CDAX_Management_Analytics.xlsx` — CDaX management analytics framework
* `CDAX_Data_Quality_Audit.xlsx` — CDaX data quality audit
* `CDAX_Revenue_Forecasting_Model.xlsx` — CDaX revenue forecasting model
* `CDAX_Course_Demand_Forecast.xlsx` — CDaX course demand forecasting model
* `CDAX_Attendance_Pattern_Analysis.xlsx` — CDaX attendance pattern analysis
* `CDAX_Certificate_Completion_Analysis.xlsx` — CDaX certificate and completion analysis
* `CDAX_Notification_Effectiveness_Analysis.xlsx — CDaX notification effectiveness analysis
