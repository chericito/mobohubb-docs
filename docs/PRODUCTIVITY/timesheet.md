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

The **Timesheet** feature in **mobohubb** monitors employee hours, including clock-ins, clock-outs, breaks, overtime, and pay.

<Image align="center" className="border" border={true} src="https://files.readme.io/242cb51b42550aba352885c649b3161fe2efeadee91a73f6cbe2eb4d4fd2b7c9-3F05309C-314D-4252-9A4D-3A0DA47B63E2.png" />

Each record is generated whenever a user clocks in or out in the mobile app—regardless of scheduling. The web portal offers filtering, searching, exporting, and column adjustments, streamlining your capacity to oversee and audit employee time.

***

## Accessing and Navigating Timesheet

From the left-side menu, under the **Productivity** section, **select Timesheet**. Only **Site Administrators**, **Organization Managers**, or **Editors** can manage this tool.

<Image align="center" className="border" border={true} src="https://files.readme.io/d20cd6d091ab4618b9fc9e53c32bf7f2cb9063793c713409aeea5d2891e2ddc9-E0CF5EEF-9A71-4811-8DDE-6C4EDEEFC509.png" />

Make sure to **select a site** from the site selector:

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/928b813bfbbc56f3f771ebf38cdd71e732e60dfcd738e844490bd97eeea631e2-668173C0-C3BC-4A2C-B710-5F43546A631E.png" />

Once inside, you’ll see:

1. A **Tab Bar** for switching between Timesheets, Clock in/Clock out, Payroll by User, and Payroll by Site.
2. A **Tool Bar** for filters, search, export, column customization, saving views, and restoring defaults.
3. The **Main Content** area displaying records for whichever tab you have open.

***

## Tab Bar Overview

The tab bar lets you move between different sections:

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/2d0fe36e38835d066ff523ea49a72db60355b2705cd894381c0c98bf430901e7-69B80EEB-E53C-4AE0-8865-2020CB534EE1.png" />

**Timesheets**: Displays all data in chronological order, including pay rates, hours worked, breaks, and site names.\
**Clock In/Clock Out**: Focuses on times recorded, leaving out pay information.
**Payroll by User**: Shows costs at the user level.
**Payroll by Site**: Presents costs at the site level, covering multiple users.

***

## Tool Bar Functions

Located at the top, the tool bar includes:

<Image align="center" className="border" border={true} width="100% " src="https://files.readme.io/97b02a9f877d20c072eba16e6572718f3989bf7aa2ea41e51b9712d2a01d87d4-02E64E72-FC1B-4DAF-A488-53886443FCD5.png" />

**Filter**: Choose quick or advanced filters to refine data by user, date, device, or tags.\
**Search Bar**: Enter text to find records by name or description.
**Export Button**: Saves your view into an Excel file.
**Columns**: Toggle columns on or off for the displayed table.
**Save View**: Retain your current filter/column setup for easy reuse.
**Three-Dots Menu**: Access additional options like “Restore View,” which resets everything to default.

***

## Timesheet Tab

Upon opening Timesheet, you land on the **Timesheets** tab. This section merges all time logs:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/a8cbd92af54a2ad19b6c2f8321bf504d2324916d02f54225ff7f10c77f39329c-EB1F0345-0F28-46DB-AA36-9C60AAE31F35.png" />

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

Click or hover over colored fields to view or edit data.

***

## Clock In/Clock Out Tab

Whereas the Timesheets tab includes pay details, the **Clock In/Clock Out** tab centers on attendance:

It typically contains the user’s name, device, site name, date, worked time, and total break duration. Selecting an entry might reveal additional data like selfies taken at clock in/out, notes, location validations, or a map view of the coordinates at clock in/out.

***

## Payroll by User and Payroll by Site

These tabs extend time records into direct cost data.

* **Payroll by User**: Organizes pay information per employee, showing hours worked, assigned hourly rates, and final pay within a chosen date range.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/2009ec405ada144588f5b86062c23fb87b5949202ad505199b10d73754ba6b01-image.png" />

<br />

* **Payroll by Site**: Summarizes how much time was logged across an entire location, multiple users, and their pay rates. You can edit clock in/out times, hourly rates, and approval statuses, with any changes documented in the audit log.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b08c5f9d9c801952002be450c34824cad85d897fb8b242ff6644200ccb82a1cc-image.png" />

For deeper info on merging hours worked with pay details, refer to the dedicated **[Payroll](https://mobohubb.readme.io/docs/payroll#/)** guide.

***

## Timesheet Filtering and Searching

Refining your timesheet data often involves filtering or searching:

* **Quick Filters**: Provide straightforward segmentation (e.g., by specific user or device).

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/662966f1d5da3b59468e09393417789d8cb4b79d53fe843396cd6b7fe277a078-2830B659-E8DD-4785-AC74-9F3C83DDFF6F.png" />

* **Advanced Filters**: Let you build multi-logic conditions, combining multiple rules like “equals,” “not equals,” or “contains”.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/0152c5eddb48458cd4d124b167e7ce2ca3ea0feb6a27fc4abce97ee757b7f454-539078C7-C336-4917-A6A5-F778A519A912.png" />

* **Search Bar** sits at the top for keyword-based record lookups.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/fe16acd4dba3b858216df94d331a8b63136e34c1144b4bc4f3bd1ebeae7b1a26-A4E7920C-81C6-4438-82F0-DFCBC6E0E7B2.png" />

<br />

## Exporting, Column Customization, and Saving Views

After adjusting filters or searching, you may export your refined dataset to **Excel** via the **Export** button.

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/2dacd54c1e9b76e7ef85abaaf661913ed48c2779bc6d1c54dd9b1f064410ab14-D4B34B3D-5AE4-4647-9F9C-8E45B3D75C18.png" />

This allows you to share or review timesheet data offline. If you’d rather see fewer or more columns, open the **Columns** option to toggle each one.

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/5a601f7dabd9c8bbee0f67b4f392c91038af6b3b92698cd94b48d1297aa02cac-262286A3-575A-4C0B-8C18-02D815FDA907.png" />

***

## Editing Records and Using Audit Logs

Certain fields are editable within Timesheet tabs, such as **worked time** or **break durations**. Changing these may affect computed pay.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/23872d3a5396f0726cc6d0f4f6370c22c09906b0848ab59d28e7a1a975fcd9a1-DB2604FD-6DDD-4571-83FF-3410F0F067B2.png" />

Toggle **“Audit log”** in the **“Columns”** menu to track edits:

<Image align="center" className="border" border={true} src="https://files.readme.io/f49fab84475f8292c29b0e6f86b98e8f2b0702a0c03cb3d2d4abd9e39a820407-CB8737B5-9EDE-4D68-B2A2-BF8D05D2A9B3.png" />

You’ll see what changed, who made it, and when.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/75aa048c17c00a174c98b8d4476a22a91f60508b583ac4bf7782b53c09d99ed5-ADCED031-14AD-469B-B0FC-F649974B7401.png" />

***

## Integrations with Schedules, Shifts, and Payroll

Timesheet automatically reconciles user activity with any shifts assigned or schedules set up for employees. This means you can see a direct comparison between planned hours versus actual hours. Coupled with the **Payroll** tabs and user profiles, time tracking extends to cost calculations, overtime, and other financial considerations. As employees clock in/out, timesheet data merges seamlessly to reflect both scheduling and budgeting in a single system.

***

## Timesheet as a Foundational Tool

Timesheet stands at the center of **mobohubb**’s workforce management, providing a unified record of labor hours, breaks, pay rates, and site details. By incorporating advanced filters, search tools, exports, and an audit log, Timesheet fosters transparency and efficiency in managing employee attendance and compensation.

Use Timesheet alongside shifts, schedules, device logs, or the payroll feature to build a comprehensive and customizable workflow, from clock in to final payout. Any manual adjustments or anomalies remain traceable through the audit log, ensuring confidence in your data. With Timesheet, you ensure every hour is logged, verified, and paid accurately.