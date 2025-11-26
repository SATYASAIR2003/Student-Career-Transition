# Student-Career-Transition
Student Career Transition Dashboard
# Project Overview

The Student Career Transition Dashboard is an interactive Power BI project that analyzes how students transition from core engineering fields to software and other domains.
It provides insights into CGPA, placement trends, internships, domain shifts, and challenges faced by students across different states and college types.

# Objectives

Analyze career transition trends among students from core to software domains.
Identify key reasons and challenges influencing student career decisions.
Visualize state-wise, gender-wise, and department-wise distribution of placements and internships.
Build a data model using Star Schema for structured analytics.

# Dashboard Features

KPIs: Average CGPA, Placement %, Department Average, Average Salary

Slicers: College Type, Gender

Visuals:

Internship % by Gender (Pie Chart)
Department count by College Type (Bar Chart)
Domain distribution by College Type (Donut Chart)
Category count by State (Tree Map)
Masters % by State (Line Chart)
Internship % by State (Bar Chart)

# Data Model (Star Schema)

Fact Table:
Fac_career_shift (CGPA, Placement, Internship, Domain_ID, Department_ID, etc.)

Dimension Tables:
Dim_student – Student info (Name, Gender, State)
Dim_department – Department & placement data
Dim_domain – Domain & required skills
Dim_platform – Platform details
Dim_reason – Reasons for domain shift
Dim_challenge – Challenges faced

# Tools & Technologies

Power BI – Data visualization & dashboard design
Excel / CSV – Data preparation
Data Modeling – Star Schema structure
DAX Measures – For calculating KPIs and insights
