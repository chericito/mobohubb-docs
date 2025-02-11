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

Site Management is divided into three main sections—**Site Information**, **Site Branding**, and **Mobile Configuration**—each accessible via a tab within the feature.

## Accessing Site Management

<Cards columns={2}>
  <Card title="Step 1" icon="fa-cogs">
    **Go to General Settings**\
    Find "Site Management" under "Site Administration."
  </Card>

  <Card title="Step 2" icon="fa-search">
    **Choose a Site**\
    Select your site from the list or use the search bar to find it.
  </Card>
</Cards>

### Parts

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

## Subscription Types & Site Creation

* **Legacy Subscriptions**: Must request new site creation through mobohubb support.
* **New Subscriptions**: The number of sites you can manage is based on how many mobile app users you have.

Site management helps **onboard staff** and **segment data** across multiple locations, improving organizational structure and efficiency.