# CDaX-Data-Analytics

CDaX Data Analytics and Power BI Dashboard

## About

This repository contains the data analytics work prepared for the CDaX project.

The project focuses on student behavior, course performance, engagement, attendance, learning activity, business performance, data quality, and analytics requirements for the CDaX platform.

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

Notification preferences are available in the shared user data, but notification preferences alone do not confirm that notifications were sent, delivered, opened, or clicked. Notification effectiveness metrics have not been calculated because the required notification event records have not been verified.

The analysis distinguishes between confirmed sample data, unverified data, and data that is not available in the reviewed sources. Missing values are not treated as zero unless the data confirms a value of zero.

## Data Dictionary

The data dictionary contains the CDaX entities and their related fields, including data types, descriptions, required/optional status, example values, sources, and relationships.

It supports consistent interpretation of the backend data and helps map database entities to the analytics requirements.

## Power BI Dashboard

The Power BI dashboard was created using the prepared Excel data. It includes analysis of CDaX-related data, metrics, and trends.

The dashboard is designed to help understand available business and student learning data through visual reports.

## KPI Analysis

The KPI file contains KPI definitions, formulas, data sources, frequency, and business purpose.

The KPIs are intended to support consistent measurement of student engagement, course performance, conversions, attendance, learning progress, and business performance.

Where the required source data is unavailable, the relevant KPI is documented as a data gap or Not Calculable.

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

The specification covers pre-launch tracking requirements for:

* Registration
* Login
* Demo booking and attendance
* Course viewing and enrollment
* Class attendance
* Recording usage
* Project activity
* Assessment activity
* Subscription activity
* Course switching
* Certificate generation
* Support requests

The specification provides a consistent framework for capturing events required for reliable analytics.

Notification-related events such as notification sent, delivered, failed, opened, and clicked should also be tracked to support notification effectiveness measurement. Their implementation and availability in the backend have not yet been verified.

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

Actual experiment results should only be reported after the required events and outcomes have been collected.

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

Each signal is intended to contribute to an overall engagement score according to the defined scoring methodology. Students can then be categorized as:

Highly Engaged → Active → Declining → At Risk

The methodology is based on available backend data and is designed to help identify students who may need early support or intervention.

Where engagement signals are unavailable, the scoring and classification should not be treated as fully validated.

## Student Value Segmentation

The student value segmentation analysis identifies which types of students can create the most long-term value for CDaX.

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

**High Value:** Multiple courses, longer subscription, renewals, project activity, high completion, and higher revenue.

**Medium Value:** Moderate course usage, active learning, some completion/project activity, and limited repeat activity.

**Low Value:** Single course, low learning activity, low completion, and limited repeat activity.

**Insufficient Data:** Used when the required student-level backend information is unavailable or cannot be verified.

No revenue, renewal, subscription, project, switching, or support values have been invented where the required records were not verified.

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
* Missing or incomplete recording consumption data
* Incorrect or null project data
* Incorrect or null assessment data
* Frontend and backend data mismatch
* Tables and records that cannot be properly joined

The audit also documents identified data issues, data gaps, validation requirements, and the additional source data required for checks that cannot be fully validated.

Findings based on sample data are distinguished from issues that require further validation against production data.

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

Forecast outputs should be interpreted according to the assumptions and data limitations documented in the model.

## Course Demand Forecasting Model

The course demand forecasting model is designed to support analysis of course demand using available CDaX course and enrollment data.

It is intended to help identify:

* Courses with higher enrollment demand
* Course-wise enrollment patterns
* Changes in course interest
* Historical demand trends where timestamps are available
* Data requirements for future demand forecasting

Where historical enrollment data is insufficient, the available data should not be treated as a validated demand forecast.

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

The analysis is designed to help CDaX understand attendance behavior, identify potential engagement issues, and support decisions related to class scheduling and student engagement.

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

The analysis is based only on the available CDaX sample and backend data.

The reviewed sample indicates:

* 3 enrolled students in the available sample
* 1 student with observed learning activity based on watched content
* No students in the reviewed sample reached 100% course completion
* The reviewed sample's course completion rate is 0%
* Actual certificate records were not available in the reviewed sample
* Assessment completion could not be confirmed
* Project activity records were not available in the reviewed sample

The observed learning activity count should not be interpreted as learning completion. It represents a student with recorded learning activity such as watched content.

Because actual certificate records are unavailable in the reviewed sample, certification rate, time to certification, course-wise certification, learning-completed-without-certificate analysis, and certificate validation against expected activities cannot currently be calculated.

These findings apply to the reviewed sample and should not be interpreted as verified production-wide results.

## Notification Effectiveness Analysis

The notification effectiveness analysis is designed to determine whether CDaX notifications are associated with meaningful changes in student behavior.

The analysis considers four notification types:

* App
* Email
* SMS
* Push Notification

The analysis follows the journey:

Notification Sent → Delivered → Opened → Clicked → Student Returned → Class Attended → Recording Consumed → Project Activity

The workbook contains seven sheets:

1. **Notification Data:** Structure for recording notification IDs, student IDs, notification types, sent timestamps, delivery status, open timestamps, click timestamps, source systems, and notes.
2. **Student Return Analysis:** Structure for checking whether students return to the application within 24 hours of a notification.
3. **Attendance Impact:** Structure for checking whether students attend classes within seven days of a notification.
4. **Learning Activity Sample:** Available sample video progress and daily streak data, with notification attribution marked as unknown where it cannot be verified.
5. **Notification Preferences:** Available user notification settings, including notifications enabled, email notifications, push notifications, and analytics settings.
6. **Notification Effectiveness Summary:** Comparison of App, Email, SMS, and Push Notification metrics.
7. **Notification Data Gaps:** Documentation of missing notification events, delivery information, student return history, attendance records, and project activity.

The intended metrics include:

* Number of notifications sent
* Delivery rate
* Open rate
* Click rate
* Student return rate within 24 hours
* Attendance rate within seven days
* Recording activity rate within seven days
* Project activity rate within seven days

The shared user data contains notification preference fields. However, enabled preferences do not prove that notifications were sent, delivered, opened, or clicked.

Notification sent, delivered, opened, and clicked records have not been verified in the shared data. Student session history, attendance records, and notification-related event linkage also require verification.

Therefore, the notification effectiveness metrics are currently marked Not Available or Not Calculable where appropriate. These values have not been replaced with zero because the absence of verified records does not prove that no notifications or activities occurred.

The analysis is intended to support future notification performance measurement once the required notification events and linked student activity records are available.

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
* `CDAX_Notification_Effectiveness_Analysis.xlsx` — CDaX notification effectiveness analysis

## Data Limitations

The analytics outputs depend on the completeness and reliability of the available sample data and backend seed data.

Some analyses define the metrics, methodology, and required source data but cannot yet calculate verified results because the underlying records are missing or have not been confirmed.

Before using the results for production decisions, the relevant data should be validated against the complete backend records and application event logs.

The repository distinguishes documented analytical frameworks from metrics that can currently be calculated using the available data.
