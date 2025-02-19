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

***

The **Kiosk** app in **mobohubb** is used to create a physical check-in station, where employees can manually clock in, clock out, and manage their breaks using a dedicated tablet or iPad.

***

## Configuration

### Set Up the Feature

Kiosk settings are **site-based**, so each site must be enabled separately:

1. Go to **Site Administration** under **General Settings**.
2. Select the site to enable the Kiosk.
3. On the **Site Information** screen, locate the **“Kiosk”** section:

<Image align="center" className="border" border={true} width="45% " src="https://files.readme.io/39411b3a1a1f63876b11890845d5ba6db82978792f8a593add35c6c8bba70a67-94C147D3-865A-4036-B251-D2453A36E882.png" />

* **Enable Kiosk**: Activates the Kiosk for this site.
* **Set the Kiosk Timer**: If checked, overrides the default 10-second timer. If unmarked, it remains 10 seconds no matter what you input.

4. Click **Save** to finalize.
5. **Repeat** for each site you want to use with Kiosk.

### Timesheet Config

If you want the Kiosk to capture an **image** of each user at clock in/out or break, enable **“Activate personnel image in the timesheet”** under **Mobile Configuration** in **Site Management**:

<img src="https://files.readme.io/642254e486c79122aef1a3163be4b51417abea7be0c02c9f53b8ce9363a15868-image.png" className="border" border={true} width="50%" />

### Breaks

Enable manual breaks under **Mobile Configuration**, deciding if Rest/Lunch breaks are **paid or unpaid** and setting timers for each:

<img src="https://files.readme.io/4afdd7cdd699c2623c7e063abc426077727a54128feccbcce47f7d43a0d4b5b0-image.png" className="border" border={true} width="50%" />

***

## Configure PIN and Timer for Each User

1. Navigate to **Site Administration**, then **Users**.

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/27f8d63959e44db5e21d1695d84efccc37e821dbb88b177582429ee0620594c2-image.png" />

2. **Select** a user from the list. **Notice** that there is a new column named "PIN". This column appears only when Kiosk is activated in this specific site.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/de4d7d7d5dce717f1f2f93e7afb7ede2bb18265ccfd3ca2c4741a655d3f31964-image.png" />

3. From the user configuration menu, navigate to **Security**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/640e59f8700008445f3ed2211ee9b1e64242a03c6da695f150b4450ae54d89c5-image.png" />

3. In **User PIN**, choose to auto-generate or enter a PIN manually.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/21cf45361fde31487b6d8b3dae830bb2c6ab1a18c16c5e29e774b3c7c56837f7-image.png" />

If you wish to override the default 10-second timer for that user, check the timer box and enter a value. If unmarked, the timer remains 10 seconds, ignoring any number you typed.

3. Click **Save**. Repeat for additional users.

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

    <img src="https://files.readme.io/c11a08951425427b78c9cc87e9936bfe157dacb1828700d61fa064a7dd84ded3-Screenshot_20250218_155732_mobohubb_kiosk.png" className="border" border={true} width="25%" />
  </Tab>

  <Tab title="Select Site">
    <p>
      After logging in, choose one of the <strong>sites</strong> you have enabled for Kiosk. If the list is long, use the search bar to find it quickly.
    </p>

    <img src="https://files.readme.io/ffb015e64f1090d165a220faaf676851fa73c2828feefc795949d8d648449b77-Screenshot_20250218_162126_mobohubb_kiosk.jpg" className="border" border={true} width="25%" />
  </Tab>

  <Tab title="Check-In">
    <p>
      Once a site is selected, employees can enter their <strong>PIN</strong> to clock in, clock out, and manage breaks.
    </p>

    <img src="https://files.readme.io/5c481143e77f2c2c43e7fc3442125dd2bddc7f992f47bcdac9a3dbccb408a96c-Screenshot_20250218_162156_mobohubb_kiosk.jpg" className="border" border={true} width="25%" />
  </Tab>
</Tabs>

## Changing Sites

To exit the current site and switch to another:

1. Enter **PIN 999999**.
2. Confirm exit when prompted.
3. Select a new site from the list.

Employees can continue to clock in/out under the newly selected site.

<img src="https://files.readme.io/b05b6315b30abfcfbbaf2d0f535054c5bd49df7e88e0fd2663cc3eda140e1669-image.png" className="border" border={true} width="25%" />

By following these steps and configurations, you ensure a smooth, secure Kiosk setup for your organization, allowing employees to manage attendance and breaks under controlled, auditable conditions.