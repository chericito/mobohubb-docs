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

1. Go to **Site Administration** under **General Settings**, and select **Site Management**.

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/234b2efc4b2d64dabf1ad620941ed2061d098cf9141679b606c54144e307feed-8C799BDC-0143-4BE5-A7C3-1DE1B81822AF.png" />

2. Select the site to enable the Kiosk.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/d0c819821d5ba0886fbf44f07aa7dc23422b3b929ed99639d7fb93932167ec4a-5EA6A014-730A-4BD9-86DE-1DFB7F0A2E83.png" />

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

If you wish to override the default timer for that user, check the timer box and enter a value. If unmarked, the timer remains the default set for this site, ignoring any number you typed.

3. Click **Save**. Repeat for additional users.

***

## Timesheet & Activity Follow Up

Use **Timesheet** to monitor who clocked in/out and how breaks are used. For details on pay calculations or planned vs. worked hours, refer to our [Timesheet Guide](https://mobohubb.readme.io/docs/timesheet#/).

***

# Log in and Set Up Your Site’s Kiosk

### Prerequisites

The **Kiosk** login is intended for **Site Managers**, **Organization Managers**, and **Editors** only (Refer to our Security Groups management section).

<Tabs>
  <Tab title="Login">
    <p>
      Enter your <strong>Site Administrator</strong> credentials in the Kiosk app and press <em>“Login.”</em>
    </p>

    <img src="https://files.readme.io/a9d825738e38774965b900ceaf310462cfd66793ff8f8ee58960dc2365fe9e61-Kiosk_1.png" className="border" border={true} width="25%" />
  </Tab>

  <Tab title="Select Site">
    <p>
      After logging in, choose one of the <strong>sites</strong> you have enabled for Kiosk. If the list is long, use the search bar to find it quickly.
    </p>

    <img src="https://files.readme.io/22c417ff4b161ad75445ccb4e662fd523764e21b815396f218f9f61e29759883-Kiosk_2.png" className="border" border={true} width="25%" />
  </Tab>

  <Tab title="Check-In">
    <p>
      Once a site is selected, employees can enter their <strong>PIN</strong> to clock in, clock out, and manage breaks.
    </p>

    <img src="https://files.readme.io/8e904d641a23b7c9f5e57b90e52ed06387f288ed1404818b0ab6480dee0f5aec-Kiosk_3.png" className="border" border={true} width="25%" />
  </Tab>
</Tabs>

# Changing Sites

After configuring kiosk mode on your device, you may need to switch between sites quickly. **mobohubb** makes it easy to exit the current site and select a new one, ensuring seamless management across multiple work locations. This flexibility is especially useful when your organization operates in various sites or when shifts need to be managed differently.

1. **Enter PIN 999999** on the kiosk to initiate the site exit process.
2. **Confirm** the exit when prompted by the system.
3. **Select** a new site from the displayed list.
4. Employees can then continue to clock in, clock out, and manage breaks under the new site's configuration.

By following these steps, you can easily switch between sites as your operational needs change.

<img src="https://files.readme.io/8e904d641a23b7c9f5e57b90e52ed06387f288ed1404818b0ab6480dee0f5aec-Kiosk_3.png" className="border" border={true} width="25%" />

By following these steps and configurations, you ensure a smooth, secure Kiosk setup for your organization, allowing employees to manage attendance and breaks under controlled, auditable conditions.