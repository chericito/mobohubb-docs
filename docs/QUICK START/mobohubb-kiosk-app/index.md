---
title: mobohubb Kiosk App
excerpt: >-
  Discover how **mobohubb Kiosk** transforms a tablet or iPad into a physical
  check-in station for employees, simplifying time tracking and break
  management. This guide outlines kiosk setup, user PIN assignments, site
  switching, and integration with **Timesheet** for complete attendance
  oversight.
deprecated: false
hidden: false
metadata:
  robots: index
---
The **Kiosk** app in **mobohubb** creates a physical check-in station where employees can manually clock in, clock out, and manage breaks using a dedicated tablet or iPad. By providing a communal device, your organization can centralize attendance records and ensure users follow consistent timekeeping procedures. The kiosk relies on site-based configurations, unique PINs for each user, and optional camera captures for further verification.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/59365653bddebc79fc35eb1e5cac7fdf9faca63394e9316122d44f14c7890ddc-Screenshot_20250218_162156_mobohubb_kiosk.jpg" />

Once enabled for a specific site, the kiosk displays a login screen reserved for Site Administrators. After logging in, you can choose which site to manage. The kiosk allows employees to type in their PIN and record work hours by clocking in and out, and breaks. If your site requires photos at clock in/out, employees can capture an image to confirm their identity. The kiosk also supports user-defined break durations and pay rates, seamlessly integrating with the **[Timesheet](https://mobohubb.readme.io/docs/timesheet#/)** feature to track and reconcile total hours worked.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/60b2f59addcbdf12f3a49b6160c5c8d96d7780957176c2f88210471d9ac414c5-Diseno_sin_titulo.png" />

Behind the scenes, all clock in/out events entered through the kiosk sync to the **mobohubb** portal, storing data in your [timesheet](https://mobohubb.readme.io/docs/timesheet#/).

By dedicating a tablet or iPad to this single function, employees won’t need individual mobile devices to clock in and out. Instead, they approach the Kiosk at the start, during, or at the end of their shifts, enter a short PIN, and confirm any relevant break times—making it an accessible, low-barrier approach to comprehensive workforce management in **mobohubb**.