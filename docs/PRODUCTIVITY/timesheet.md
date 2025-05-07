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
**In this guide you’ll learn**

* Where to **find the Timesheet module** and which roles can access it
* How each tab—**Timesheets and Payroll by Site**—differs and when to use them
* How to **filter, search, export, hide/show columns, and save custom views** for quick auditing
* How to **edit time entries, break durations, and hourly rates** (and trace every change through the Audit Log)
* How Timesheet data **feeds into payroll calculations** and reconciles with scheduled shifts for accurate cost reporting

***

The **Timesheet** feature in **mobohubb** monitors employee hours, including clock-ins, clock-outs, breaks, overtime, and pay.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/825ff253580adb65f14994447e11d5f84ad669f73323f65d2718d53442602e7b-image.png" />

Each record is generated whenever a user clocks in or out in the mobile app—regardless of scheduling. The web portal offers filtering, searching, exporting, and column adjustments, streamlining your capacity to oversee and audit employee time.

***

## Accessing and Navigating Timesheet

From the left-side menu, under the **Productivity** section, **select Timesheet**. Only **Site Administrators**, **Organization Managers**, or **Editors** can manage this tool.

<Image align="center" className="border" border={true} src="https://files.readme.io/d20cd6d091ab4618b9fc9e53c32bf7f2cb9063793c713409aeea5d2891e2ddc9-E0CF5EEF-9A71-4811-8DDE-6C4EDEEFC509.png" />

Make sure to **select a site** from the site selector:

<Image align="center" className="border" border={true} src="https://files.readme.io/ec5ab68428cd9b368713c2dfff674cb9f3687b81c086f1d9af22c3c67e32532a-image.png" />

<br />

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/928b813bfbbc56f3f771ebf38cdd71e732e60dfcd738e844490bd97eeea631e2-668173C0-C3BC-4A2C-B710-5F43546A631E.png" />

Once inside, you’ll see:

1. A **Tab Bar** for switching between Timesheets and Payroll by Site.
2. A **Tool Bar** for filters, search, export, column customization, saving views, and restoring defaults.
3. The **Main Content** area displaying records for whichever tab you have open.

***

## Tab Bar Overview

The tab bar lets you move between different sections:

<Image align="center" className="border" border={true} src="https://files.readme.io/511fe1a7163124ec62241f5b805932603346254532835fba0611bd72c938bdf2-image.png" />

**Timesheets**: Displays all data in chronological order, including pay rates, hours worked, breaks, and site names.\
**Payroll by Site**: Presents costs at the site level, covering multiple users.

***

## Tool Bar Functions

Located at the top, the toolbar includes:

<Image align="center" className="border" border={true} width="100% " src="https://files.readme.io/97b02a9f877d20c072eba16e6572718f3989bf7aa2ea41e51b9712d2a01d87d4-02E64E72-FC1B-4DAF-A488-53886443FCD5.png" />

**Filter**: Choose quick or advanced filters to refine data by user, date, and role.\
**Search Bar**: Enter text to find records by name or description.
**Export Button**: Saves your view into an Excel file.
**Columns**: Toggle columns on or off for the displayed table.
**Three-Dots Menu**: Access additional options like “Restore View,” which resets everything to default.

***

## Timesheet Tab

Upon opening Timesheet, you land on the **Timesheets** tab. This section merges all time logs:

<Image align="center" className="border" border={true} src="https://files.readme.io/58d642a32021bed881058e2e147116dd7ef2a6debf5a25e3cd4ba7ef302823e0-image.png" />

It may show:

* A **checkbox** to select multiple rows.
* **S/NO** for sequential indexing.
* **User** for who logged the hours.
* **Device Name** to identify device used.
* **Date** of the log.
* **Worked Time** minus unpaid breaks.
* **Break Time** distinguishing paid and unpaid breaks.
* **Paid Break** time.
* **Audit Log** offering visibility into modifications.
* **Site Name** indicating the site name.

**Click** or **hover** over colored fields to view or edit data.

***

## Payroll by Site Tab

This tab extends time records into direct cost data.

* **Payroll by Site**: Summarizes how much time was logged across an entire location, multiple users, and their pay rates. You can edit clock in/out times, hourly rates, and approval statuses, with any changes documented in the audit log.

<Image align="center" className="border" border={true} src="https://files.readme.io/7266348df702b297422426f0c43d5877797ccb5d13249585b35f39ba99ef0302-image.png" />

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

Certain fields are editable within Timesheet and Payroll by Site tabs, such as **worked time** or **break durations**. Changing these may affect computed pay.

<Image align="center" className="border" border={true} src="https://files.readme.io/b0b7459b981fdc4f6f89454b4598f1ddc9aa385b3ee886b97a7c5504303486ed-image.png" />

### Timesheets tab

#### Editing an Entry

1. From the **Timesheets** tab, you can easily modify the Worked time by clicking on the specific row you want to edit, or hover over the cell, change its contents, and press **Enter**.

<Image align="center" className="border" border={true} src="https://files.readme.io/1c29eea0063eb405e8d1ee11a35e8cd192af17ba565a9d373e7610b3976268d3-image.png" />

* For **Entry Time**, you can directly edit the field by writing in it and pressing "Enter".
* For a detailed edition, **press** the **Pencil button** under the **Actions** column.

<Image align="center" className="border" border={true} src="https://files.readme.io/10d7b2eb4381ca23e7c0d63ae0af144984912dcfd73f689c0bfbed3ae60537b1-image.png" />

2. **Modify** the fields as needed.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/e27684d869ff85f0644db2410325bbb20755310589ff3be66d0c1957e0c06e31-image.png" />

3. **Press** **Update** to save your changes.

#### Adding an Entry

1. **Press** the **Add New** button.

<Image align="center" className="border" border={true} src="https://files.readme.io/90ca3e21e29cea91d3252b2c7a8229e24495ff74c70740824ca44081efbaef28-Screenshot_2025-05-06_at_3.50.13_PM.png" />

2. **Fill** in the information. In this example, we are adding a **paid break** from 11:00:00 AM to 11:30:00 AM.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/bccb4d6cf0e73a3d6eeaa14cefa50604b703dbc2735440f5ca3bdda6a29d80c4-image.png" />

3. **Save** your entry. It will appear on the entries list.

<Image align="center" className="border" border={true} src="https://files.readme.io/90e6cf62f1c13936cfc77f4ecc9ef71a9e4a574076ed7c8d3bb59c6fa7665050-Screenshot_2025-05-06_at_3.57.07_PM.png" />

### Payroll by Site

#### Editing an Entry

From the **Payroll by Site** tab you can easily modify the records by clicking over **Clock-in**, **Clock-out**, and **Hourly Rate** (hourly pay will only affect this specific shift. If you want to modify the hourly pay at a general level, please visit our [Roles ](https://mobohubb.readme.io/docs/roles#/add-roles)guide, where you can learn how to do it).

* You can edit **Clock-in**, **Clock-out**, and **Hourly Rate** by overwriting their contents and pressing **Enter**.

<Image align="center" className="border" border={true} src="https://files.readme.io/f154b2a8d2dbd7691b5bbcb09485a5dc45b66f929d0793c0571dc791cc2b2465-Screenshot_2025-05-06_at_3.58.20_PM.png" />

* You can change the **Approval Status** by selecting the appropiate option from the drop-down menu under that column.

<Image align="center" className="border" border={true} src="https://files.readme.io/11adc3ff9d3e98380f86460e3247d52f5950f37a55e8a8b31edabd5c1632efba-image.png" />

### Revising Audit Logs

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