# 🏅 Paris Olympics 2024 Power BI Dashboard

## 📊 Project Overview

An interactive Power BI dashboard providing comprehensive analytics and insights into Olympic Games performance data, featuring advanced DAX calculations and engaging visualizations.

<table>
<thead>
<tr>
<th>Component</th>
<th>Details</th>
<th>Technology</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Primary Tool</strong></td>
<td>Microsoft Power BI</td>
<td>Business Intelligence Platform</td>
</tr>
<tr>
<td><strong>File Format</strong></td>
<td>.pbix (Self-contained)</td>
<td>Embedded dataset included</td>
</tr>
<tr>
<td><strong>Visual Theme</strong></td>
<td>Olympic-themed design</td>
<td>Custom backgrounds and styling</td>
</tr>
<tr>
<td><strong>Data Architecture</strong></td>
<td>Star Schema</td>
<td>Fact and dimension tables</td>
</tr>
</tbody>
</table>

## 🗃️ Data Model Structure

<table>
<thead>
<tr>
<th>Table Type</th>
<th>Table Name</th>
<th>Purpose</th>
<th>Key Metrics</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Fact Table</strong></td>
<td>Fact</td>
<td>Core performance metrics</td>
<td>Medal counts, rankings, scores</td>
</tr>
<tr>
<td><strong>Dimension Tables</strong></td>
<td>Athletes</td>
<td>Athlete demographics</td>
<td>Name, nationality, gender</td>
</tr>
<tr>
<td><strong>Dimension Tables</strong></td>
<td>Coaches</td>
<td>Coaching information</td>
<td>Coach details, team associations</td>
</tr>
<tr>
<td><strong>Dimension Tables</strong></td>
<td>Medals</td>
<td>Medal achievements</td>
<td>Gold, Silver, Bronze allocations</td>
</tr>
<tr>
<td><strong>Dimension Tables</strong></td>
<td>Teams</td>
<td>Team information</td>
<td>Team names, countries, sports</td>
</tr>
<tr>
<td><strong>Dimension Tables</strong></td>
<td>Gender</td>
<td>Gender classification</td>
<td>Male/Female distribution</td>
</tr>
</tbody>
</table>

## 🏠 Dashboard Navigation Structure

<table>
<thead>
<tr>
<th>Page</th>
<th>Navigation</th>
<th>Primary Focus</th>
<th>Visual Components</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Home Page</strong></td>
<td>Entry Point</td>
<td>Dashboard Overview</td>
<td>Olympic theme, navigation buttons</td>
</tr>
<tr>
<td><strong>Athlete & Team Performance</strong></td>
<td>From Home Page</td>
<td>Individual & Team Analytics</td>
<td>Treemaps, Pie Charts, KPIs</td>
</tr>
<tr>
<td><strong>Medal & Country Insights</strong></td>
<td>From Home Page</td>
<td>Global Performance Analysis</td>
<td>Maps, Matrix, Trend Charts</td>
</tr>
</tbody>
</table>

## 🎯 Page 1: Home Dashboard

<table>
<thead>
<tr>
<th>Element</th>
<th>Type</th>
<th>Description</th>
<th>User Action</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Background</strong></td>
<td>Visual Design</td>
<td>Olympic-themed imagery</td>
<td>N/A - Decorative</td>
</tr>
<tr>
<td><strong>Navigation Button 1</strong></td>
<td>Interactive Control</td>
<td>"Athlete & Team Performance"</td>
<td>Click to navigate</td>
</tr>
<tr>
<td><strong>Navigation Button 2</strong></td>
<td>Interactive Control</td>
<td>"Medal & Country Insights"</td>
<td>Click to navigate</td>
</tr>
</tbody>
</table>

## 📈 Page 2: Athlete & Team Performance

### 🔍 Interactive Filters
<table>
<thead>
<tr>
<th>Filter</th>
<th>Type</th>
<th>Options</th>
<th>Functionality</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Athlete Nationality</strong></td>
<td>Multi-select Dropdown</td>
<td>All countries + blank option</td>
<td>Filter by one or multiple nationalities</td>
</tr>
<tr>
<td><strong>Sports/Discipline</strong></td>
<td>Selector</td>
<td>All Olympic sports</td>
<td>Filter by specific sports</td>
</tr>
<tr>
<td><strong>Rank Range</strong></td>
<td>Slider Control</td>
<td>1–86 (adjustable)</td>
<td>Filter athletes by ranking range</td>
</tr>
</tbody>
</table>

### 📊 Visualization Components
<table>
<thead>
<tr>
<th>Visual</th>
<th>Type</th>
<th>Data Displayed</th>
<th>Insight Provided</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Medals by Nationality</strong></td>
<td>Treemap</td>
<td>Total medals per country</td>
<td>Country performance comparison</td>
</tr>
<tr>
<td><strong>Gender Distribution</strong></td>
<td>Pie Chart</td>
<td>Male vs. Female percentages</td>
<td>Gender representation analysis</td>
</tr>
<tr>
<td><strong>Gold Medals by Team</strong></td>
<td>Donut Chart</td>
<td>Gold medal percentages by nationality</td>
<td>Top-performing countries in gold medals</td>
</tr>
</tbody>
</table>

### 🎯 Key Performance Indicators (KPIs)
<table>
<thead>
<tr>
<th>KPI</th>
<th>Metric</th>
<th>Calculation</th>
<th>Business Insight</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>National Diversity</strong></td>
<td>Total Athlete Nationalities</td>
<td>Count distinct countries</td>
<td>Global participation level</td>
</tr>
<tr>
<td><strong>Athlete Scale</strong></td>
<td>Total Athletes</td>
<td>Count all athletes</td>
<td>Overall competition size</td>
</tr>
<tr>
<td><strong>Sports Variety</strong></td>
<td>Number of Sports</td>
<td>Count distinct sports</td>
<td>Event diversity</td>
</tr>
<tr>
<td><strong>Female Participation</strong></td>
<td>Female Participants</td>
<td>Count female athletes</td>
<td>Gender inclusion metrics</td>
</tr>
<tr>
<td><strong>Male Participation</strong></td>
<td>Male Participants</td>
<td>Count male athletes</td>
<td>Gender balance analysis</td>
</tr>
</tbody>
</table>

## 🌍 Page 3: Global Medal & Country Insights

### 🎯 Medal KPIs
<table>
<thead>
<tr>
<th>Medal Type</th>
<th>KPI Name</th>
<th>Calculation</th>
<th>Significance</th>
</tr>
</thead>
<tbody>
<tr>
<td>🥉 Bronze</td>
<td>Total Bronze Medals</td>
<td>Sum of bronze medals</td>
<td>Third-place achievements</td>
</tr>
<tr>
<td>🥈 Silver</td>
<td>Total Silver Medals</td>
<td>Sum of silver medals</td>
<td>Second-place performances</td>
</tr>
<tr>
<td>🥇 Gold</td>
<td>Total Gold Medals</td>
<td>Sum of gold medals</td>
<td>Championship-level achievements</td>
</tr>
</tbody>
</table>

### 📊 Advanced Visual Analytics
<table>
<thead>
<tr>
<th>Visual</th>
<th>Chart Type</th>
<th>Data Relationship</th>
<th>Analytical Insight</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Country Performance Matrix</strong></td>
<td>Matrix Table</td>
<td>Country vs. Performance Quintile</td>
<td>Country ranking distribution</td>
</tr>
<tr>
<td><strong>Athlete Efficiency</strong></td>
<td>Stacked Area Chart</td>
<td>Medals per athlete by nationality</td>
<td>Country performance efficiency</td>
</tr>
<tr>
<td><strong>Performance Trends</strong></td>
<td>Line Chart</td>
<td>Moving average of medals by rank</td>
<td>Performance trend analysis</td>
</tr>
<tr>
<td><strong>Sports Participation</strong></td>
<td>Stacked Bar Chart</td>
<td>Number of sports vs. athlete count</td>
<td>Sports diversity per country</td>
</tr>
<tr>
<td><strong>Global Distribution</strong></td>
<td>Azure Map</td>
<td>Athlete distribution by country</td>
<td>Geographical participation analysis</td>
</tr>
</tbody>
</table>

## ⚡ Technical Features

<table>
<thead>
<tr>
<th>Feature Category</th>
<th>Specific Features</th>
<th>Technology Used</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Interactivity</strong></td>
<td>Interactive visuals, slicers, filters</td>
<td>Power BI Native Controls</td>
</tr>
<tr>
<td><strong>Data Management</strong></td>
<td>Embedded dataset, no external files</td>
<td>Power BI Internal Data Model</td>
</tr>
<tr>
<td><strong>Calculations</strong></td>
<td>DAX-driven KPIs, dynamic insights</td>
<td>DAX (Data Analysis Expressions)</td>
</tr>
<tr>
<td><strong>Navigation</strong></td>
<td>Page-to-page navigation buttons</td>
<td>Power BI Buttons & Actions</td>
</tr>
<tr>
<td><strong>Geospatial Analysis</strong></td>
<td>Country-based mapping with bubble sizes</td>
<td>Azure Maps Integration</td>
</tr>
</tbody>
</table>

## 🚀 Implementation Guide

<table>
<thead>
<tr>
<th>Step</th>
<th>Action</th>
<th>Requirements</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>1. Access</strong></td>
<td>Download or clone repository</td>
<td>GitHub access or file download</td>
</tr>
<tr>
<td><strong>2. Open</strong></td>
<td>Open .pbix file in Power BI Desktop</td>
<td>Power BI Desktop installed</td>
</tr>
<tr>
<td><strong>3. Explore</strong></td>
<td>Use buttons and slicers for insights</td>
<td>Basic Power BI navigation skills</td>
</tr>
<tr>
<td><strong>4. Analyze</strong></td>
<td>Interact with filters and visualizations</td>
<td>No technical skills required</td>
</tr>
</tbody>
</table>

## 📺 Demonstration Resources

<table>
<thead>
<tr>
<th>Resource</th>
<th>Platform</th>
<th>Content</th>
<th>Access</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Live Demo</strong></td>
<td>YouTube</td>
<td>Complete dashboard walkthrough</td>
<td>@raslenferchihi channel</td>
</tr>
<tr>
<td><strong>Project Files</strong></td>
<td>GitHub</td>
<td>Complete .pbix source file</td>
<td>Repository download</td>
</tr>
<tr>
<td><strong>Documentation</strong></td>
<td>README</td>
<td>Comprehensive usage guide</td>
<td>Current document</td>
</tr>
</tbody>
</table>

## 🔒 License Information

<table>
<thead>
<tr>
<th>Usage Type</th>
<th>Permission</th>
<th>Restrictions</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Educational Use</strong></td>
<td>✅ Allowed</td>
<td>Learning and academic purposes</td>
</tr>
<tr>
<td><strong>Portfolio Display</strong></td>
<td>✅ Allowed</td>
<td>Career and skill demonstration</td>
</tr>
<tr>
<td><strong>Commercial Use</strong></td>
<td>❌ Not Permitted</td>
<td>No business or revenue generation</td>
</tr>
<tr>
<td><strong>Modification</strong></td>
<td>✅ Allowed</td>
<td>For personal learning purposes</td>
</tr>
<tr>
<td><strong>Redistribution</strong></td>
<td>❌ Not Permitted</td>
<td>Cannot share modified versions</td>
</tr>
</tbody>
</table>

## 📊 Skill Demonstration

<table>
<thead>
<tr>
<th>Technical Skill</th>
<th>Demonstration Level</th>
<th>Specific Implementation</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Power BI Development</strong></td>
<td>Advanced</td>
<td>Multi-page dashboard with navigation</td>
</tr>
<tr>
<td><strong>DAX Programming</strong></td>
<td>Intermediate</td>
<td>Custom KPIs and calculated measures</td>
</tr>
<tr>
<td><strong>Data Modeling</strong></td>
<td>Intermediate</td>
<td>Star schema with fact/dimension tables</td>
</tr>
<tr>
<td><strong>Data Visualization</strong></td>
<td>Advanced</td>
<td>Multiple chart types and interactive elements</td>
</tr>
<tr>
<td><strong>UI/UX Design</strong></td>
<td>Intermediate</td>
<td>Olympic-themed consistent design</td>
</tr>
</tbody>
</table>

---

**Developed by Raslen Ferchichi**  
*Transforming sports data into actionable insights through powerful business intelligence* 📈🎯
