---
title: 'Kiosk: Site Administrator Quick Start Guide'
excerpt: >-
  Learn how to set up and manage the **Kiosk** feature in **mobohubb**, enabling
  employees to clock in/out and manage breaks on a tablet or iPad. This guide
  explains how to configure each site, assign user PINs/timers, and monitor
  timesheets for comprehensive attendance management.
deprecated: false
hidden: false
metadata:
  robots: index
---
**In this guide you'll learn**

* How to **activate and configure** Kiosk for each site
* How to **customize** Timesheet options and break settings
* How to **assign** user PINs and individual timers
* How **Site Administrators** log in to the Kiosk and switch between sites

# Kiosk: Site Administrator Quick Start Guide

The **Kiosk** app in **mobohubb** is used to create a physical check-in station, where employees can manually clock in, clock out, and manage their breaks using a dedicated tablet or iPad.

***

## Configuration

### 1. Set Up the Feature

Kiosk settings are **site-based**, so each site must be enabled separately:

1. Go to **Site Administration** under **General Settings**.
2. Select the site to enable the Kiosk.
3. On the **Site Information** screen, locate the **“Kiosk”** section:

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/681e83e0713496cf62313d4e68d9dae2f61678c62488c4dbeceefffa50556ad1-image.png" />

* **Enable Kiosk**: Activates the Kiosk for this site.
* **Set the Kiosk Timer**: If checked, overrides the default 10-second timer. If unmarked, it remains 10 seconds no matter what you input.

4. Click **Save** to finalize.
5. Repeat for each site you want to use with Kiosk.

### 2) Timesheet Config

If you want the Kiosk to capture an **image** of each user at clock in/out or break, enable **“Activate personnel image in the timesheet”** under **Mobile Configuration** in **Site Management**:

<img src="https://files.readme.io/642254e486c79122aef1a3163be4b51417abea7be0c02c9f53b8ce9363a15868-image.png" className="border" border={true} width="50%" />

### 3. Breaks

Enable manual breaks under **Mobile Configuration**, deciding if Rest/Lunch breaks are **paid or unpaid** and setting timers for each:

<img src="https://files.readme.io/4afdd7cdd699c2623c7e063abc426077727a54128feccbcce47f7d43a0d4b5b0-image.png" className="border" border={true} width="50%" />

***

## Configure PIN and Timer for Each User

1. Navigate to **Site Administration**, then **Users**.
2. Select a user and open **Security**.
3. In **User PIN**, choose to auto-generate or enter a PIN manually.
4. If you wish to override the default 10-second timer for that user, check the timer box and enter a value. If unmarked, the timer remains 10 seconds, ignoring any number you typed.
5. Click **Save**. Repeat for additional users.

***

## Timesheet & Activity Follow Up

Use **Timesheet** to monitor who clocked in/out and how breaks are used. For details on pay calculations or planned vs. worked hours, refer to our [Timesheet Guide](https://mobohubb.readme.io/docs/timesheet#/).

***

# Log in and Set Up Your Site’s Kiosk

### Prerequisites

The Kiosk login is designed for **Site Administrators** only. Ensure you have the proper credentials before proceeding.

<Tabs>
  <Tab title="Login">
    <p>
      Enter your <strong>Site Administrator</strong> credentials in the Kiosk app and press <em>“Login.”</em>
    </p>

    <img src="https://files.readme.io/c11a08951425427b78c9cc87e9936bfe157dacb1828700d61fa064a7dd84ded3-Screenshot_20250218_155732_mobohubb_kiosk.png" width="25%" />
  </Tab>

  <Tab title="Select Site">
    <p>
      After logging in, choose one of the <strong>sites</strong> you have enabled for Kiosk. If the list is long, use the search bar to find it quickly.
    </p>

    <img src="https://files.readme.io/ffb015e64f1090d165a220faaf676851fa73c2828feefc795949d8d648449b77-Screenshot_20250218_162126_mobohubb_kiosk.jpg" width="25%" />
  </Tab>

  <Tab title="Check-In">
    <p>
      Once a site is selected, employees can enter their <strong>PIN</strong> to clock in, clock out, and manage breaks.
    </p>

    <img src="https://files.readme.io/5c481143e77f2c2c43e7fc3442125dd2bddc7f992f47bcdac9a3dbccb408a96c-Screenshot_20250218_162156_mobohubb_kiosk.jpg" width="25%" />
  </Tab>
</Tabs>

## Changing Sites

To exit the current site and switch to another:

1. Enter **PIN 999999**.
2. Confirm exit when prompted.
3. Select a new site from the list.

Employees can continue to clock in/out under the newly selected site.

<img src="https://files.readme.io/b05b6315b30abfcfbbaf2d0f535054c5bd49df7e88e0fd2663cc3eda140e1669-image.png" width="50%" />

By following these steps and configurations, you ensure a smooth, secure Kiosk setup for your organization, allowing employees to manage attendance and breaks under controlled, auditable conditions.