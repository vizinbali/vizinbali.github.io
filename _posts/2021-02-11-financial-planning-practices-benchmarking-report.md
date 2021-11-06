---
title: Financial Planning Practices - Performance Benchmarking Interactive Report
tags: 
- Work Project
- Tableau Desktop
- Tableau Prep
- Microsoft Excel
cover: /FPDashboard.png
---
*Note: This post is best viewed on desktop.*

## Visualisation
The report below only contains parts of the entire workbook and uses dummy data. The dummy data source contains data of 6 fictious Financial Planning practices. To view the performance of different practices, click the **Select a Practice** dropdown from the first Staffing dashboard.

<div class='tableauPlaceholder' id='viz1636180066993' style='position: relative'><noscript><a href='#'>
    <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pe&#47;PerformanceBenchmarkingDashboards-withAdjustedBusinessOwnersSalary-20210211-Copy&#47;Staffing-Cover&#47;1_rss.png' style='border: none' />
</a>
</noscript>
<object class='tableauViz'  style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
    <param name='embed_code_version' value='3' /> 
    <param name='site_root' value='' />
    <param name='name' value='PerformanceBenchmarkingDashboards-withAdjustedBusinessOwnersSalary-20210211-Copy&#47;Staffing-Cover' />
    <param name='tabs' value='yes' />
    <param name='toolbar' value='no' />
    <param name='device' value='desktop' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-GB' />
    <param name="dataDetails" value="no" />
    <param name="alerts" value="no" />
    <param name="showShareOptions" value="false" />
    <param name="subscriptions" value="no" />
   
</object>
</div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1636180066993');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    
    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1169px';vizElement.style.height='877px';} 
    else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1169px';vizElement.style.height='877px';} 
    else { vizElement.style.width='100%';vizElement.style.height='2900px';}                     
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Overview
### Background
In September 2020, I started a work project to design an end-to-end reporting solution for a Financial Planning group based in Australia. This project was completed in February 2021.

The client had double-digit practices (franchises) and would like to know more about each practice's performance when compared against its peers (the other practices) during a predetermined period of time. The goal of this project is to automate the generation of customised PDF reports for each practice, as well as an interactive report for the executives. In addition, the client requested that the peers' results to be anonymised, i.e. each practice can only view the details of their own results in their customised reports.

### Project Details
To complete this project:
* I designed a Tableau Prep Flow that extracts the contents of the client's questionnaire inputs in 7 seconds. The output is saved as a CSV file.
* I planned and designed a Microsoft Excel database to compile the extracted questionnaire data. I utilised VBA to automate the copy-and-pasting process from the Tableau Prep output (CSV file) to the database. This database is used as the data source for the Tableau Desktop workbook.
* I planned, designed, and created a Tableau workbook, which comprises of **7 chapters**. Each chapter focuses on different aspects of a Financial Planning business' performance, such as revenue, expenses, profitability, etc. The Tableau workbook contains:
    * **44** dashboards; **2** of the dashboards have What-If (Scenario) Analysis capabilities, designed using parameters embedded in calculated fields
    * **298 sheets**, with the following breakdown: **184** charts, **11** tables, and **103** BANs
    * **310** calculated fields
    * **4** parameters

## Inspiration
[Income Statement](https://public.tableau.com/app/profile/andy.kriebel/viz/IncomeStatement_4/IncomeStatement) by **Andy Kriebel** - A beautiful and clean KPI dashboard.
