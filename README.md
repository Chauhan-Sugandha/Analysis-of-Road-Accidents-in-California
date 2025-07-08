# Analysis-of-Road-Accidents-in-California

## Project Area: Data Engineering & Data Analytics - Traffic Safety Research and Accident Pattern Analysis

_________________________________________________________________________________________________________________________________________________________________________
## Project Overview:
This comprehensive data analytics project analyzes traffic accident patterns in California using the Statewide Integrated Traffic Records System (SWITRS) database. The project implements a complete data engineering pipeline from data ingestion to visualization, providing actionable insights for improving road safety across California's diverse transportation network.

California reports over 250,000 traffic collisions annually, with over 3,000 fatalities each year. This analysis aims to identify critical patterns, risk factors, and trends that can inform policy decisions and safety interventions to reduce accident severity and frequency.

_________________________________________________________________________________________________________________________________________________________________________
## Objective:
Primary Goal: Analyze road accident data to identify patterns, risk factors, and trends that can inform effective safety measures
Safety Enhancement: Reduce accident severity and improve overall road safety in California
Policy Support: Provide data-driven insights for policymakers, law enforcement, and transportation authorities
Risk Factor Analysis: Investigate how weather conditions, time of day, driver behavior, and road conditions impact accident occurrence and severity
Prevention Strategies: Develop evidence-based recommendations for accident prevention and safety improvements

_________________________________________________________________________________________________________________________________________________________________________

## Dataset:  California Highway Patrol SWITRS

_________________________________________________________________________________________________________________________________________________________________________
## Tools and Technologies Used:

### Cloud Infrastructure & Data Engineering
Amazon Web Services (AWS): Complete cloud solution stack
Amazon S3: Data lake storage for raw and processed data
Amazon Redshift: Data warehouse for analytics and reporting
AWS Glue: ETL (Extract, Transform, Load) pipeline automation
AWS Crawler: Automated data catalog and schema discovery
VPC Endpoints: Secure network connectivity

### Database Technologies
PostgreSQL: Relational database for structured data storage
Amazon RDS: Managed database service integration
MongoDB: NoSQL database for flexible data handling

### Data Processing & Analytics
Python: Primary programming language for data analysis
Pandas: Data manipulation and analysis
AWS Glue ETL: Data cleaning and transformation
Excel: Data preprocessing and cleaning

### Data Visualization
Amazon Redshift Charts: Cloud-based data visualization
MongoDB Charts: Interactive dashboard creation
Statistical Analysis: Pattern recognition and trend analysis

### Development & Collaboration
GitHub: Version control and code repository
Jira Kanban: Project management and task tracking
Pair Programming: Agile development methodology
Zoom: Team collaboration and meetings
Google Docs/Sheets: Documentation and collaborative editing

### Data Engineering Pipeline

Local PostgreSQL → AWS RDS → AWS Glue → S3 Data Lake → Redshift Data Warehouse
Data Ingestion: Automated extraction from SWITRS database.
ETL Processing: Data cleaning, transformation, and validation.
Data Warehousing: Structured storage in Amazon Redshift.
Real-time Processing: Continuous data pipeline monitoring.

_________________________________________________________________________________________________________________________________________________________________________

## Key Insights:
### Traffic Pattern Discoveries
Peak Accident Hours: Highest accident rates occur during 5-6 PM (rush hour traffic)
Weather Paradox: Clear weather conditions show predominant accident occurrence, indicating factors beyond weather contribute significantly to collision severity
Movement Patterns: Over 50% of fatal accidents occur while vehicles are proceeding straight, with left turns and running off road as next significant factors

### Technology and Safety
Cell Phone Impact: Significant correlation between cell phone usage (especially maps/navigation) and accident occurrence
Distracted Driving: Multiple forms of device usage (searching, chatting) contribute to accident risk
Safety Recommendations: Emphasis on hands-free operation and distraction prevention

### Demographic and Behavioral Insights
Age Factors: Specific age groups show higher involvement in fatal accidents
Gender Patterns: Analysis of victim and party demographics across accident types
Injury Severity: Detailed classification from property damage to fatal outcomes

### Infrastructure and Environmental Factors
Road Conditions: Impact of road surface conditions (dry, wet, slippery) on accident severity
Lighting Conditions: Relationship between lighting (daylight, street lights, darkness) and accident occurrence
Traffic Volume: Correlation between high-traffic areas and accident frequency.
_________________________________________________________________________________________________________________________________________________________________________

## Important Note
This code is not meant for direct execution without custom setup. It is intended to demonstrate data engineering and analysis capabilities for recruiters and reviewers.
This project is developed for academic purposes as part of the Master of Science in Data Analytics program at San Jose State University.
For questions about this project or collaboration opportunities, please refer to the GitHub repository or project blog linked above.
