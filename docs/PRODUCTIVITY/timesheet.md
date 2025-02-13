---
title: Timesheet
excerpt: >-
  Explore the **Timesheet** feature in **mobohubb**, which monitors employee
  hours, verifies clock ins/outs, calculates pay, and offers various data views
  for thorough oversight. This guide provides a detailed, narrative-style
  explanation of how to access, navigate, and manage timesheets, including shift
  records, paid/unpaid breaks, and advanced filtering.
deprecated: false
hidden: false
metadata:
  robots: index
---
**In this guide you'll learn**

* [Accessing and Navigating Timesheet](#accessing-and-navigating-timesheet)
* [Tab Bar Overview](#tab-bar-overview)
* [Tool Bar Functions](#tool-bar-functions)
* [Timesheet Tab](#timesheet-tab)
* [Clock In/Clock Out Tab](#clock-inclock-out-tab)
* [Payroll by User and Payroll by Site](#payroll-by-user-and-payroll-by-site)
* [Timesheet Filtering and Searching](#timesheet-filtering-and-searching)
* [Exporting, Column Customization, and Saving Views](#exporting-column-customization-and-saving-views)
* [Editing Records and Using Audit Logs](#editing-records-and-using-audit-logs)
* [Integrations with Schedules, Shifts, and Payroll](#integrations-with-schedules-shifts-and-payroll)
* [Timesheet as a Foundational Tool](#timesheet-as-a-foundational-tool)

***

The **Timesheet** feature in **mobohubb** monitors employee hours, including clock-ins, clock-outs, breaks, overtime, and pay. Each record is generated whenever a user clocks in or out in the mobile app—regardless of scheduling. The web portal offers filtering, searching, exporting, and column adjustments, streamlining your capacity to oversee and audit employee time.

***

## Accessing and Navigating Timesheet

To open Timesheet, click the **left-side menu**, select **“Productivity,”** then **“Timesheet.”** Only **Site Administrators**, **Organization Managers**, or **Editors** can access and manage it. You must also **select a site** at the top of the interface. Each record you see or edit pertains to that selected site.

Once inside, you’ll see:

1. A **Tab Bar** for switching between Timesheets, Clock in/Clock out, Payroll by User, and Payroll by Site.
2. A **Tool Bar** for filters, search, export, column customization, saving views, and restoring defaults.
3. The **Main Content** area displaying records for whichever tab you have open.

***

## Tab Bar Overview

The tab bar lets you move between different sections:

**Timesheets**: Displays all data in chronological order, including pay rates, hours worked, breaks, and site names.\
**Clock In/Clock Out**: Focuses on times recorded, leaving out pay information.
**Payroll by User**: Shows costs at the user level.
**Payroll by Site**: Presents costs at the site level, covering multiple users.

***

## Tool Bar Functions

Located at the top, the tool bar includes:

**Filter**: Choose quick or advanced filters to refine data by user, date, device, or tags.\
**Search Bar**: Enter text to find records by name or description.
**Export Button**: Saves your view into an Excel file.
**Columns**: Toggle columns on or off for the displayed table.
**Save View**: Retain your current filter/column setup for easy reuse.
**Three-Dots Menu**: Access additional options like “Restore View,” which resets everything to default.

***

## Timesheet Tab

Upon opening Timesheet, you land on the **Timesheets** tab. This section merges all time logs:

It may show:

* A **checkbox** to select multiple rows.
* **S/NO** for sequential indexing.
* **User** for who logged the hours.
* **Device Name** to identify hardware used.
* **Date** of the log.
* **Pay Rate** as specified in the user’s profile.
* **Pay Out** calculated from the rate and hours worked.
* **Worked Time** minus unpaid breaks.
* **Break Time** distinguishing paid and unpaid breaks.
* **Audit Log** offering visibility into modifications.
* **Site Name** indicating the location or project name.

Click or hover over certain fields to view or edit data, provided your role permits it.

***

## Clock In/Clock Out Tab

Whereas the Timesheets tab includes pay details, the **Clock In/Clock Out** tab centers on attendance:

It typically contains the user’s name, device, site name, date, worked time, and total break duration. Selecting an entry might reveal additional data like selfies taken at clock in/out, notes, location validations, or a map view of the coordinates at clock in/out.

***

## Payroll by User and Payroll by Site

These tabs extend time records into direct cost data:

**Payroll by User**: Organizes pay information per employee, showing hours worked, assigned hourly rates, and final pay within a chosen date range.\
**Payroll by Site**: Summarizes how much time was logged across an entire location, multiple users, and their pay rates. You can edit clock in/out times, hourly rates, and approval statuses, with any changes documented in the audit log.

For deeper info on merging hours worked with pay details, refer to the dedicated **Payroll** guide.

***

## Timesheet Filtering and Searching

Refining your timesheet data often involves filtering or searching:

**Quick Filters**: Provide straightforward segmentation (e.g., by specific user or device).\
**Advanced Filters**: Let you build multi-logic conditions, combining multiple rules like “equals,” “not equals,” or “contains.”
A **Search Bar** sits at the top for keyword-based record lookups.

***

## Exporting, Column Customization, and Saving Views

After adjusting filters or searching, you may export your refined dataset to **Excel** via the **Export** button. This allows you to share or review timesheet data offline. If you’d rather see fewer or more columns, open the **Columns** option to toggle each one. Meanwhile, the **Save View** button ensures you can easily return to a specific arrangement of filters and columns anytime.

***

## Editing Records and Using Audit Logs

Certain fields are editable within Timesheet tabs, such as **total hours** or **break durations**. Changing these may affect computed pay. All user-driven changes appear in a different color or designated marker, and an **Audit Log** button indicates who made edits, the values changed, and the timestamp for each change, preserving data integrity.

***

## Integrations with Schedules, Shifts, and Payroll

Timesheet automatically reconciles user activity with any shifts assigned or schedules set up for employees. This means you can see a direct comparison between planned hours versus actual hours. Coupled with the **Payroll** tabs and user profiles, time tracking extends to cost calculations, overtime, and other financial considerations. As employees clock in/out, timesheet data merges seamlessly to reflect both scheduling and budgeting in a single system.

***

## Timesheet as a Foundational Tool

Timesheet stands at the center of **mobohubb**’s workforce management, providing a unified record of labor hours, breaks, pay rates, and site details. By incorporating advanced filters, search tools, exports, and an audit log, Timesheet fosters transparency and efficiency in managing employee attendance and compensation.

Use Timesheet alongside shifts, schedules, device logs, or the payroll feature to build a comprehensive and customizable workflow, from clock in to final payout. Any manual adjustments or anomalies remain traceable through the audit log, ensuring confidence in your data. With Timesheet, you ensure every hour is logged, verified, and paid accurately.