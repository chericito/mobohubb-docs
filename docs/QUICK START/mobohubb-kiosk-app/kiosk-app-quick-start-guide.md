---
title: 'Kiosk: Site Administrator Quick Start Guide'
deprecated: false
hidden: false
metadata:
  robots: index
---
### Metadata Description

Learn how to set up and manage the **Kiosk** feature in mobohubb, designed for Site Administrators. This comprehensive guide walks you through configuring the kiosk for each site, setting up user PINs and timers, and managing timesheet and activity follow-up.

### In This Guide You'll Learn

* How to set up the Kiosk feature for your sites
* How to configure Timesheet options, breaks, and user PIN/timer settings
* How to log in to the kiosk and change sites as needed

# Kiosk: Site Administrator Quick Start Guide

This guide will walk you through the initial steps and general workflow for setting up and managing the Kiosk feature on a tablet or iPad. The Kiosk app in mobohubb is used to establish physical check-in points where employees can manually clock in, clock out, and manage their break times.

***

## Configuration

### Set Up the Feature

To set up Kiosk for your sites, note that this is a **site-based configuration**. You must manually activate the kiosk feature for each site.

1. Go to **Site Administration** under the General Settings page.
2. Select the site for which you want to activate the feature.
3. In the Site Information screen, locate the **"Kiosk"** section. Here you can:
   * **Enable Kiosk**: Activate or deactivate the feature for this site.
   * **Set the Kiosk Timer**: Define the amount of time (default is 10 seconds) that employees have to enter their PIN and select options. (If you set a custom timer, ensure the checkbox is marked; otherwise, the timer remains at 10 seconds.)
4. Click the **"Save"** button to apply your changes.
5. Repeat this process for each site as needed.

### Timesheet Config

If you want Kiosk to automatically capture an image of the person checking in/out or managing breaks, activate this option under **Mobile Configuration** in Site Management. This setting will add a photo to the timesheet records.

### Breaks

Ensure that manual breaks are enabled in the site settings under Mobile Configuration. Here you can set whether Rest and Lunch breaks are paid or unpaid and establish a timer for each.

***

## Configure PIN and Timer for Each User

1. Navigate to **Site Administration** and then to **Users**.
2. Select a user from the list and go to their **Security** screen.
3. Under the **User PIN** section, you can either auto-populate a PIN or manually enter one.
4. Similarly, set a custom timer for that user (default is 10 seconds if unmarked; marking and setting a value changes the timer accordingly).
5. Save your changes and repeat for each user as necessary.

***

## Timesheet & Activity Follow Up

After configuring Kiosk, use the **Timesheet** feature to monitor employee activity. This section lets you review clock in/clock out records, view shift details, and track overall activity. For a detailed explanation, refer to our dedicated Timesheet guide.

***

## Log in and Setup Your Site's Kiosk

<Accordion title="Prerequisites" icon="fa-info-circle">
  The Kiosk login is intended for **Site Administrators** only. Ensure you have the proper credentials before proceeding.
</Accordion>

To log in to the Kiosk, follow these steps:

<Tabs>
  <Tab title="Login">
    Enter your **Site Administrator** credentials on the Kiosk login screen and press **"Login"**.

    ![](https://files.readme.io/c11a08951425427b78c9cc87e9936bfe157dacb1828700d61fa064a7dd84ded3-Screenshot_20250218_155732_mobohubb_kiosk.png)
  </Tab>

  <Tab title="Select Site">
    After logging in, select the site you wish to manage. Only sites that have been set as active for Kiosk by the Site Administrator will appear. Use the search bar if the list is long.

    ![](https://files.readme.io/ffb015e64f1090d165a220faaf676851fa73c2828feefc795949d8d648449b77-Screenshot_20250218_162126_mobohubb_kiosk.jpg)
  </Tab>

  <Tab title="Check-In">
    Once a site is selected, employees can enter their **PIN** to check in, check out, and manage break times.

    ![](https://files.readme.io/5c481143e77f2c2c43e7fc3442125dd2bddc7f992f47bcdac9a3dbccb408a96c-Screenshot_20250218_162156_mobohubb_kiosk.jpg)
  </Tab>
</Tabs>

## Changing Sites

To change sites in the Kiosk App:

1. Enter the **PIN 999999** to trigger the exit process for the current site.
2. Confirm the exit when prompted.
3. You can then select a new site from the list.

![Change Site Prompt](https://files.readme.io/b05b6315b30abfcfbbaf2d0f535054c5bd49df7e88e0fd2663cc3eda140e1669-image.png)

Once the new site is selected, employees can resume using the Kiosk for check-in, check-out, and break management.

This guide will guide you through the first steps and general workflow to set up and manage the initial log-in to Kiosk through a tablet/iPad for your employees/users.

Kiosk is a mobohubb app for Ipad and Tablet that allow your company to set up physical points where employees/users can manually check-in checkout and manage their break times.

# Configuration

## Set up the feature

To set up Kiosk for your sites, it's important to be aware that this a site-based configuration, meaning that you will have to manually activate this feature for each site.

Go to "Site Administration", under the general settings page.

Select the site for which you want to activate the feature.

In the Site Information screen, there will be a section called "Kiosk", in which you can enable the feature for this specific site and set an authentication timer for each user checking in-out and managing their break times.

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/681e83e0713496cf62313d4e68d9dae2f61678c62488c4dbeceefffa50556ad1-image.png" />

1. **Enable Kiosk:** This will activate-deactivate the feature for this specific site.
2. **Set the Kiosk timer to**: If enabled, you can set a specific timer for employees/user to fill in the required data (PIN and options selection) in the app. By default, the timer is set to 10 seconds, after which the process will be terminated and the employee/user must start again. If left unmarked, the timer will always be 10 seconds. If marked and set for a specific timer, e.g. 20 seconds, the timer will be 20 seconds. If you set 20 seconds, but you leave it unmarked, the timer will still be 10 seconds. Note: This timer can also be user-based configured. Learn how.

Make sure to save you changes using the "Save" button.

Repeat the process for each site.

### Timesheet Config

If you want Kiosk to automatically take a picture of the person checking-in out and managing their breaks, you can activate this feature under the Mobile Configuration in the Site Management menu.

<Image align="center" className="border" border={true} src="https://files.readme.io/642254e486c79122aef1a3163be4b51417abea7be0c02c9f53b8ce9363a15868-image.png" />

Activate the checkbox "Activate personnel image in the timesheet".

### Breaks

Make sure to have the manual breaks enabled in the site, also under mobile configurations. You can set whether the Rest and Lunch are paid or not paid, and also establish a timer for each one.

<Image align="center" className="border" border={true} src="https://files.readme.io/4afdd7cdd699c2623c7e063abc426077727a54128feccbcce47f7d43a0d4b5b0-image.png" />

## Configure PIN and Timer for Each User

To configure the pin and timer for each user, navigate to site administration and to "Users".

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/d9d5e61963e617d185341a4a7ea5eb96c86af39dfe9ea93828aefb14f5707237-image.png" />

Select one user from the list and navigate to the Security screen.

Under the User PIN section you can auto populate a PIN for this specific user or manually write one.

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/8a12dd1a7fe56f457f3c7f7354472a43ea4d0cc0f51107dfc59f98046f002cc5-Screenshot_2025-02-18_at_7.34.12_PM.png" />

You can also easily find each user's PIN in the Users list.

Similarly to the timer tool in Site Administration for each site, you can set a custom timer for each user.

If enabled, you can set a specific timer for employees/user to fill in the required data (PIN and options selection) in the app. By default, the timer is set to 10 seconds, after which the process will be terminated and the employee/user must start again. If left unmarked, the timer will always be 10 seconds. If marked and set for a specific timer, e.g. 20 seconds, the timer will be 20 seconds. If you set it to 20 seconds, but you leave it unmarked, the timer will still be 10 seconds.

Save changes and repeat for each user.

## Timesheet & Activity Follow Up

<Image align="center" className="border" border={true} src="https://files.readme.io/242cb51b42550aba352885c649b3161fe2efeadee91a73f6cbe2eb4d4fd2b7c9-3F05309C-314D-4252-9A4D-3A0DA47B63E2.png" />

Use the Timesheet and all its tools to follow up on your team activity while using Kiosk. You can find a comprehensive guide on [Timesheet](https://mobohubb.readme.io/docs/timesheet#/) here.

# Log in and Setup Your Site's Kiosk

<Accordion title="Prerequisites" icon="fa-info-circle">
  The Kiosk login is intended for **Site Administrators** only.
</Accordion>

To log in to the Kiosk, enter your Site Administrator credentials and press **"Login"**.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/c11a08951425427b78c9cc87e9936bfe157dacb1828700d61fa064a7dd84ded3-Screenshot_20250218_155732_mobohubb_kiosk.png" />

After logging in, select one of the sites. Only the sites previously set as active for Kiosk by the Site Administrator will be available. Use the search bar if the list is long to find a specific site.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/ffb015e64f1090d165a220faaf676851fa73c2828feefc795949d8d648449b77-Screenshot_20250218_162126_mobohubb_kiosk.jpg" />

Once a site is selected for the session, all employees/users can then enter their **PIN** to check in, check out, and manage break times.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/b05b6315b30abfcfbbaf2d0f535054c5bd49df7e88e0fd2663cc3eda140e1669-image.png" />

## Changing Sites

To easily change sites in the Kiosk App, you must enter the **PIN 999999**. The system will prompt you to confirm you want to exit the current site.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/b05b6315b30abfcfbbaf2d0f535054c5bd49df7e88e0fd2663cc3eda140e1669-image.png" />

You can then select a new site from the list.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/ffb015e64f1090d165a220faaf676851fa73c2828feefc795949d8d648449b77-Screenshot_20250218_162126_mobohubb_kiosk.jpg" />