---
title: Report Scheduler
excerpt: >-
  Configure and automate your reports in **mobohubb** using the **Report
  Scheduler**. This guide explains how to create, set up, and customize
  scheduled reports so that they are automatically generated and sent according
  to your needs.
deprecated: false
hidden: false
metadata:
  robots: index
---
**In this guide you'll learn**

* How to **create** a new report scheduler and define its scope
* How to **customize** report settings and frequency
* How to **configure advanced options** like notifications and file attachments

***

A **report scheduler** automatically generates and sends reports based on your preferences and settings. Follow the steps below to create and customize a scheduled report:

1. **Access the Report Scheduler**: Under **General Settings**, locate the **Report Scheduler** section.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/a9b6c3c854c5d92c05aa9d69c9500982059b0676866e36425974fc95942ccf9e-image.png" />

<br />

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/e7b1033655e35aef78e3882c67348762434347a99232dff6f3f408683e5fccd3-image.png" />

2. **Click “Add new.”**

A new window will open for setting up your report scheduler.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/f81330fa9506bf567537b1ff4099bc2d116537d407ff993e1a39d53c23c579af-image.png" />

3. **Fill in Basic Settings**

* **Report Name**: Identifies your report scheduler in the list of scheduled reports.
* **Customer Report Name**: Appears in the email sent to report recipients.
* **Report Type**: Choose from scan, alert, task, report, device, map, timesheet, or study time.
* **Report Format**: Select HTML or PDF.
* **Report Period**: Specify up to seven days.
* **Report Time Zone**: Choose the time zone to display dates/times.
* **Start Date**: The date when the scheduler begins generating reports.
* **End Date**: The date when the scheduler stops generating reports (or leave blank to run indefinitely).
* **Tag**: (Optional) A label or keyword to categorize your report.
* **Scan Point**: (Optional) Filter the report by a specific location.
* **Work Shift**: (Optional) Filter the report by a particular schedule.

4. **Proceed to Advanced Options**

Click **Next** or **Advanced Options** to configure additional settings.

## Advanced Options

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/98f793c3ce10d7fe1e0b63f27af6ac52056c2b40e1129bf1ca30442efcee30b6-image.png" />

* **Notify if No Records Were Found**: Enable or disable an email notification when no data is present in the report.
* **Custom Logo**: Upload an image file to display in the report header.
* **Group by Device**: Organize the report by the devices that collected the data.
* **Order**: Choose ascending or descending order based on the date/time of data.
* **Order by**: Select **Upload Time** or **Submit Time** for data sorting criteria.
* **Recurrence**: Pick once, daily, or weekly for how often the report should be generated.
* **Report Creation Time**: Set the time of day for generating and sending reports.
* **Start Time**: Choose the beginning time of the report period.
* **End Time**: Choose the finishing time of the report period.
* **Report to Email Address**: Specify the email address(es) to receive the report.
* **Send a Copy**: Enter additional email address(es) to receive copies.
* **Email Subject**: Provide the subject line for the email carrying the report.
* **Email Body**: Provide the body text for the email.

When you have completed these steps and settings, **click “Save”** to create your scheduled report. The system will then automatically generate and send the report according to your defined parameters.