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

A **report scheduler** automatically generates and emails reports on a cadence you define.

***

## Add a New Report Scheduler

1. From **General Settings → Report Configuration**, choose **Report Scheduler**.

<Image align="center" width="80% " src="https://files.readme.io/8c4f5707adfc1379b3a9734446bddbf05f51f9394fe0258e27edca7c680e9c03-Screenshot_2025-05-05_at_12.01.45_PM.png" />

2. Click **Add new**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/fe5ef15e962ccae1ab1e77a4aad50642e251077b7f1e50515062d0e5c15975eb-Screenshot_2025-05-05_at_12.03.22_PM.png" />

3. Complete the **Report Scheduler** form.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/1f13f20f8a7c47c8b75b8bdfc6b0474bee253155f2830e117b8580e89e0baf1a-image.png" />

| Field                                      | Purpose                                                                      |
| ------------------------------------------ | ---------------------------------------------------------------------------- |
| **Report name  (Required)**                | Friendly name that appears in the email subject.                             |
| Customer report name                       | Optional alternate label shown inside the report.                            |
| **Report format  (Required)**              | **PDF** (file attachment) or **HTML** (web‑style email).                     |
| **Report type (Required)**                 | Data source: **Scans, Tasks, Forms, Devices, Map, Timesheet, Time Studies**. |
| Scan / Tags                                | Filter by a specific scan point or tag. Leave blank for “all”.               |
| **Report period (Required)**               | Rolling window (Last 2–7 days) or fixed range.                               |
| **Scheduler Start / End Dates (Required)** | Overall lifespan of the scheduler.                                           |
| **Time zone (Required)**                   | Drives when the report runs and which data timestamps are included.          |

***

## Advanced options

Click **Next** (or **Advanced options**) to fine‑tune delivery details.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c151870ddc086330d2105ad150ef9d5ccbf1b45ffb7e18d5b8ca2df142733acb-image.png" />

| Option                    | Description                                                                           |
| ------------------------- | ------------------------------------------------------------------------------------- |
| **Report to (Required)**  | Primary email recipient(s). Separate multiple addresses with commas.                  |
| Report CC                 | Additional recipients.                                                                |
| Send of report            | Local time of day to send.                                                            |
| Subject                   | Overrides the default email subject.                                                  |
| Notify if no records      | Sends an empty‑data alert instead of skipping the email.                              |
| Group by device           | Adds device headers inside the report.                                                |
| Add custom logo           | Upload a PNG/JPG to brand the PDF/HTML header.                                        |
| Report order / Order by   | Sort data **Ascending/Descending** by **Upload Time** or **Submit Time**.             |
| Email body                | Rich‑text (or basic HTML) message shown above the report.                             |
| **Recurrence (Required)** | **Once**, **Daily**, or **Weekly**. Specify how often the report should be generated. |
| Frequency hour            | Hourly cadence (e.g., every 2 h) *only* when Recurrence = Daily or Weekly.            |
| Start / End Time          | Limits data to a daily window (e.g., 07:00–19:00).                                    |

> **Tip:** If you need several daily snapshots (e.g., every 4 hours), set **Recurrence = Daily** and **Frequency hour = 4**.

***

## Save & Activate

Click **Save**. **mobohubb** will now:

1. Generate the report on the schedule you chose.
2. Email it to the addresses provided—PDF attachment or HTML body—until the **End Date** is reached or the scheduler is deactivated.

Need to tweak something later? Open **Report Scheduler**, click the scheduler name, adjust the fields, and **Save** again.