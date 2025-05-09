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
**In this guide, you'll learn**

* How to **add a new schedule**, **edit existing schedules**, **configure user acceptance**, **manage notifications**, and **delete schedules** safely.

***

The **Schedule** feature in **mobohubb** allows you to assign jobs or shifts to each user, monitor attendance, and ensure proper resource allocation. A well-organized schedule provides a clear overview of who is working when, helps maintain high customer service standards, and maximizes operational efficiency.

***

## Add a Schedule

1. **Navigate to the Portal’s Top Menu** and select **Settings** from the dropdown.

<Image align="center" className="border" border={true} width="80%" src="https://files.readme.io/84271ddfd277b67b32b0addce24e9e728b4ac48763aa0b92a63a0cf8c52f9a50-Screenshot_2025-04-03_at_12.41.34_PM.png" />

2. From the **Configuration** section, select **Scheduling**.

<Image align="center" className="border" border={true} width="80%" src="https://files.readme.io/2e21f2fc0ea1df4bf19ec02338766b0321a2f96bf775b0fd8bcba7affebc6fea-image.png" />

3. **Click** **“Add new”**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c6bb82e57968d884ff8bdb87c076709d4f465fe8825e370a87defb30d7bc49fc-image.png" />

4. A new configuration menu will appear.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/0c5c7c4f187101facffa7de8ed578f7ba0f59e6fc7ee98973e3fd5ccf015a247-Screenshot_2025-05-09_at_5.36.56_PM.png" />

### General Tab

* **Name**: Specify the schedule’s name.
* **Description**: Provide a brief overview of the schedule’s purpose.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/6d06bb7fedbabc96c5da4ef97e5cef2d523894c0535019d9d0424db5b123ebd6-image.png" />

* **Users**: Add users by pressing the "**Add Users**" button, selecting users from the **“Assign users”** window, and clicking "**Add**".

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/57a5e9b913784a04277c02ae391329e241348fa40a294eac523491b3146af393-image.png" />

* **Admin User**: Designate one or more administrators for this schedule. Administrators will receive notifications and approval requests for unassigned shifts or other schedule changes.

<Image align="center" className="border" border={true} width="40%" src="https://files.readme.io/d21dc27428c7409b623f3ff0d8fc8dda9ed705cf8413ea29482a573e62312f11-image.png" />

* **Location**: Select a location using the interactive map or by typing an address.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/a8f1e7c6601ede36470eda208023d55ba86883e88519b30d7e1b5e624250d3b3-image.png" />

* **Active**: Check this box to mark the schedule as “active.” By default, this should be checked. If unchecked, the schedule will be hidden from the list of active schedules.

Click "**Save**" to continue to the next tab.

### Mobile Settings Tab

This section includes two tabs: Requests and Check-in/Checkout. Be sure to configure both.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/d4ba8ca0b2d519df2aa08843763af42d4501fef137a311d0bffb9dcb620e0c1a-image.png" />

#### Requests (Time off, Claim shift, Replacement)

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/4ec675542ccf3b668d743c2a6b41e3f1d9041160fe8e1f4201df2e70af18c5ec-image.png" />

* **Time off** requests:

  * Enable or disable users' ability to submit time-off requests.
  * **Request type**: Label the request type (e.g., “Vacation”).
  * **Category**: For example, “Emergency” or “Regular Absence.”
  * **Report minimum**: Set a minimum notice period before a request can be submitted.
  * **Paid or Unpaid**: Define whether the time off is paid or unpaid.
  * **Requires admin approval**: If checked, an admin must approve the request before it’s processed.
* **Shift Replacement**:

  * Enable the ability for users to request shift replacements.
  * **Replacement requires admin approval**: If checked, admins must approve the replacement request.
* **Claim Shifts**:

  * Enable the option for users to claim shifts.
  * **Time window**: Set a cutoff time (in days/hours/minutes) before which claims can no longer be made.
  * **Claim requires admin approval**: If checked, admins must approve any claimed shifts.

#### Check-in/Checkout

By default, this is integrated with the clock.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/ebfea6f82d7db20a1bc9b428879ff669986f870d4d2db359e5c0a4afd4e31bf2-image.png" />

* **Allow** users to check in and out via the mobile app's clock functionality.
* Alternatively, **automatically** start/end the shift when the scheduled time arrives.

Click "**Save**" to confirm your changes.

### Default Values Tab

This section includes two tabs: Time Settings and Work Schedule. Make sure to configure both.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/2dad70001367c35be2507452767d8b498d7b7eb840706f26c456a0bb07da1eeb-Screenshot_2025-05-09_at_6.04.08_PM.png" />

#### **Time Settings**

In this tab, you can configure settings for the work week and working hours.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/bdd0f8cbf40d9ca1b5bb41dfedb6a7116795e56c506fbc4ba07eff61e23f53d9-image.png" />

* **Week starts**: Select the day when the week starts.
* **Default shift length**: Set the default number of hours for shifts.
* **Work hours from/to**: Set the working hours, for example, from 8 AM to 5 PM.

#### **Work Schedule**

This section allows you to configure limits on hours worked per week and per day.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/d1b635faa707a6dd1a7f7ee0ae7322e7b8410d34595b76aeddb85ed3dd76df08-image.png" />

* **Max hours per user per week**: Set a maximum number of hours a user can work per week.
* **Max hours per user per day**: Set a maximum number of hours a user can work per day.
* **Max hour enforcement**: Prevent users from being assigned shifts that exceed the maximum limits.

Click **Save** to confirm.

### Notification Tab

Configure how **portal users** (administrators) and **mobile users** (employees) receive notifications about schedule events. For each event, you can check or uncheck to send notifications via **Email**, **SMS**, or **push notifications**. By default, SMS notifications are turned off. Be sure to configure both options.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/50158da6ec78ac484bdc53951c4bd81a084007c51980db49c46225099fa18325-image.png" />

#### Portal Users (Admins)

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/39c7c423cbf051b28262d12caef546714aa24f6523d78f2d74f91296c965aebd-image.png" />

#### Mobile Users

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/057e13f8da6b191192af2a624e8944f6b1c081654d9ea0c7d7ce214c31e6f25b-image.png" />

### Template Management Tab

This tab provides an overview of all the templates you've created. Use it as a reference to manage your templates. You can delete one or more templates at a time.

<Image align="center" className="border" border={true} width="80%" src="https://files.readme.io/e2cca0af72bf32f7ac3b9f26b29ff63cfa7c98f4cecda2cbbf925ecc26747ab8-image.png" />

## Add Multiple Users

In **mobohubb**, only users already associated with the schedule can be assigned shifts. If you need to include additional individuals in a specific schedule, follow these steps:

1. **Open** the **schedule**.

2. **Click** **“Add New”**, and then select **"Add Users to Schedule"**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/689938839a6890809f2eaee8972396a4fbdc3806be4ac0dabf2141b72e9c12cb-image.png" />

3. **Check** the users you want to include.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/afe2d509c8a2442443e54b238670c16349ba1e1f5644edc112a2221ecc1d84a5-image.png" />

Use the **search bar** to quickly locate specific names or roles.

4. **Click** **“Add”** to confirm your selections.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b321eef5b09f5fb0286574defd40adece3146bd9ca32c444bbfc8d644847810c-image.png" />

5. **Save** your changes to finalize the updated user list.

***

## Edit a Schedule

1. From the **Schedules** list, **click** the name of the schedule you want to modify.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/f49ae4d8e20a2f9c7c15e35abf0d4c1b506d6a857514701e00178329616dd85b-image.png" />

2. From the schedule screen, click the 3-dot menu, and then press **Settings**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/aaa2c4f842835c88bf4fc9fb7842180c15a475cd22e987e507a8b9f72396a211-image.png" />

3. **Modify** data in any of the tabs (General, Mobile Settings, Default Values, Notification, or Template Management).

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/f21f991679e188062e6782c24e5396fb1e8fa53cf8030811022daa6e1400ce28-image.png" />

4. **Save** and **Close** when finished.

***

## Delete a Schedule

You can only delete schedules with no data records. This is to ensure that critical information is not lost.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/f23b04f5ce23555826f4d53a98a2c442a54a67132775ab06ae829181100b8cc5-image.png" />

1. From the **Schedules** list, **check** the schedule(s) you want to remove.
2. **Click** **“Delete”**.
3. **Confirm** your choice. The schedule will be deleted if it’s empty.

If the schedule contains records, the system won’t allow you to delete it. You can either modify or archive it to preserve the essential data.