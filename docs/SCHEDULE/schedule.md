---
title: Schedule
excerpt: >-
  Learn how to create, edit, and delete **Schedules** in **mobohubb**, enabling
  you to assign jobs or shifts to users, configure time-off requests, manage
  shift replacements, and set notifications for various scheduling events.
deprecated: false
hidden: false
metadata:
  robots: index
---
**In this guide you'll learn**

* How to **add a new schedule**, **edit existing schedules**, **configure user acceptance**, **manage notifications**, and **delete schedules** safely.

***

The **Schedule** feature in **mobohubb** helps you assign jobs or shifts to each user, monitor attendance, and ensure proper resource allocation. A well-structured schedule provides a clear overview of who is working when, maintains good customer service, and maximizes operational efficiency.

***

## Add a Schedule

1. **Navigate** to the portal’s top menu.
2. **Go** to **“General Settings.”**
   * Click **Settings** in the top menu to find various organization configuration options.
3. **Locate** **“Schedule”.**
   * Within the **Configuration** area, select **“Schedule”.**
4. **Click** **“Add new”.**
   * You’ll see the **General**, **Mobile Settings**, **Default Values**, and **Notification** tabs.

### General Tab

* **Name**: Specify the schedule’s name.
* **Description**: Provide a brief overview of the schedule’s purpose.
* **Users**: Add users by checking boxes in the **“Assign users”** tab.
* **Admin User**: Designate an administrator for this schedule.
* **Location**: Pick a location using the interactive map or by typing an address.
* **Active**: Check to mark the schedule as “activated.”
* **Save** your changes.

### Mobile Settings Tab

* **Accept/Reject**: Configure the time window for users to accept or reject shifts.
  * If users fail to accept or reject within this timeframe, alerts are generated for admins to find alternatives.
* **Enable users to accept/reject shifts**: If checked, users can confirm or decline a shift in the app.
* **Time Window**: Set days, hours, or minutes before the shift starts for acceptance or rejection.

#### Requests (Time off, Claim shift, Replacement)

* **Time off** requests:
  * Check/uncheck to enable users’ time-off requests.
  * **Request type**: A label for the request (e.g., “Vacation”).
  * **Category**: For instance, “Emergency” or “Regular Absence.”
  * **Report minimum**: Minimum notice before requesting.
  * **Paid or Unpaid**: Determines compensation handling in cost calculations.
  * **Requires admin approval**: If checked, an admin must confirm before the request is valid.
* **Shift Replacement**:
  * **Enable** shift replacement request.
  * **Replacement requires admin approval**: If checked, admin must confirm.
* **Claim Shifts**:
  * **Enable** users to claim shifts.
  * **Time window**: Days/hours/minutes before the shift when claims are no longer allowed.
  * **Claim requires admin approval**: If checked, admin must confirm claims.
* **Check-in / Checkout**:
  * **Allow** users to check in via clock in/out in the mobile app.
  * Or **automatically** start/end the shift when the scheduled time arrives.

**Save** your changes after setting these fields.

### Default Values Tab

* **Time Settings**:
  * **Week starts**: Choose the first day of your workweek.
  * **Work hours (from/to)**: Specify the typical start/end times.
  * **Default shift length**: How many hours per day.
* **Work Schedule**:
  * **Max hours per user per week**: Enter a number to limit weekly hours.
  * **Max hours per user per day**: Limit daily hours.
  * **Max hour enforcement**: Prevents adding shifts that exceed these values.

Click **Save** to confirm.

### Notification Tab

Configure how **portal users** (administrators) and **mobile users** (employees) receive alerts about schedule events. For each event, check or uncheck to send **Email**, **SMS**, or **push notifications**:

#### Portal Users (Admins)

* User has accepted/declined a shift
* User missed a shift
* User claimed/unclaimed a shift
* User requested time off, a shift replacement, or checked in to a shift
* Reminders for users failing to accept shifts or check in on time

#### Mobile Users

* Shift was published/removed/edited
* Request approved/rejected
* Claim approved/rejected
* User did not check in or missed a shift
* User did not accept a shift in time

When done, **click** **“Save.”**

***

## Edit a Schedule

1. **Open** the portal’s top menu, go to **“General Settings.”**
2. In the **Configuration** area, select **“Scheduling.”**
3. **Check** the schedule you want to modify; you can use filters to find it quickly.
   * Note: Only one schedule can be edited at a time.
4. **Click** **“Edit.”**
5. **Modify** data in any of the tabs (General, Mobile Settings, Default Values, Notification).
6. **Save** and **Close** when finished.

***

## Delete a Schedule

You can only delete schedules that have no data records. This prevents losing critical information.

1. **Go** to **“General Settings.”**
2. In the **Configuration** area, select **“Scheduling.”**
3. **Check** the schedule(s) you want to remove.
4. **Click** **“Delete.”**
5. **Confirm** your choice. The schedule is discarded if it’s empty.

If the schedule contains records, the system won’t let you delete it. You can either modify or archive it to preserve essential data.

***

That’s how you **add**, **edit**, and **remove** schedules in mobohubb, allowing you to manage shifts, user acceptance, time-off requests, and notifications to ensure smooth operations.