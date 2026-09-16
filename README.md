# HR-Working-Preference-Dashboard
### 1. Project Title / Headline

Employee Workforce Presence & Work-From-Home Analytics Dashboard

### 2. Short Description / Purpose

An interactive HR analytics dashboard that provides insights into employee presence, WFH, and sick-leave trends. It transforms monthly Excel working-preference data into a standardized dataset and uses Power BI to support workforce planning and business decisions.

### 3. Tech Stack

Example: The dashboard was built using the following tools and technologies: <br>
• 📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
• 📁 File Format – .pbix for development and .png for dashboard previews.<br>

### 4. Data Source

The source data is an Excel workbook containing employee working-preference
information, with each month maintained in a separate worksheet.

Each monthly sheet contains the Employee Name and their date-wise working
preference/status, such as P, WFH, HWFH, HPL, PL, NPL, WO, and PHO.

The data was transformed in Power Query by unpivoting the date columns,
standardizing the structure, and combining the monthly data for Power BI
analysis.

### 5.Features / Highlights

#### Business Problem
Organizations need to understand employee availability and working patterns, but data stored across separate monthly Excel sheets makes it difficult to analyze presence, WFH, and leave trends efficiently.

#### Key questions such as:<br>

What is the overall employee Presence %? <br>
How does WFH % change over time?<br>
Which days of the week have higher WFH or presence?<br>
Which employees have higher or lower presence and WFH percentages?<br>
Are there noticeable changes in sick-leave patterns?<br>

…are difficult to answer efficiently from raw, date-wise Excel data.<br>

#### Goal of the Dashboard

To deliver an interactive HR workforce analytics dashboard that:<br>
Provides a centralized view of employee presence and working preferences.<br>
Tracks Presence %, WFH %, and Sick Leave % over time.<br>
Enables users to analyze working patterns by month, day of week, and employee.<br>

#### Walkthrough of Key Visuals
- Key KPIs — Top Left

The dashboard provides three high-level KPIs:

Presence % – Overall employee presence percentage.
WFH % – Percentage of present days worked from home.
Sick Leave % – Sick-leave percentage based on the defined calculation.

These KPIs provide an immediate summary of workforce availability.

- Month-Year Filter — Top

An interactive Month-Year slicer allows users to select individual months such as:

Apr 22 | May 22 | Jun 22

All relevant visuals update based on the selected month.

- Employee Summary Table — Left

The employee-level table displays:

Employee Name
Presence %
WFH %
Sick Leave %

This allows users to move from an overall workforce view to individual employee-level analysis.

- Presence % Trend — Top Right

The line/area chart displays the Presence % by date.

It helps identify fluctuations in employee availability and periods where overall presence was relatively higher or lower.

- WFH % Trend — Middle Right

The WFH trend visual shows Work From Home % by date.

It helps identify periods with increased WFH activity and understand how WFH patterns change over time.

- Sick Leave % Trend — Bottom Right

The Sick Leave trend displays changes in sick-leave percentage across the reporting period.

This provides visibility into variations in sick-leave patterns over time.

- Day-of-Week Analysis — Right Side

Three tables provide day-of-week analysis for:

Presence %
WFH %
Sick Leave %

This helps identify recurring working patterns across different days of the week.

- Date-wise Working Preference Table — Bottom Left

The detailed table displays each employee's working preference for individual dates, such as:

P | WFH | HWFH | HPL | PL | NPL | WO | PHO

This provides detailed information behind the aggregated dashboard metrics.

#### Business Impact & Insights
i. WFH Trend Analysis

WFH % helps track the monthly trend of employees working from home. This insight can support business decisions such as product release and activity planning. For example, if WFH levels are historically higher during periods such as Diwali, the organization can consider employee availability when scheduling important product releases or business activities.

ii. Event & Meeting Planning

WFH patterns can help identify days when a larger proportion of employees are working remotely. Organizations can use these insights to plan events, team activities, meetings, or other in-person initiatives on days when employee availability at the workplace is expected to be higher.

iii. Sick Leave Monitoring

Tracking Sick Leave % over time can help identify unusual increases in sick-leave patterns. If a significant increase is observed during a particular period, HR or workplace teams can investigate the underlying cause and, where appropriate, coordinate with relevant health and safety teams on preventive measures or employee awareness initiatives.

iv. Workforce Availability

By combining Presence %, WFH %, and Sick Leave %, stakeholders can get a broader view of employee availability and use these insights to support workforce planning and operational decisions.

#### 6. Screenshots / Demos

[Dashboard Preview](https://github.com/Subrahmanya-naik/HR-Working-Preference-Dashboard/blob/main/Snapshot%20of%20Dashboard.png)



