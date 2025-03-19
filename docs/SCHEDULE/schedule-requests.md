---
title: 'Schedule: Requests'
excerpt: >-
  Learn how to manage **Requests** in **mobohubb**'s **Scheduling** feature.
  This guide explains how administrators handle user-initiated requests such as
  **Time Off**, **Claim Shift**, and **Replacement Requests**, along with
  editing request settings and adding new time-off categories.
deprecated: false
hidden: false
metadata:
  robots: index
---
# Schedule: Requests

“Scheduling” in **mobohubb** supports requests from mobile users for **Time off**, **Claim shift**, or **Replacement**, which admins can accept, reject, or mark as pending. Responding to these requests can keep your schedule updated and resolve potential coverage gaps or shift conflicts.

***

## Manage Request

1. **Open** the scheduler and click **“Requests”**.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/25b9130e418ac81266b152f1a34630d249788812ae9027dfdb29c315b0fff591-image.png" />

2. A new window displays all **pending or existing requests**, with details such as category, user, date, and more.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/32e819b1a16f142d8f5923695eb77b0b1f0418a25fe24e7fab46d537c03ccfdf-image.png" />

3. For each request, you can:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/eb2e8d42eddca37a0d4c753c4d70f17a4c539d631d3e40e7794b167f7795ec7c-image.png" />

* **Accept**: Approve the user’s request.
* **Reject**: Deny the request.
* **Mark as Pending**: Keep the request open for further review.

**Users receive notifications about your decision**.

***

## Request Description

### Time Off

Time Off can be custom-defined for various scenarios—paid or unpaid, emergency leaves, vacations, etc.

### Claim Shift

Users can claim **unassigned** shifts ([open shifts](https://mobohubb.readme.io/docs/schedule-shifts#add-new-shifts)), which may require admin approval.

### Replacement Request

A user with an already-assigned shift requests a replacement before the shift starts. Another user may take that shift, subject to admin approval.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/32e819b1a16f142d8f5923695eb77b0b1f0418a25fe24e7fab46d537c03ccfdf-image.png" />

When reviewing requests, you’ll see:

* **Tool Bar**: Includes filters, search bar, columns, and the three-dots menu (to restore view).
* **Main View**: A list of requests, each showing:

  * **Date of Request**: When the user submitted it.
  * **User**: Who initiated the request.
  * **Request Type**: “Time off,” “Claim shift,” “Replacement request,” etc.
  * **Approval Status**: “Approved,” “Rejected,” or “Pending.”

  <br />

  <Image align="center" border={true} caption="General view" src="https://files.readme.io/eb2e8d42eddca37a0d4c753c4d70f17a4c539d631d3e40e7794b167f7795ec7c-image.png" width="80% " />

<Image align="center" border={true} caption="Claim Shift" src="https://files.readme.io/5efe1dcc6addb1409f06d03769db1e2810685c075cda19fe85dd0ae776c406ea-image.png" width="50% " />

<Image align="center" border={true} caption="Replacement" src="https://files.readme.io/1213682890a7151d8d97f900e35aa9a3252a203b97bc6c363a53942aea895da9-image.png" width="50% " />

<Image align="center" border={true} caption="Time off" src="https://files.readme.io/b0321cd14bb577c2ddba772047819a2f8c99c4b13b3bba43fc22d8d4d915dfc0-image.png" width="50% " />

Clicking on a request opens additional details—like the specific shift, the type of time off, or which users are involved in a replacement.

***

## Edit Request Settings

1. In the scheduler, **click** the three-dots button.

2. **Select** **"Settings".**

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/9038d413e55127afb6abb75ddde47c18b5730f2dd27c69a7050ffe4abd03133c-image.png" />

3. Go to the **"Mobile Settings"** tab.
4. Open the **"Requests"** section, where you can update:

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/89faf8c365c657a2b2dd396a289ef39426bfdcdb8e924e477781f1dd16704bd4-image.png" />

* **Enable shift replacement request**: Toggle on/off for user replacements.
* **Replacement requires admin approval**: Force admin confirmation before a user can finalize a replacement.
* **Enable users to claim shifts**: Let employees pick open shifts.
* **Claim shifts require admin approval**: Choose if they need admin’s OK before a shift is fully claimed.
* **Time window** for claiming or declining shifts.

5. **Save** and **close** to confirm your changes.

***

## Add New Time off Request Types

1. In the scheduler, click the **three-dots** button.
2. **Select** **"Settings".**
3. In the **"Mobile Settings"** tab, open **"Requests".**

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/e45481907eba1a4b25b8c001c90b3a4bf723ab8c67fe4dd8c411c4334c5f1f18-image.png" />

4. Within **Time off** requests, you can:

* **Check/uncheck** to allow time-off submissions.
* **Add** or **delete** as many request types as needed. Each request type may include:
  * **Name** (e.g., “Vacation,” “Sick Leave”).
  * **Category** (e.g., “Emergency,” “Regular absence”).
  * **Report minimum** (minimum lead time for requesting).
  * **Paid/Unpaid** status for cost calculation.
  * **Requires admin approval** toggle.

5. **Save** and **close** to finalize your time-off request settings.

***

By effectively handling **Requests**—whether **Time Off**, **Claim Shift**, or **Replacement**—you can maintain a dynamic and responsive schedule, ensuring employees’ needs are met while keeping shifts fully covered.