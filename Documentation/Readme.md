**Betway Enterprise Analytics Dashboard**

**Project Overview**

The Betway Enterprise Analytics Dashboard is a comprehensive Power BI solution designed to provide executives and commercial stakeholders with actionable insights into sportsbook performance. The dashboard consolidates betting activity, customer behaviour, revenue performance, and operational KPIs into an interactive analytics platform that supports strategic and data-driven decision-making.

The solution applies enterprise Business Intelligence principles, including dimensional modelling, advanced DAX, Row-Level Security (RLS), drill-through analysis, KPI scorecards, and interactive reporting to transform transactional betting data into meaningful business insights.

**Business Problem**

Sports betting operators generate millions of transactions across customers, sports, betting channels, and geographic regions without a centralized analytics solution and the stakeholders face challenges such as:
•	Limited visibility into betting performance.
•	Difficulty identifying high-performing sports and regions.
•	Lack of customer behaviour insights.
•	Slow manual reporting processes.
•	Inconsistent KPI reporting.
•	Limited executive visibility into commercial performance.

**Purpose**

The purpose of this project was to build a scalable analytics platform that enables decision-makers to monitor performance in real time and identify growth opportunities.

**Business Objectives**

The dashboard enables stakeholders to:

•	Monitor sportsbook revenue performance.

•	Analyse betting activity across sports.

•	Understand customer betting behaviour.

•	Evaluate provincial performance.

•	Measure customer engagement.

•	Track operational KPIs.

•	Support commercial decision-making.

•	Improve reporting efficiency through automation.

•	Target Audience.

**Stakeholders**

•	Executive Management.

•	Commercial Managers.

•	Regional Managers.

•	Marketing Teams.

•	Customer Insights Teams.

•	Business Intelligence Analysts.

•	Operations Managers

**Technology Stack**

Technology				      (Purpose)

Power BI Desktop				(Dashboard Development)

Power Query				      (Data Transformation)

DAX					            (Business Calculations)

SQL					  					(Data Preparation)

Star Schema				      (Data Modelling)

Row-Level Security			(Secure Reporting)

GitHub					        (Portfolio)

**Data Model**

The solution follows a Star Schema.

**Fact Table**
**Fact_Bets**
Contains betting transactions including:

•	Bet ID

•	Customer ID

•	Sport ID

•	Province ID

•	Date

•	Stake Amount

•	Revenue

•	Odds

•	Bet Status

**Dimension Tables**

•	Dim_Date

•	Dim_Customer

•	Dim_Sport

•	Dim_Province

•	Dim_Channel

•	Dim_VIP

•	Security Table (RLS)

**Dashboard Features**

**Executive Summary**

Provides a high-level overview of sportsbook performance through interactive KPI scorecards.

**KPIs include:**

•	Active Customers
•	Total Bets
•	Total Stake
•	Average Stake
•	Total Revenue
•	Revenue per Bet
•	Average Odds
•	Win Rate

**Commercial Analysis**

**Provides insights into:**

•	Revenue by Sport
•	Revenue by Province
•	Revenue Trends
•	Customer Segmentation
•	VIP Analysis
•	Betting Activity
•	Drill-through Analysis

Interactive drill-through enables users to move from executive KPIs to detailed sport-level analysis.

**Features include:**

•	Dynamic page titles
•	Back navigation
•	Executive insights
•	Detailed trend analysis

**Security**

Implemented Dynamic Row-Level Security (RLS) using:

USERPRINCIPALNAME()
Security mapping table
Province-based access control
Key Performance Indicators
KPI					Description
Active Customers			Number of unique customers placing bets
Total Bets				Total number of bets placed
Total Stake				Total value wagered by customers
Average Stake			Average value wagered per bet
Total Revenue			Revenue retained after settled bets
Revenue per Bet			Average revenue generated per bet
Average Odds			Average betting odds selected
Win Rate				Revenue retained as a percentage of Total Stake

**Business Insights**

**The dashboard enables stakeholders to identify:**

•	High-performing sports.
•	Underperforming regions.
•	Customer betting trends.
•	Revenue growth opportunities.
•	Changes in betting behaviour.
•	High-value customer segments.
•	Regional betting performance.
•	Commercial performance trends.

**Business Value**

**The solution delivers value by:**

•	Automating executive reporting.
•	Improving decision-making through real-time analytics.
•	Enhancing visibility into sportsbook performance.
•	Supporting customer behaviour analysis.
•	Reducing manual reporting effort.
•	Enabling secure self-service analytics.
•	Providing actionable commercial insights.

**Skills Demonstrated**

This project showcases proficiency in:
•	Business Intelligence
•	Power BI
•	Power Query
•	DAX
•	SQL
•	Data Modelling
•	Star Schema Design
•	Data Visualisation
•	KPI Development
•	Commercial Analytics
•	Executive Reporting
•	Row-Level Security
•	Drill-through Reporting

**Performance Optimisation**

**Project Outcome**

The Betway Enterprise Analytics Dashboard demonstrates how enterprise Business Intelligence can transform sportsbook transaction data into meaningful commercial insights. By combining advanced analytics, interactive reporting, and secure access controls, the solution enables stakeholders to monitor performance, understand customer behaviour, and make informed business decisions.
