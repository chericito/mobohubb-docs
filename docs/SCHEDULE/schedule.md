---
title: 'Schedule: Add, Edit and Delete Schedules'
excerpt: >-
  Learn how to create, edit, and delete **Schedules** in **mobohubb**, enabling
  you to assign jobs or shifts to users, configure time-off requests, manage
  shift replacements, and set notifications for various scheduling events.
deprecated: false
hidden: false
metadata:
  robots: index
next:
  pages:
    - slug: schedule-shifts
      title: 'Schedule: Shifts'
      type: basic
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

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/2e21f2fc0ea1df4bf19ec02338766b0321a2f96bf775b0fd8bcba7affebc6fea-image.png" />

   <br />
4. **Click** **“Add new”.**

<Image align="center" className="border" border={true} src="https://files.readme.io/c6bb82e57968d884ff8bdb87c076709d4f465fe8825e370a87defb30d7bc49fc-image.png" />

5. A new configuration menu will appear.

<Image align="center" className="border" border={true} src="https://files.readme.io/0c5c7c4f187101facffa7de8ed578f7ba0f59e6fc7ee98973e3fd5ccf015a247-Screenshot_2025-05-09_at_5.36.56_PM.png" />

<br />

### General Tab

* **Name**: Specify the schedule’s name.
* **Description**: Provide a brief overview of the schedule’s purpose.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/8ffd922598667f1a0650bd44289fa72142e7df64b2bbb8aee03ade227f9a5188-image.png" />

* **Users**: Add users by pressing the "**Add Users**" button, checking boxes in the **“Assign users”** window, and pressing "**Add**".

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/7c13e02e19be26c4e21692a9a91210148fc4e1b2240351004fc9503c6be270a4-image.png" />

* **Admin User**: Designate an administrator for this schedule.

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/d21dc27428c7409b623f3ff0d8fc8dda9ed705cf8413ea29482a573e62312f11-image.png" />

* **Location**: Pick a location using the interactive map or by typing an address.

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/ba9e466ddab5e222b29fad6d892edfa4defbbf6c4181f2a0c79e2442cfd33082-image.png" />

* **Active**: Check to mark the schedule as “active".

Press "**Save**" to continue to the next tab.

### Mobile Settings Tab

#### Requests (Time off, Claim shift, Replacement)

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/cd0bfb3c479a2255e34931439908109fe9af556fb91907d8a6687365769a5486-image.png" />

<br />

* **Time off** requests:
  * Check/uncheck to enable users’ time-off requests.
  * **Request type**: A label for the request (e.g., “Vacation”).
  * **Category**: For instance, “Emergency” or “Regular Absence.”
  * **Report minimum**: Minimum notice before requesting.
  * **Paid or Unpaid**: Determines compensation.
  * **Requires admin approval**: If checked, an admin must confirm before the request is valid.
* **Shift Replacement**:
  * **Enable** shift replacement request.
  * **Replacement requires admin approval**: If checked, admin must confirm.
* **Claim Shifts**:
  * **Enable** users to claim shifts.
  * **Time window**: Days/hours/minutes before the shift when claims are no longer allowed.
  * **Claim requires admin approval**: If checked, admin must confirm claims.

#### Check-in / Checkout

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/39998c48d42cf5e9c104b6bb4c615cff1792c10ad46a7d6cb73ba01b2aaa5fd7-image.png" />

* **Allow** users to check in via clock in/out in the mobile app.
* Or **automatically** start/end the shift when the scheduled time arrives.

**Save** your changes after setting these fields.

### Default Values Tab

<Image align="center" className="border" border={true} src="https://files.readme.io/acfc7d4e2ad93a03d38e4e59b9ff9bd0bec428d1794a12be707da44ea22f58ea-image.png" />

* **Work Schedule**:
  * **Max hours per user per week**: Enter a number to limit weekly hours.
  * **Max hours per user per day**: Limit daily hours.
  * **Max hour enforcement**: Prevents adding shifts that exceed these values.

Click **Save** to confirm.

### Notification Tab

Configure how **portal users** (administrators) and **mobile users** (employees) receive alerts about schedule events. For each event, check or uncheck to send **Email**, **SMS**, or **push notifications**:

#### Portal Users (Admins)

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/a3df013bd445323e3058a1531901ea604b2b068d527eace7d49980226989772f-image.png" />

* User has accepted/declined a shift
* User missed a shift
* User claimed/unclaimed a shift
* User requested time off, a shift replacement, or checked in to a shift
* Reminders for users failing to accept shifts or check in on time

#### Mobile Users

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/b47767bb6a66b33f2bd7e9e052749cc42520de225170cc332840dfddaf416f91-image.png" />

* Shift was published/removed/edited
* Request approved/rejected
* Claim approved/rejected
* User did not check in or missed a shift
* User did not accept a shift in time

When done, **click** **“Save.”**

## Add Multiple Users

In **mobohubb**, only users already associated with the schedule can be assigned shifts. If you need to include more individuals in a particular schedule, follow the steps below:

1. **Open** the **scheduler**.

2. **Click** the **“Add New”** button within the scheduler interface.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/ce1d1f8697f6ff455d164f8b84a893f200d205fc3a30df81f183eaff138d4e1a-image.png" />

3. **Select** **“Add Users to the Schedule.”**
4. **Check** the users you want to include.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/cbf7a55cf48e4b841fc46dbf586518ae9b588bb97aff58e6250b09500f353f57-Screenshot_2025-02-25_at_12.27.22_PM.png" />

<br />

* Use the **search bar** to quickly locate specific names or roles.

3. **Click** **“Add”** to confirm your choices.
4. **Save** your changes to finalize the updated user list..

***

## Edit a Schedule

1. From the Schedules list, **check** the schedule you want to modify; you can use filters to find it quickly.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/f92bc381b7f2a5b9f216d51a42f30d2569268a4e286756ba7f95ac85db938a69-image.png" />

> **Note:** Only one schedule can be edited at a time.

2. **Click** **“Edit”.**
3. **Modify** data in any of the tabs (General, Mobile Settings, Default Values, Notification).

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/78a9089268e734d89dbb54ba901c37bfc6b98efa61d3eacde3a20b74b25e989f-image.png" />

4. **Save** and **Close** when finished.

***

## Delete a Schedule

You can only delete schedules that have no data records. This prevents losing critical information.

<Image align="center" className="border" border={true} src="https://files.readme.io/1c95b182238e292a219ce61eb6e1cf4be629fd04768a1b798321ad95cbe79bc7-image.png" />

<br />

1. From the Schedules list, **check** the schedule(s) you want to remove.
2. **Click** **“Delete”**
3. **Confirm** your choice. The schedule is discarded if it’s empty.

If the schedule contains records, the system won’t let you delete it. You can either modify or archive it to preserve essential data.

***