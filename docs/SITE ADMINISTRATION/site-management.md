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

# Site Management Configuration

## Site Information

The **Site Information** interface allows you to manage sites for your organization. Each site can be configured with the following details:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/730285c06de8d58bd99fd2de26f7b292276e45863ee4de5550a1ed89b35a59a6-593F2136-23D5-4ED5-A983-F6E393D50D71.png" />

* **Site Name**: A unique name to identify the site.
* **Site Path**: The site path represents the hierarchical position of the site within the organizational structure. Instead of indicating a physical address or directory on the server, it shows the level of the site and its relationship to other sites or child sites within the organization.
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