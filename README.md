# Drug Discovery Program Analytics Dashboard

A comprehensive Power BI dashboard designed to monitor assay performance, compound activity, project timelines, and overall R&D progress across multiple drug discovery programs.
________________________________________
# 2. Short Description / Purpose 🗒️
The Drug Discovery Program Analytics Dashboard provides an end-to-end visualization of ongoing and completed R&D projects, allowing researchers, project managers, and decision-makers to track assay performance, compound activity (IC50/EC50), screening timelines, and resource allocation. The dashboard is built to centralize experimental data and accelerate insights for hit identification, lead validation, and program optimization.

 # 3. Data Source 💾
In-house experimental data representing multiple stages of early drug discovery workflows.
Data Includes:
•	# Project Tracker Table:
Tasks, assay names, start/end dates, durations, resource assignment (ABS, PM, Client, In Vivo), and project status.
•	Compound Screening Table:
Compound IDs, IC50 values, activity %, concentrations, assay dates, and project associations.
•	Lead Identification Table:
Lead IDs, EC50, %Activity, assay target (e.g., PXR transactivation), and compound linkage.
•	Program-Level Compound Table:
Detailed entries for each compound screened in each program, including EC50/Activity across timeline.
•	Calendar Table:
Continuous date dimension for time intelligence functions (YTD, QTD, monthly trends).

# 4. Features / Highlights
 ## Business Problem 🌐
Key decision-making questions such as:
•	Which projects are delayed or ahead of schedule?
•	Which compounds show the strongest activity or lowest IC50/EC50 values?
•	Which assays produce the highest-quality leads?
•	How resources (ABS/PM/Client/In Vivo) are distributed across tasks?
________________________________________
# Goal of the Dashboard 🎯
To deliver an analytical and interactive Power BI dashboard that:
•	Tracks R&D projects from preliminary screening to compound shipment and lead optimization
•	Highlights high-performing compounds based on potency and activity thresholds
•	Monitors project durations, task completion, and resource allocation
•	Supports data-driven decisions for program prioritization and hit-to-lead advancement

________________________________________
# Visuals of the dashboard 📊
## Project Timeline gannt chart
Displays:
•	Start and end dates of each project
•	Stages such as preliminary screening, rescreening, validation, compound shipment, and lead optimization
•	Duration (days) for each task
•	Resource type (ABS, PM, Client, In Vivo)
Helps identify project bottlenecks and overlapping workloads.
_______________________________________
 ## Activity vs. Concentration Plot (area chart)
Shows the relationship between activity % and concentration, helping identify dose-response trends.
________________________________________

 ## Lead & compound Identification slicer
Interactive slicer showing:
•	Lead IDs
•	compound ID
•	%Activity
Helps teams track validated leads in each program.
________________________________________
 ## Date Slicer & Calendar Intelligence
Users can slice the entire dashboard by:
•	Year
•	Quarter
•	Month
•	Date range
Enabling time-based analysis of project progression and assay throughput.
