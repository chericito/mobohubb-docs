---
title: Site Management
excerpt: >-
  Manage and configure your organization's sites in **mobohubb**. This
  comprehensive guide walks you through **Site Information**, **Site Branding**,
  and **Mobile Configuration**, helping you tailor each site to your unique
  workflow and visual identity.
deprecated: false
hidden: false
metadata:
  robots: index
---
**In this guide you'll learn**

* How to **access Site Management** and edit a site’s essential details
* How to **customize site branding** or inherit your organization’s branding
* How to **configure mobile app features** for each site (GPS polling, security, timesheets, etc.)

***

**Navigate** to **Settings** → **General Settings** → **Site Management**

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/0af4f4561cbc3fe2db96c149951dfafee6e72f390e11f1e8c798982dbcf3a0b4-43814F16-0A24-4209-96CC-62DB79C3E7E4.png" />

**Select** a **Site** from the list.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/57defea36f372fdce65ac41055860d759abc28e8f8f3470dd40adba8c1923dfd-183E27B7-AFD6-408E-9FFA-241432BA8120.png" />

Site Management is divided into three main sections—**Site Information**, **Site Branding**, and **Mobile Configuration**—each accessible via a tab within the feature.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/efd155f8866944201eea8a4ea966fdf8313f30bc62d6fac6f4b27e76b9c4190d-image.png" />

<br />

<Tabs>
  <Tab title="Site Information">
    Site Information enables you to create and manage sites within your organization. Each site can be configured according to several details. The Site Name is a unique identifier. The Site Path is the address or directory where the site is located on the server. The Type of Site can be security, facilities, janitorial, construction, restaurant, or “other.” The Site Address is where the site or target location is physically located. The Time Zone determines how dates and times are displayed and recorded. Enable Web App Access allows forms to be accessed through [https://mobile.mobohubb.com/](https://mobile.mobohubb.com/). You can activate or deactivate the site without deleting it, and you can select NFC tags or QR codes as the scanning method.

    To update site information, select a site from Site Management, open the Site Information tab, and make any changes to name, description, location, or settings. Save your changes to apply them.
  </Tab>

  <Tab title="Site Branding">
    Site Branding determines whether a site inherits the organization’s branding or has its own design. Disabling “Inherit Settings” allows further customization of description, mobile logo, icon, main logo, date format, time format, theme color, time zone, and the scanning method (QR or NFC). You may also activate or deactivate the site. To modify site branding, open the Branding tab for the chosen site, disable “Inherit Settings” if you need custom branding, adjust the elements, and save your changes.
  </Tab>

  <Tab title="Mobile Configuration">
    Mobile Configuration customizes user interaction with the mobohubb app at each site. GPS Polling periodically queries device GPS for attendance or tracking. Security controls whether users stay logged in or must log in again. Timesheet Configuration records and manages work time, possibly auto clocking out users. Landing Screen Configuration selects a default screen (dashboard, timeclock, tasks, forms, schedule, or scan/NFC), with up to four items in the navbar and the rest under “Additional apps menu.” The More Menu Configuration lets you show or hide items like My Activity, Chat, Knowledge Base, App Info, Support, Offline Work, Map, and Request in the side menu. Panic Configuration activates or deactivates a panic button for emergencies by email, SMS, or call. Sitemap Configuration uploads an image with site details. Breaks define rest intervals and can be automatic, manual, or inactive. To access Mobile Configuration, choose the site in Site Management, open Mobile Configuration, and customize your preferred options. Save any changes.
  </Tab>
</Tabs>

# Site Management Configuration

## Site Information

The **Site Information** interface allows you to create and manage sites for your organization. Each site can be configured with the following details:

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/159405d0bba0b9b119d39c3b0450106a7de4e843682c5a518a78d5ca2032ae27-image.png" />

* **Site Name**: A unique name to identify the site.
* **Site Path**: The address or directory where the site is located on the server.
* **Type of Site**: Security, facilities, janitorial, construction, restaurant, “other,” etc.
* **Site Address**: The geographical location of the site or target audience.
* **Time Zone**: Sets the display and record times for activities on the site.
* **Enable Web App Access**: Grants access to forms through the web at [https://mobile.mobohubb.com/](https://mobile.mobohubb.com/).
* **Activate the Site**: Quickly deactivate or activate the site without deleting its record.
* **Type of Scan**: Chooses between **NFC tags** or **QR codes**.

#### How to Update Site Information

1. Under **Site Management**, locate and **click** the site you wish to modify.
2. In the **Site Information** tab, **review** the fields (site name, description, location, etc.).
3. **Save** your changes to apply them. (You can also **cancel** to discard changes.

## Site Branding

The **Site Branding** tab lets you determine whether to inherit the organization’s branding or customize your own. Disabling “Inherit Settings” allows further personalization of the site’s design:

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/e5a644d8985cd72fe3cc50a0091e9a20b091b24eea8506dbebecd4d54dee2c21-image.png" />

* **Description**: A short text introducing the site’s purpose or value.
* **Logo app mobile**: The graphic symbol shown in the mobile app.
* **Icon**: Displayed when the web app’s menu collapses.
* **Main logo**: Represents the organization on the web portal.
* **Date format**: How dates appear (e.g., dd-mm-yyyy, yyyy-mm-dd, mm-dd-yyyy).
* **Time format**: 12-hour or 24-hour time display.
* **Theme color**: The primary hue in the portal’s graphical interface.
* **Time zone**: Sets how time is displayed based on geographical location.
* **QR codes or NFC tags**: Indicates the scanning method for the site.
* **Activate Site**: Allows you to enable or disable the site.

#### How to Modify Site Branding

1. Under **Site Management**, choose the **site** to modify.
2. **Click** the “Branding” tab.
3. **Disable** “Inherit Settings” if you want custom branding.
4. **Adjust** the branding details (logos, date/time formats, theme color, etc.).
5. **Save** your changes.

## Mobile Configuration

The **Mobile Configuration** tab lets you configure technical aspects of the mobile application for each site, determining how users interact, view data, and manage tasks.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/1552b8d7251124dcbbc5c32a83767c8e416f1bd9b58a5a9f78b41ab31f375fd0-image.png" />

* **GPS Polling**: Periodically queries a device’s GPS for user tracking or attendance. Set the interval in seconds.
* **Security**: Allows users to stay logged in or requires them to log in each time they access mobohubb.
* **Timesheet Configuration**: Records and manages time spent on tasks or projects, including an auto clock-out option.
* **Landing Screen Configuration**: Choose a default screen for the mobile app (dashboard, timeclock, tasks, forms, schedule, or scan/NFC). You can also select up to four items for the navbar; extra items appear under “Additional apps menu.”
* **More Menu Configuration**: Decide which items are visible in the mobile app’s side menu:
  * **My activity**: List of user activities
  * **Chat**: One-on-one communication
  * **Knowledge base**: Organizational guidelines
  * **App info**: App details
  * **Support**: Contact mobohubb assistance
  * **Offline work**: Allows the user to operate without an internet connection, storing data locally until reconnected
  * **Map**: Shows Geo-type tasks
  * **Request**: Lets users request emergency or permit-type requests
* **Panic Configuration**: Allows a panic button to send emergency alerts via email, SMS, or call.
* **Sitemap Configuration**: Upload an image to provide directions or details about the site.
* **Breaks**: Time intervals for rest periods. Options:
  * **Automatic**: Deducts break hours after a set duration
  * **Manual**: Lets users clock in/clock out breaks, paid or unpaid
  * **Inactive**: Disables breaks altogether

#### How to Access Mobile Configurations

1. Under **Site Management**, pick the **site** to modify.
2. Go to the **“Mobile Configuration”** tab.
3. **Customize** your mobile options as needed (GPS polling, timesheet settings, etc.).
4. **Save** changes for each configuration.

> **Note:** Each module within Mobile Configuration may have its own “Save” button—make sure to press it to confirm your edits.

***

**That’s it!** You’ve now explored the **Site Information**, **Site Branding**, and **Mobile Configuration** sections within **Site Management**, giving you a complete overview of how to set up and tailor each site in **mobohubb** to fit your organization’s needs.

## Subscription Types & Site Creation

* **Legacy Subscriptions**: Must request new site creation through mobohubb support.
* **New Subscriptions**: The number of sites you can manage is based on how many mobile app users you have.

Site management helps **onboard staff** and **segment data** across multiple locations, improving organizational structure and efficiency.