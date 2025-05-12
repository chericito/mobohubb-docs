---
title: 'Schedule: Shifts'
excerpt: >-
  Learn how to manage **Shifts** in **mobohubb’s Scheduling** tool. This guide
  covers shift indicators, how to add new shifts, create drafts, use shift
  templates, and edit or update existing shifts for efficient workforce
  scheduling.
deprecated: false
hidden: false
metadata:
  robots: index
---
**Scheduling** in **mobohubb** helps assign jobs or shifts to each user, ensuring your business has coverage for every hour it operates. A **shift** is a designated time slot an employee is assigned to work. Administrators create these shifts, and mobile users can then fulfill them with relevant tasks, scans, or forms. Shifts are displayed as the central axis in the scheduling interface.

> **Tip**: If you haven’t yet created a schedule, visit our [“Schedule: Essentials” guide](https://mobohubb.readme.io/docs/schedule#/) for instructions on adding or editing a schedule.

***

## Pay Rate Calculation

**mobohubb** calculates a user’s pay rate based on **two different settings**:

1. **Role Assigned to the Shift**: If a shift is linked to a specific role, mobohubb uses the pay rate from that role. You can view or modify these rates in the [Roles configuration menu](https://mobohubb.readme.io/docs/roles#edit-roles).

2. **User Configuration**: If the shift **has no role**, the system automatically pulls the pay rate set in the [User configuration menu](https://mobohubb.readme.io/docs/users#edit-users).

## Shifts Indicators

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c7889a9087b948e4fd70ab729cb601f536311a92c263fff647a8174335850cb9-image.png" />

Each shift can include various visual indicators, which help differentiate their statuses or key attributes:

### Shift states

#### Published

Visible in the mobile app, so users can **accept** or **decline** the assignment. A published shift displays a **solid background** in the color tied to its role.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/eee7556280283cf921ab1b33de074192f2ffea4eef6279779f535e2b723867e2-image.png" />

#### Missed

The shift was accepted but never started before its scheduled time. It keeps the role’s **solid color**, but the border fades to signal it was missed.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/0267f52b41e30d1d6c407e6080f0d053a434e07c140a98816c5ecb31e7be5b56-image.png" />

#### Completed

After the user checks in, works, and checks out, the shift label is shown with a **strikethrough**, confirming completion.

<Image align="center" width="30% " src="https://files.readme.io/38ce65551b0cb8da5236b51b953f4cd9feeaf257dc49222d1f498b4776e30cca-image.png" />

#### Draft

Still unpublished—therefore invisible to mobile users—and rendered with a **faded background**. Drafts may already include tasks, scans, or forms.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/34348930d35996fdbfb400b964dc66a795fca5b732d0f5e25031c072a879e98f-image.png" />

***

### Alert notification types

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/8e51d680fde8168f85aa436131eaf4213f73133666a396fccc8e8805adff36f3-image.png" />

#### Immediate Attention Messages

A **red icon** flags urgent conflicts—missed shifts, shifts not yet accepted, or overlapping assignments.

<Image align="center" src="https://files.readme.io/e22f4bffbc2266c1759b5eb8a1097c06c457f8a955950f97e02227db5e2d95f2-image.png" />

#### Alert Messages

A **yellow icon** highlights non-critical issues, such as unfinished activities, undefined pay rates, or hour-limit violations.

<Image align="center" src="https://files.readme.io/a6658079c913d07302b36f053a1cc2c7ca9fc999bf8bdff676d073b253699cc0-image.png" />

#### Informative Messages

A **blue icon** communicates neutral information—scheduled time-off, holidays, or other unavailabilities tied to the user or shift.

<Image align="center" src="https://files.readme.io/d25f836d5cc201b49bc7d0955ae1933715edf368e293f1086378422825c96f0f-image.png" />

***

### Shift-based indicators

#### Tasks Indicator

Shows an **activity icon** when tasks, scans, or forms are linked to the shift.

<Image align="center" width="30% " src="https://files.readme.io/6ca98ba5a58cac256175a60fe34688ee1ff32ee215b69930bdfe694bcb86ee1f-image.png" />

#### Spots Indicator

Displays the remaining and claimed spots for an **unassigned shift** that users can pick up.

<Image align="center" width="30% " src="https://files.readme.io/570d687a94305f4d33cad4b80ea3a3933dc6cad10957bffd54c174f89736367f-image.png" />

<br />

No matter which scheduling view you’re in (day, week, month, or list), you can always view individual shift details:

1. **Click** on a shift to inspect.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/3ed296ea5c3f506be08aac09a1da7eca18dcd1c17b4da94e8d0b7b34a00a1c8d-image.png" />

2. A **popup** displays that shift’s core info:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/45e03fc7300c658edf720058b59c76ff02399a9f9d360141cd22c5fa39ae70ee-image.png" />

* **Card Color**: When a shift is created, the **Role** setting determines its color by default—each role has its own color configuration. If needed, you can adjust each role’s color in the [Role configuration menu](https://mobohubb.readme.io/docs/roles#/). This color helps employees quickly recognize the nature of their shifts at a glance. **You can also set a customized color for each shift.**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/88d9599961199b032481e9243681f5d782dc4a23c40aa946c0a0c69eccae605b-image.png" />

* **Tool Bar**: Options to delete, edit, publish/unpublish, duplicate, or exit the shift.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/88497572b0685e989418cd5527c7f8604ddf873fd76e4e4ed853b1b21a0456c2-image.png" />

<br />

* **Shift General Information**:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/da8261416b043ce1a0a756cc3859c6671dfeb48b1e29450f5589bb04ce4222d0-image.png" />

* **Shift Status**: “Draft” or “Publish.”
* **Work Status**: “Not started” until a user checks in; then it becomes “Started.”
* **Location**: The defined work location.
* **Assigned Users**: Number of people assigned.
* **Attachments**: Files or images accessible to users (e.g., instructions).
* **Users’ Information**: Detailed acceptance status, work status, etc.
* **Tasks/Scan/Forms**: Activities linked to the shift and their progress.
* **Alert Messages**: Immediate attention issues or standard alerts. Click to view specific problems.

***

## Add New Shifts

When you’re inside a schedule, you can quickly drop in brand-new shifts for your team.

1. **Click “Add new”** in the scheduler.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b80b79e409bf04fb5e8f7dac87c726cdf20a212e024ebff3740eb62f5c013094-image.png" />

2. **Choose “New shift.”**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/aea3ba996649ae687c742d1eeececd051ba30f11ff517087194c878160352085-image.png" />

3. **Complete the shift details.**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/2c12bb04efc1c5304b69180b7784624de81aa1b147d47b028ecd402fc10eef57-image.png" />

* **Shift Title (\*)** – the name employees see.
* **Color (\*)** – inherits the role color, or pick another.
* **Role** – link to a predefined role (with its own color).
* **Date (\*)** – choose the day and time from the calendar.
* **Skills / Certifications** – specify must-have qualifications.
* **Location** – pinpoint where the shift takes place.
* **Description / Notes** – add context for admins or staff.
* **File Attachment** – upload reference images, PDFs, etc.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/86c7bd4a2437b009b030fcd810629966d6b273b05e4cde45d846706632e3fdf2-image.png" />

* **Assignments** – pick users now, or leave blank for an open shift employees can claim.
* **Number of Spots** – how many people can claim this shift (for unassigned shifts).
* **Tasks / Forms / Scans** – attach the activities employees must complete.\
  *Example*: set **Spots** to **2** if two employees should cover the same shift.

4. **Publish** to make the shift visible in the mobile app, or **Save as Draft** to keep it hidden for now.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/975d12dd22f08fc0bc23af5f25e06c04e9bca13c9ff41e5a8eee9aaf22f9b58e-image.png" />

5. **Edit anytime.** Hover over the shift and click the pencil icon.

   * A draft can be updated or published directly.
   * A published shift must be **unpublished** first, then edited, and finally re-published or saved as a draft.
   * Shifts already **started** by a user can no longer be edited.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/7f59f7eeec7ded3f7ad1ccbfafe6dd3d398d547edda70cdd01c7af1a3fec91d6-image.png" />

***

## Add New Drafts

**Draft** shifts remain invisible to mobile users until published:

1. **Click** **“Add new”** in the scheduler.
2. **Select** **“New shift.”**
3. **Fill** in the information (similar to adding a new shift above).
4. **Click** **“Save As Draft”.**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/707848892c721a2d67fb43ac22f432412c338730b3a3591b6ba620235a0d9184-image.png" />

5. This shift appears in the schedule with a **faded background**, indicating a draft state.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/3a7624733a500066ab80eb66d96cdce6318873494f9d624ad9eed405afea1be2-image.png" />

***

## Add Multiple Shifts

A **shortened form** lets you quickly create multiple shifts in bulk at once with minimal details (e.g., basic date/time, role).

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/7d1c03b12f482ca30933c48916fe81253af000da4753013d99b89c843ff0f3a8-image.png" />

1. **Open** the **scheduler** and **click** the **“Add new”** button.
2. **Choose** **“Add Multiple Shifts”.**
3. **Fill in** the necessary shift details:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/7e3a89b212e1fe2076dbd11ac315434516008bea55893031dccc6be9775f268e-image.png" />

* **Start Date**: Select the date from the interactive calendar.
* **Start Hour** and **End Hour**: Define when the shift begins and ends.
* **Shift Title**: Provide a name your users will recognize.
* **Role**: Assign a role (which determines shift color) from previously created roles.
* **Assignments**: Pick which users will work these shifts. A pop-up lets you filter users by role, certification, or skills.

4. **Add Another Row**:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/af4248835124cd9297cd3ea7e4b9ee6050dfa11cb8e0b8a003207566ab0996ce-image.png" />

* Click the **add (+)** button to create as many shift rows as you need.
* Click the **delete (-)** icon next to that entry to remove a row.

5. **Publish** or **Save as Draft**:

* **Publish** makes the shifts visible to your team on their mobile devices.
* **Save as Draft** keeps them hidden until you’re ready to publish.

> **Note**: You can revisit these shifts later to include more details (like location, tasks, forms, or scans) in the full shift editor if needed.

***

## Edit Shifts

Even after publishing, you may edit a shift as long as it hasn’t **started**:

1. In the scheduler, **click** the shift to edit.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/7f59f7eeec7ded3f7ad1ccbfafe6dd3d398d547edda70cdd01c7af1a3fec91d6-image.png" />

2. **Unpublish** if it’s already published (but not started).

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/4081c4d81dd8a1b92ea6b55b289573cde457bc0d4d2a72aa959fff36c94024ff-image.png" />

3. **Edit** any fields necessary (title, time, tasks, assignments).
4. **Click** **“Update Shift”**. If it’s still a draft, the button says **“Update Draft”**.

<Image align="center" className="border" border={true} src="https://files.readme.io/10517127a6260b7487aad39a8101ce38d660e84a986ebc98481cb8574d269c46-image.png" />

5. **Publish** again to make changes visible to users.

***

# Schedule: Unassigned Shifts

**Unassigned Shifts** (open shifts) allow employees to **claim** spots themselves, rather than having administrators assign them. Shifts can have multiple spots, so multiple employees can claim until the quota is filled.

> **Note**: To be able to publish unassigned shifts, please make sure to have at least set up a Role.

## Unassigned Shift View

<Image align="center" className="border" border={true} src="https://files.readme.io/30607d48f3d30554f1cb85e2a50d0105f8ffa1184b1a36d72162e7664c74a803-image.png" />

The scheduling interface includes a special **Unassigned Shift** section showing hours, total cost, and a **spots indicator** (e.g., “3 of 5 spots claimed”). This helps track how many employees can still claim each open shift.

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/36aaf0ea84f05f7f1efe8fd0e8e18e9c60532c4f7c3e6b83dd4a45364abcd72d-image.png" />

***

## Add New Unassigned Shifts

1. **Open** the scheduler, then **click** **“Add new”**.

2. **Select** **“New shift.”**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/4463cc5ef7e8330459c7cac0dbc930faed152aed8d705d7af06721dc27f48690-image.png" />

3. **Enter** general shift information:

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/c5c124ddddd9a988021ae984d8001ae28a7ae15f4950631e2e7231a8e99b95a1-image.png" />

* **Shift Title**: The name employees see.
* **Color:** Defaults to the role’s color but can be changed.
* **Role:** Associates with a predefined role/color.
* **Date:** Select a specific time using the calendar.
* **Skills/Certifications/Location/Description/Notes/File attachment** (optional): Add clarifications or references.
* **Assignments:** Leave users **unassigned** so they can claim these spots.
* **Number of spots:** Set how many users can claim this shift.
* **Tasks/Forms/Scans:** Link existing tasks, forms, or scan points.

3. **Click** **Publish** to make it visible in the schedule.

<Image align="center" className="border" border={true} src="https://files.readme.io/1db02f19e7094f581b460f95d0ead6652b5010bb4b3765745ebced2df0cf23a2-image.png" />

> **Note:** As employees claim the shift, the spots indicator updates. If admin approval is required, see below for details on approving claims.
>
> <Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/36aaf0ea84f05f7f1efe8fd0e8e18e9c60532c4f7c3e6b83dd4a45364abcd72d-image.png" />

***

## How to Approve Claimed Shifts (If Admin Approval is Required)

If you configure your schedule to require **admin approval** before employees can fully claim a shift:

1. **Open** the scheduler and **click** **“Requests.”**
2. A window shows all requests, including **Claim shift** types.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/4f92a4cd43a17f5177859efee19cf3ed8cbfc8a923a2a5e4370096a237250217-image.png" />

3. **Review** the user, shift details, and request date.
4. **Use** the decision buttons:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/a71270ee6c3d874c23666157efa0e04e87643c2fdb510d2b48b7f5bd46856aab-image.png" />

* **Accept:** The user is officially assigned and deducted the claimed spot.
* **Reject:** The user’s claim is denied; they get a rejection notification.
* **Pending:** Keeps the request unresolved until you decide.

> **Note:** You can set up or change approval requirements in **“Edit Request Settings”** within the schedule’s Mobile Settings.

***

By following these guidelines, you can manage each **Shift**—from drafts to final publishing, from setting up tasks and forms to verifying user assignments. Each shift remains the core building block of the schedule, allowing employees to know precisely when and where they’re needed.