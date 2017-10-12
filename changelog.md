# Changelog

A breakdown of all new EDIS features, upgrades, and bug fixes by version.

|Version|Release Date|
|---|---|
|[2.12.2](#v2_12_2)|2017-09-29|
|[2.12.1](#v2_12_1)|2017-09-22|
|[2.12](#v2_12)|2017-09-02|
|[2.11](#v2_11)|2017-05-12|
|[2.10](#v2_10)|2017-04-25|
|[2.9](#v2_9)|2017-02-28|
|[2.8](#v2_8)|2017-02-07|
|[2.7](#v2_7)|2017-01-12|
|[2.6](#v2_6)|2016-11-11|
|[2.5](#v2_5)|2016-10-19|
|[2.4](#v2_4)|2016-09-09|
|[2.3](#v2_3)|2016-06-29|
|[2.2](#v2_2)|2016-05-06|
|[2.1](#v2_1)|2016-03-25|
|[2.0](#v2_0)|2016-03-12|
|[1.10](#v1_10)|2016-01-28|
|[1.9](#v1_9)|2015-11-12|
|[1.8](#v1_8)|2015-09-04|
|[1.7](#v1_7)|2015-05-08|
|[1.6](#v1_6)|2015-03-06|
|[1.5](#v1_5)|2014-10-16|
|[1.4](#v1_4)|2014-01-10|
|[1.3](#v1_3)|2013-12-30|
|[1.2](#v1_2)|2013-11-14|
|[1.1](#v1_1)|2013-10-15|
|[1.0](#v1_0)|2013-08-30|

## 2.12.2 - 2017-09-29 <a name="v2_12_2"></a>
- Added ability to record comments in custom assessment scores and push them to student logs.
- Removed legacy custom assessment reports.
- Added search bar and filter popup to forms landing page.
- Bug fixes and generic improvements from 2.12.1.

## 2.12.1 - 2017-09-22 <a name="v2_12_1"></a>
- Added "Save as" and "Copy" options to interventions, templates, and blueprints.
- Added "Title" field to intervention evaluations.
- Added “Sharing” to forms and form entries.
- Upgraded Custom Assessment subjects to use EDISSubjects.
- Sync of weekly STAR Data.
- Made reports created by “Anyone” the default in listings.
- Bug fixes and generic improvements from 2.12.

## 2.12 - 2017-09-02 <a name="v2_12"></a>
- New Custom Reports landing page with search, filter, and cleaner UI.
- New naming convention clue for interventions and intervention templates.
- New intervention tab for evaluations/fidelity tracking.
- New intervention tab for logging sessions with individual student attendance.
- New intervention tab for logging intervention changes for groups or individual students.
- More flexible time units to deal with intervention duration.
- New "Time" and "User" form fields.
- Improved "Behavior" tab in student profile with historical graphics.
- Improved design for "Home" tab in student profile.
- New Custom Assessments landing page with search, filter, and cleaner UI.
- Improved Custom Assessments details with comparisons between filter, my students, and the universe.
- Improved Custom Assessment trial drawers with comparisons and embedded student listings.
- Added labels in Custom Assessment charts.
- Improved login workflow for Test-taking UI.
- Extended new sharing capabilities to new entities.
- New Standards Analysis report for standards and domains with comparisons between filter, my students, and the universe.

## 2.11 - 2017-05-12 <a name="v2_11"></a>
- Added dynamic student listings to test event analytics
- Added intervention status/effectivess to custom reports
- Included dependencies logic when editting custom assessments
- Added "About" tab to test event UI
- Added new "Publish" feature to calculate test event analytics
- Improved design of Standards-Based Results Analytics
- Improved test response processing workflow in backend
- Improved layout of "Assessments" nav-bar menu
- Added warning to notify users of new scores availble after publishing test events
- Upgraded to Font Awesome 4.7

## 2.10 - 2017-04-25 <a name="v2_10"></a>
- Added initial push for intergration between forms and data warehouse
- Initial push for standards-based report analytics
- Initial push for percentage calculations in forms
- Improved design of graduation report to embed early warning codes
- Initial push for new test event analytics report
- New global login feature (still in alpha mode)

## 2.9 - 2017-02-28 <a name="v2_9"></a>
- Added async intervention re-calculation for improved UX
- Improved intervention calculation algorithm to add more weight to trends
- Improved test-taking login UX
- Added better browser accident recovery handling when test-taking
- Improved test events UI with support for student search
- Improved error handling for widgets in data dashboard

## 2.8 - 2017-02-07 <a name="v2_8"></a>
- Added test booklets, answer keys, and bubble sheets to testing engine
- Added copy/create-from functionality to blueprints, templates, interventions
- Added RTI glossary of terms
- Improved UX for listings of RTI entities
- Added new layout for detailed views of RTI entities
- Added new RTI chart
- Added new intervention form entity
- Added pause/resume test event functionality

## 2.7 - 2017-01-12 <a name="v2_7"></a>
- Added filter by progress/effectiveness in RTI dashboards
- Improved formatting of calculation, date, and other form fields
- Added new Student form field
- Initial push for RTI V2 with support for blueprints, templates, and interventions
- Initial push for new Content API to house intervention blueprints
- Improved design for WYSIWYG editor in item bank
- Improved test item copying with support for copy everything vs copy info
- Added new read-only and signature fields to forms
- Improved validation UX for item/test editor
- Improved rules for deleting items/tests/events

## 2.6 - 2016-11-11 <a name="v2_6"></a>
- New forms management tool
- Added a new "Tools" nav-bar menu
- Improved "Test Results" UI
- Added ordinal positions to custom assessment trials
- Optimized loading of async app filter in js code

## 2.5 - 2016-10-19 <a name="v2_5"></a>
- Added classroom alerts into the Flipped Data pipeline
- Added Notes to custom assessment trials
- Added tracking beacon / campaigns to Flipped Data emails
- Improved SFTP csv connectors
- Added transactional email api
- Improved student image pipeline

## 2.4 - 2016-09-09 <a name="v2_4"></a>
- Added fixed-to-top nav-bar
- Added highest, lowest, first, last columns to test results
- Improved test events UI
- New "Question Map" feature in live testing UI
- New floating Prev/Next buttons in live testing UI
- Improved live testing welcoming worflow
- Added "item bank sharing" purpose to user teams
- Refactored multiple logins feature
- Enhancements to item bank filters
- New classroom alerts

## 2.3 - 2016-06-29 <a name="v2_3"></a>
- Custom MTDA cell sizes
- Added "pausing" to live testing interface
- Added "impersonate user" option for system admins
- Next-gen app filter with multi-selects and async student queries
- Next-gen EdFabric Data Points

## 2.2 - 2016-05-06 <a name="v2_2"></a>
- Optimized item bank search
- Added Trial Description to Custom Assessment Widgets and Tables
- Removed icons from menus and other UI elements
- New design for create/edit test event
- Enhancements to Live Testing UI
- Added Depth of Knowledge to Test Blueprints

## 2.1 - 2016-03-25 <a name="v2_1"></a>
- Default Post on student logs
- Student log Q/A
- Refactoring of attendance ingestion data
- New attendance widgets
- MTDA with fixed cols and headers
- Automated assessment ingestion workflow
- Improved assets folder structure and code
- Refactoring of Base / ApiBase controllers
- Async/cached client stats on login page
- Refactoring of paging code
- Improved login workflow
- Improved UserType / UserGroup management

## 2.0 - 2016-03-12 <a name="v2_0"></a>
- Refactor of data access connection strings for the EDIS API
- Add graduation credits summary for middle school students
- New log feature with social entities API
- Upgraded expandable listings
- Create smart pivot table functionality to handle large x-axis tables
- New student image proportions
- New nav-bar to support new EDIS 2.0 branding
- Improve ingestion of attendance entities
- Remove floating options, replace with scroll-to-top
- New set of favicons
- Improved operator handling of KPIs/KPAs
- Improved custom assessments section in student profile to support advanced widgets
- Improve dashboard widget tooltips to support non-related vs related series
- Improved custom assessment interfaces and workflow
- Initial push for new website
- Remove print to word, pdf, printing except for entities
- New MTDA datable concept that supports freezing of columns, headers, footers
- Advanced Widgets for Assessments, Trials, and Group Analysis
- Enhance Report Library
- Improved QTI Items Importer
- Upgrade Font Awesome Icons

## 1.10 - 2016-01-28 <a name="v1_10"></a>
- Add KPIs to student profile section
- Customization of intervention sections to support added security, printing, and family access
- Project added for QTI item ingestion
- Added support for mid-tem and semester exam grades to Course grades
- Email notifications functions in operator
- New brand-neutral app tour
- Added reading level to MTDA item library for STAR
- New brand-neutral app tour
- Flipped data message design conforming with EDIS brand design
- Move ESE codes to Especial education codes
- Bring new intervention UI preferences for family access in student profile
- Enhanced login access for families with tooltips
- Added lexile scores to NWEA MAP Results
- New notification settings for Flipped Data added to user settings

## 1.9 - 2015-11-12 <a name="v1_9"></a>
- Added support for factor in RTI PM Charts and Tables
- Added factor support for defining when a score meets target
- Add support for factor in MTDA
- Refactoring of notifications
- Add ability to flip assessment context based on factor
- Added ability to use final date in interventions with no PMP
- Add factor (+/-) to assessments
- change custom assessment process and rti wizard to support inverted scales
- add support for inverted interventions
- Added support for custom client logos in Flipped Data
- New favicons
- Branding capabilities for client name, logo, flipped data, etc.
- Email insights settings in user settings section
- Added LEP level to student entity
- Added support for factor to RTI verbose analysis
- Extended effectiveness and progress status to be push instead of pull
- Wire-up standards-based grading to student profile
- VAM updates
- New family login merged into EDIS
- New family message async control
- Add Agnostic project to showcase HTML, CSS, and JSON Api
- New flip data css
- New top nav-bar design for families
- Upgrade to latest Font Awesome version
- New student dashboard for families
- Cleaned-up student profile for families
- Added factor to % meeting target in MTDA
- Real-time language translations into notifications
- Enhanced locatization to student profile
- Added data source types to support multiple sources in interventions (KPIS, Assessments, Customs, etc)
- External employee directory open in public API
- Fixed trend-line out-of-bound issue
- Dev API branding improvements
- Added ability to export VAM season rosters to Excel
 
## 1.8 - 2015-09-04 <a name="v1_8"></a>
- Improved logic to deploy KPIs and alerts into clients
- Addded support for multiple areas of concern in RTI
- Owin-based Sso logic separated into standalone project
- Testing Engine - Assessment Creator/Editor
- New concordant scores legend for ACT, SAT, PERT scores
- Testing Engine - QTI Item Editor
- Data structure optimization for daily KPIs
- Added levels EOC History and Civis
- Added support for KPIs in MTDA library
- Testing Engine - Async full-text search for QTI item bank
- Added new executive summary reports for all EOCs
- Browser searches and listings optimizations
- New widget to support tabular info
- Added ESE, ELL, and 504 tags to student v-card
- Normalization and new format for test scores tables
- Enhancements to VAM process
- Improvements to operator for email notification and flip-data model creation for KPIs and alerts
- Email insights template concept
- Tagging system bridge between KPIs, alerts and PD pins
 -Added factor to KPIs
- Pinterest flip-data bridge
- Improved release logic to update student profile items in all clients
- Improved design of Enrollment section of the student profile
- Improved login and sign up pages
- New student profile layout
- Wired intervention re-calculation triggers
- Testing Engine - Test taking authentication flow
- Ability to fetch widgets to Agnostic apps
- Enhanced calculation of intervention status and effectiveness
- Added ability to filter FCAT reports by test administration
- Added test administration filter to i-Ready executive summaries
- Add ability to support new SSO in Web API
- Upgraded from highcharts to highstocks to support historical KPI widgets
- New admin section to update school year terms
- Added ability to serve KPI data via JSON api
- Improved email design for Flipped Data
- Added ability to sort by intervention status and efffectiveness in intervention dashboard
- Add new intervention section for KPIs
- Upgrading design of intervention log
- Added ability to fetch minimal css for third-party apps
- Added ability to show historical KPI data in interventions
- Wired-up new intervention status and effectiveness into the RTI UI
- Enhanced intervention status / effectiveness re-calculation
- Added support for KPIs in RTI baselines
- Added teacher performance filters
- Added support for KPIs in RTI progress-monitoring
- Added AOCs to intervention bank
- Added support for auto-links in intervention log
- Added new KPIs widgets
- Add exporting capabilities to KPI report
 
## 1.7 - 2015-05-08 <a name="v1_7"></a>
- Added support for USATestPrep scores.
- New structure to represent information within student profile.
- Added support for graduation credits summary within student profile.
- New report information section in student profile
- Refreshed design of trees and drawers to improve legibility.
- Added support for trimester grades.
- New color-coding for ACT, PERT, and SAT reports.
- Added new settings section for RTI areas of concern, skill areas, and sub-skills.
- Refreshed login page with links to client websites.
- New flow for handling errors, unauthorized requests, and 404s.
- Bug fixes and other improvements from 1.7. bug
- Improved performance of RTI security checks.
- Performance improvements to dashboard and report library.
- New data points on Graduation report.
- Supplemental report information
- Improve performance of Attendance reports.
- New assessment creation interface
- Ability to copy custom assessments.
- Home page now goes straight to log in.
- Intervention log redesign
- Upload files to interventions
- Refresh student profile
- Cosmetic updates to the intervention details page
- Upgraded charts in Family module
- General bug fixes bug
- New Learning Profiles
- Tree selector for educational standards.
- Pretty urls for EDIS sites
 
## 1.6 - 2015-03-06 <a name="v1_6"></a>
- User interface received a major redesign.
- We now allow for creating multiple individual interventions at once.
- Much more widgets in data dashboard
- MTDA becomes Custom Reports
- Profile Pics
- We added the ability to copy custom reports.
- Custom Reports can now be created from the report library.
- Better student listings options
- Profile Pic upload
- Unified Group options
- The Student Profile gets a facelift.
- Group and Team management screens now have a cleaner design
- “Featured Reports” category has been eliminated.
- New listing stats
- Redesigned users listings now display the user image and the employee title.
- Teacher Id tooltip
- New Intervention References.
- Custom Reports get a facelift.
- Enhanced Page titles, descriptions, and tags
- Users can now select multiple advanced filter options at the same time.
- New Migrant/Not Migrant option has been added to the advanced filter.
- Create interventions with no PMP
- Dashboard grew to more than 1000 widgets. Will keep growing...
- Top navigation bar is blue now.
- Page actions are now centralized in the top bar and have bigger icons.
- Floating Menu
- New Student V-Cards show negative/positive/neutral KPIs
- Schools and Districts also get V-Cards
- New report library27, 2016
- Brand-new RTI Wizard
- New format for intervention names when multiple individual interventions are generated.
- You can copy and paste URLs into the intervention log.
- Updated App Tour.
- New Admin Settings page
- New “Center Program” advanced filter.
- New functions to deal with proper casing during ingestion.
- Faster loading of assessment trials.
- Attendance Reports run faster.
- School and District websites are now linked from the student profile.
- URL routes are now in lower caps.016
- New App Modules structure, 2016
- New Demo Request form.
- We introduced the concept of “Smart References”.
- Improved Usage Analytics in for software administrators.
- A time-stamp has been added to file exports.
- Archived Interventions can now be copied.
- Added support for signed letter grades like: A+, B-, etc...
- EDIS has a new logo and new icons for iOS, Android, Microsoft, and Chrome web apps.
- We made it easier to add and remove students and members for teams and groups respectively.
- Improved design for intervention details.
- Listings of students have been re-redesigned
 
## 1.5 - 2014-10-16 <a name="v1_5"></a>
- Embeddded Google Analytics
- New Fountas & Pinell report
- New Pals2 report
- Logged in users will go to the dashboard when clicking on the EDIS icon.
- Improved MTDA library
- New Tier 1 form
- Intervention dashboard has been enhanced
- New support for reference areas in RTI
- Major data dashboard update
- EdFabric multi-lingual capabilities have been added to EDIS School. (BETA)
- Sharing capabilities is now available for student groups.
- Workflow for adding students to a group has been improved.
- Enhanced widget descriptions
- Dashboard widget performance has been improved.
- Enhanced charts exporting features
- Introduction of warmer color palette
- New KPIs Summary Widget.
- New font-icons
- Improved page headers with cleaner design.
- Redesigned filter stats, legend tags and action controls
- 2 new Truancy KPIs: Truancy Candidate; Reportable for Truancy.
- More KPIs
- New Civics EOC Report.
- New ACT Plan and Explore Reports.
- Enhanced EOC Reports with new subcategories information.
- Enhanced Algebra One Exam by Year with Categories information.
- Improved Performance Indicators Executive report with supplementary charts.
- Enhanced Student Profile with new ACT Plan and Scores information.
- Updated trend line algorithm
- Improved Intervention Wizard guide
- The intervention form left navigation bar has been improved
- Enhanced Interventions Assessment selection with “All Custom Assessments” option.
- The widget library categories have been re-organized for better usage.
- Improved On-Track minimum controls
- Improved "No Data" templates
- Improved student profile with new categories layout
- Course Grades report
- OAuth 2.0 has been implemented
- Improved Admin User Mapping
- Enhanced MTDA report
- Improved infographics in time-based dashboard widgets.
- Smarter "Trending To" feature
- Faster standards library
- New flexible educational standards
- Improved drawer reports
- Cleaner RTI progress Monitoring charts
- A new intervention progress semantic engine
- New footer summaries
- New RTI naming conventions
- Added secure support for external users
- Improved application search page
- Large search box
- The Withdrawn Students report contains new data points.
- More options when adding dates to an intervention
- Improved security in Reports, MTDA Reports, RTI and Custom Assessments.
- Schedule filter now allows filtering by school type.
- Schedule filter eliminates duplicate courses and periods.
- Dramatically-improved filter performance.
- New report icons.
- New sharing interface
- Creating interventions now support adding groups of students.
- Fonts and buttons have been re-styled for readability purposes.
- Enhanced Top Navigation design
- Enhanced User Interface
- Advanced Filters are more descriptive
- Enhanced Admin User Mapping
- Improved Intervention Progress Monitoring Chart with better trend line
- Improved i-Ready Reports and i-Ready Executive Summary reports
- Group on-track min calculation change
- “RTI” tab has been renamed to “Intervention”.
- Improved sharing in MTDA Reports and Custom Assessments
- MTDA Reports and Custom Assessments now have a new interface for managing sharing.
- Non-custom Assessments in RTI PM
- “Secondary Type” option
- Responsive rounded images bug
- New option added for Power users to view all assessments and MTDA reports.
- Smarter intervention creation from listings
- Application filter stats
- Timeframe defaults in reports
- Changing targets trigger expected scores calculation
- Anonymous intervention printing
- Calculate expected scores automatically
- Redesigned report library
- Search tool redesign
- Added ability to also edit the Progress Monitoring Plan
- The intervention log has been redesigned
- New Security Roles feature
- Support for large data-sets in exporting
- Page Options have been redesigned
- Performance fine-tuning in some listings, menus, and graphics.
- Enhanced typography
- Related interventions
- New Health section added to student profile.
- View/edit scores in intervention details
- Design facelift to intervention bank.
- New trend line in RTI Progress monitoring charts.
- New CELLA report is available in the report library.
- Option to enter scores when selecting baselines
- CELLA Scores
- Wizard steps reduced from 6 down to 4
- Headers in MTDA Report can now scroll horizontally.
- Autogenerate intervention names
- Redesigned intervention details
- Document inteventions when deactivating
- Ability to override intervention name
- EDIT expected scores in interventions
- Merge intervention type selectors
- Design revamp to Executive KPIs Report
- Design revamp to behavior referrals
- New flatter design
- New skill area and intervention standard selections
- Intervention tips
- New gray colors in charts
- Merge app and page filters
- More operations from intervention details page
- An option to link to the Intervention Guide section 2016
- New Enrollment Widget.
- AP Test has now been added to the College & Career section of the student profile.
- Comparison card in intervention creation
- New landing page for creating interventions

## 1.4 - 2014-01-10 <a name="v1_4"></a>
- Ability to provide hints to specific help sections inside the software
- Ability to add/remove students from interventions
- Ability to add/remove progress monitoring dates for interventions
- Improved Intervention Log
- Creation of Help Center
- Redesign of RTI Dashboard
- Ability to copy an intervention
- Anonymous Intervention Bank feature
- Ability to log intervention session hours
- Redesigned Intervention Details view
- Filtering ability for assessments in RTI Progress Monitoring
- Supplemental student information in RTI Progress Monitoring
- New Intervention Effectiveness Measure

## 1.3 - 2013-12-30 <a name="v1_3"></a>
- Executive Reports
- Enrollment/Withdrawn Reports
- New Enrollment Withdrawn section in Student Profile
- New Behavior, Attendance, Withdrawn widgets in Data Dashboard
- Assessment Targets added to MTDA table headers
- Ability to add targets and scales to non-custom assessments
- Ability to include non-custom assessments in the MTDA item library
- Enhanced Filtering in the MTDA Dashboard
- MTDA Items Library is now search-able
- Ability to include performance indicators in MTDA Reports
- Enhanced RTI Printing feature
- New data points in RTI PM charts
- Rounded Faces for Student Images
- Student V-Cards

## 1.2 - 2013-11-14 <a name="v1_2"></a>
- WSAS Reports
- STAR Reports
- iReady Reports
- Retained Student Reports
- FCAT Subcategory Reports
- FAA Reports
- PALS Reports (First Graders, 4K, 5K)
- Improved Filtering in Assessments Dashboard
- New Custom Assessments in Student Profile
- New Industry certifications section in Student Profile
- Sharing assessments and reports by role
- Enhanced RTI progress monitoring charts
- Ability to export to Excel, Word, PDF
- Highlighting on Filter Legend
- New progress monitoring charts in MTDA
- Ability to link to include URLs as supplemental information for MTDA Reports
- Advanced Filter Grouping and Color Coding
- Improved Assessment Selection for RTI allows to pull from non-custom assessments

## 1.1 - 2013-10-15 <a name="v1_1"></a>
- Notification Center available to all users
- Ability to search for students, interventions, reports, and assessments
- Ability to lock and unlock assessment trials
- New Performance Indicators Report
- New feature to predefine intervention names by district to increase naming consistency
- New college and career section in student profile
- New Interventions section in Student Profile

## 1.0 - 2013-08-30 <a name="v1_0"></a>
- Initial release of EDIS
