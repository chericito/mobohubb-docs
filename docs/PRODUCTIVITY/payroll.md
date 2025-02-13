---
title: Payroll
excerpt: >-
  Learn how to manage your organization’s **Payroll** in mobohubb, a sub-feature
  of Timesheet that offers detailed views of shifts, hours worked, hourly rates,
  and daily pay. This guide provides an overview of payroll’s flexibility,
  including editing work hours, approving or rejecting pay, and auditing changes
  for full transparency.
deprecated: false
hidden: false
metadata:
  robots: index
---
**In This Guide You'll Learn**

* How **Payroll** extends Timesheet to show clock ins, clock outs, and user pay details
* How to **filter and manage** planned vs. worked hours for easy payroll adjustments
* How to **approve, reject, or keep pending** each shift’s pay
* How the **audit log** ensures transparency for payroll changes

***

**Payroll** is a sub-feature of **Timesheet** that provides a detailed view of each user’s shifts—clock ins, clock outs, hours worked, overtime, hourly rate, and daily pay. If you’ve assigned recurrent or one-day shifts, Payroll can compare **planned** vs. **worked** hours for valuable insight into scheduling and costs. You can **adjust** hours worked, hourly pay rates, and more, filtering shifts by date or other criteria to streamline your process.

<Cards columns={3}>
  <Card title="Granular Shift Details" icon="fa-list">
    Review each user’s clock ins and clock outs, hours worked, overtime, and pay.\
    Track both *planned* vs. *worked* hours for real-time insight.
  </Card>

  <Card title="Flexible Editing" icon="fa-edit">
    Easily modify hours, pay rates, and overtime details per user, per shift.\
    Use the **Payroll filters** to find today’s shifts, upcoming shifts, or older records.
  </Card>

  <Card title="Approval & Audit" icon="fa-check-circle">
    Approve, reject, or keep pay pending for any shift.\
    View an **audit log** to see who changed what and when, ensuring full transparency.
  </Card>
</Cards>

Using the **Payroll** feature, you can fine-tune every aspect of compensation to match your organizational rules and agreements. Its integrated **audit log** ensures that any change to editable fields (like work hours or overtime pay) is recorded, giving you comprehensive control and **confidence** in your payroll process.

## Access Payroll

From the left panel, under the **Productivity** section, **select Timesheet**. Only **Site Administrators**, **Organization Managers**, or **Editors** can manage this tool.

![](https://files.readme.io/d20cd6d091ab4618b9fc9e53c32bf7f2cb9063793c713409aeea5d2891e2ddc9-E0CF5EEF-9A71-4811-8DDE-6C4EDEEFC509.png)

Make sure to **select a site** from the site selector:

![](https://files.readme.io/10e2a33e8e1a6d9527120f765ec435acb7a4c2fadd43fd6f08aae62933846f72-4CF669AA-AF30-4827-924A-4B7711137EEE.png)

From here, you’ll see a general overview of people’s shifts and a **Clock In/Clock Out** breakdown for each user. Refer to our dedicated **Timesheet** guide for more info.

Two Payroll tabs are available:

1. **Payroll by User**
2. **Payroll by Site**

***

## Payroll by User

![](https://files.readme.io/bdfc43e5934ed9bf4f82863d5126edeac084848a9d884c9442dcf2fd5d5c626e-140D8F4C-ED67-45CE-940B-B7788A19D73A.png)

**Payroll by User** provides a general overview of all your users’ payroll data. Use filters to select specific users and dates:

![](https://files.readme.io/9133572c0b7d348df05f6c07c229c849e3bc70ff89785ab2e264c182ceb1cb66-image.png)

You can choose a pre-set or custom **date range**:

![](https://files.readme.io/4a6af803a389d751d25a00d757f6254cdd5538531e89c8849f838797a5daa17c-826E0D5D-31FA-439C-AB4E-4FE715892B53.png)

Press **“Apply”** to filter or **“Clear All”** to reset. At least a date range is needed to generate a report.

### Export (Payroll by User)

Click **“Export”** at the top of the report, then **“Export data”** to download an Excel file reflecting your current filter setup. For a different export, adjust your filters accordingly.

***

## Payroll by Site

**Payroll by Site** offers a more granular, shift-by-shift breakdown for each user:

![](https://files.readme.io/be07bb709d4551eed1c6808ff3d276069a96e1919a6b939c25b8f5715181a665-image.png)

Filter by date range, schedule name, username, and approval status. At least a **date range** is required to see any data. You can also **show/hide** columns using the **“Columns”** button above the report.

### Modifications (Payroll by Site)

You can edit **Clock In/Out**, **Hourly Rate**, and **Approval Status**:

* **Clock In/Clock Out** changes recalculate **hours worked** and daily pay.
* **Hourly Rate** changes directly affect the **daily pay**.
* Any changes appear in a distinct color.

If a shift was assigned, e.g., “cleaning bathrooms shift” with set hours, “Planned hours” will show. The system calculates overtime and final daily pay automatically based on the assigned rate. You can assign hourly pay rates and overtime via **[Roles configuration feature](https://mobohubb.readme.io/docs/roles#/add-roles)** and **[Users role assignment](https://mobohubb.readme.io/docs/users#/edit-users)**.

Approval Status can be set to **Pending**, **Rejected**, or **Approved**:

![](https://files.readme.io/25571dd6e0ebbf9c05cc68b8dc7ad0b7e469be9421f56bf0c6d6b6e7e21ae129-886431A1-DD0F-4A10-A43B-01D2E49C8F0C.png)

By default, only **pending** items appear. Change filters to see different statuses.

### Audit Log

Toggle **“Audit log”** in the **“Columns”** menu to track edits:

![](https://files.readme.io/bbe629ad7496f6fec1d951d7214262961173b17e6b7beebfc022692d3317d9e1-44E644E9-9643-4FD5-86F2-1E32CCACD744.png)

You’ll see what changed, who made it, and when:

![](https://files.readme.io/b03b6aa821d2a3c52c47c6e57e0f7ddc0593d906aa7893fcb1151843dc0256a8-D3EB3B04-3154-425B-8962-D86AE1A03CEF.png)

### Export (Payroll by Site)

Click **“Export”** at the top, then **“Export data”** to download an Excel file of your current view. Change filters first if you want a different export.

***

That’s how you manage payroll in **mobohubb**, leveraging filters, edits, approvals, and audit logs for a transparent and efficient workflow.

# Access Payroll

From the left panel, under the Productivity section, select Timesheet. Only, Site Administrators, Organization Manager and Editors are the security groups with the permissions to enter/manage this tool.

<Image align="center" className="border" border={true} src="https://files.readme.io/d20cd6d091ab4618b9fc9e53c32bf7f2cb9063793c713409aeea5d2891e2ddc9-E0CF5EEF-9A71-4811-8DDE-6C4EDEEFC509.png" />

<br />

Make sure to select a site from the site selector.

<Image align="center" className="border" border={true} src="https://files.readme.io/10e2a33e8e1a6d9527120f765ec435acb7a4c2fadd43fd6f08aae62933846f72-4CF669AA-AF30-4827-924A-4B7711137EEE.png" />

<br />

From this page you can have a general view on people's shifts and in the clock in/clock out a granutaled view for each user. We have a dedicated guide on Timesheet, please visit it here.

From this page, you have two payroll tabs: Payroll by User and Payroll by Site.

## Payroll by User

<br />

![](https://files.readme.io/bdfc43e5934ed9bf4f82863d5126edeac084848a9d884c9442dcf2fd5d5c626e-140D8F4C-ED67-45CE-940B-B7788A19D73A.png)

**Payroll by User** it's a general view for all your users payrolls. Use the filters to select a specific user/users and the date.

<Image align="center" className="border" border={true} src="https://files.readme.io/9133572c0b7d348df05f6c07c229c849e3bc70ff89785ab2e264c182ceb1cb66-image.png" />

<br />

You can select a date range from our filters, or use a custom one.

<br />

<Image align="center" className="border" border={true} src="https://files.readme.io/4a6af803a389d751d25a00d757f6254cdd5538531e89c8849f838797a5daa17c-826E0D5D-31FA-439C-AB4E-4FE715892B53.png" />

Once you have selected all of your filters, you can press "apply" or "Clear All" to start again and have a clean view. It is important to select at least a date range to visualize the information in the report.

### Export

You can export your current view based on your filters by simply clicking the "Export" button right above the report, and the press "export data". You will get an excel file with the exact same view/information based on your filters. If you want a different export/view, you must change the filters configuration.

## Payroll By Site

<br />

**Payroll by Site** is a more granutaled view of every user and their payroll for a specific time range. You have several columns and filters to utilize, and it gives you the ability to modify certain fields such as clock in and out, hourly rate and the approval status.

<br />

![](https://files.readme.io/be07bb709d4551eed1c6808ff3d276069a96e1919a6b939c25b8f5715181a665-image.png)

You can and should filter by date range, schedule name (which wil also give you the planned hours, overtime, and actual hours worked that can give you a lot more information), user name and approval status.

To visualize a report it is necessary to have at least a date range filter applied. Try using "Today" as reference, and press "Apply".

You can also show/hide columns using the "Columns" button above the report. Use this to have a more customized view.

### Modifications

You can modify Clock in and clock out and hourly rate, as well as changing the Approval Status.

Changing the clock in and out will modify the amount of hours worked and also will impact the daily pay.

Changing the hourly rate will impact the daily pay.

!Important: all changes to the original data will appear in a different color.

If the shift was previously assigned with certain parameters, e.g. "cleaning bathrooms shift" with certain amout of hours, the "Planned hours" column will be populated with the planned hours. In case the user did more hours or overtime, the system will automatically calculate the daily pay based on the hourly pay and overtime pay rate. You can assign hourly pay rates and overtime payrates from the [Roles configuration feature](https://mobohubb.readme.io/docs/roles#/add-roles) and [assign Users that role](https://mobohubb.readme.io/docs/users#/edit-users).

You can change the approval status from Pending to Rejected or Approved.

<br />

<Image align="center" className="border" border={true} src="https://files.readme.io/25571dd6e0ebbf9c05cc68b8dc7ad0b7e469be9421f56bf0c6d6b6e7e21ae129-886431A1-DD0F-4A10-A43B-01D2E49C8F0C.png" />

By default, the system will show the pending for approval/rejection cases. If you want to look at specirfic statuses, it is posisble by just setting it up through the report filters. This is usefull in case you approved something and then realized another change should've happened before or to change the status at anytime.

### Audit Log

You can toggle on/off the Audit log column from the column button above the report. This tool will give you a detailed log of changes made to that specific shift/time worked.

![](https://files.readme.io/bbe629ad7496f6fec1d951d7214262961173b17e6b7beebfc022692d3317d9e1-44E644E9-9643-4FD5-86F2-1E32CCACD744.png)

It will give you info on what was the change made, who made it and when.

![](https://files.readme.io/b03b6aa821d2a3c52c47c6e57e0f7ddc0593d906aa7893fcb1151843dc0256a8-D3EB3B04-3154-425B-8962-D86AE1A03CEF.png)

<br />

### Export

You can export your current view based on your filters by simply clicking the "Export" button right above the report, and the press "export data". You will get an excel file with the exact same view/information based on your filters. If you want a different export/view, you must change the filters configuration.