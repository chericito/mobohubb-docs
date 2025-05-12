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

<Image align="center" className="border" border={true} src="https://files.readme.io/c7889a9087b948e4fd70ab729cb601f536311a92c263fff647a8174335850cb9-image.png" />

Each shift can include various visual indicators, which help differentiate their statuses or key attributes:

### Shift states

#### Published

Visible to mobile users, allowing them to accept or reject. Published shifts have a **solid background color**. This color is set based on the color assigned to the role.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/eee7556280283cf921ab1b33de074192f2ffea4eef6279779f535e2b723867e2-image.png" />

#### Missed

Accepted but not started in time; displayed with a **solid color** yet a **faded border**.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/0267f52b41e30d1d6c407e6080f0d053a434e07c140a98816c5ecb31e7be5b56-image.png" />

#### Completed

Once accepted, started, and finished, the shift text appears **crossed out** to signify completion.

<Image align="center" width="30% " src="https://files.readme.io/38ce65551b0cb8da5236b51b953f4cd9feeaf257dc49222d1f498b4776e30cca-image.png" />

#### Draft

Unpublished (invisible to users). Displays with a **faded background**. Can contain tasks, scans, or forms.

<Image align="center" className="border" border={true} src="https://files.readme.io/34348930d35996fdbfb400b964dc66a795fca5b732d0f5e25031c072a879e98f-image.png" />

### Alert notifications types

<Image align="center" className="border" border={true} src="https://files.readme.io/8e51d680fde8168f85aa436131eaf4213f73133666a396fccc8e8805adff36f3-image.png" />

<br />

#### Immediate Attention Messages

A **red alert icon** indicates high-risk issues like missed shifts, not accepted shifts, or overlapping shifts.

![](https://files.readme.io/e22f4bffbc2266c1759b5eb8a1097c06c457f8a955950f97e02227db5e2d95f2-image.png)

#### Alert Messages

A **yellow alert icon** indicates potential risks such as incomplete activities, missing cost data, or exceeding day/week hour limits.

![](https://files.readme.io/a6658079c913d07302b36f053a1cc2c7ca9fc999bf8bdff676d073b253699cc0-image.png)

<br />

#### Informative Messages

A **blue alert icon** indicates shift or user-associated time off or unavailabilities for holidays, company day off, etc.

<br />

![](https://files.readme.io/d25f836d5cc201b49bc7d0955ae1933715edf368e293f1086378422825c96f0f-image.png)

<br />

### Shift-based indicators

#### Tasks Indicator

An **activity icon** showing associated tasks, scans, or forms for the shift.

#### Spots Indicator

Indicates how many slots are available (or claimed) for **unassigned** shifts.

## Shift Details

No matter which scheduling view you’re in (day, week, month, or list), you can always view individual shift details:

1. **Open** the schedule.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/0061e50d87a0dcdc651e5e08973f7478b9894bf7bb1046af6d12a6165139d7c9-image.png" />

2. **Click** on a shift to inspect.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/122780b2d2e9c594b3b445beed631c4d892e590b369c8339098b904257c0a537-image.png" />

<br />

3. A **popup** displays that shift’s core info:

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/cf42e06de54653555f86877b905c99d68b478cea08e8127c5e3980375f82569b-image.png" />

* **Card Color**: When a shift is created, the **Role** setting determines its color by default—each role has its own color configuration. If needed, you can adjust each role’s color in the [Role configuration menu](https://mobohubb.readme.io/docs/roles#/). This color helps employees quickly recognize the nature of their shifts at a glance. **You can also set a customized color for each shift.**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/88d9599961199b032481e9243681f5d782dc4a23c40aa946c0a0c69eccae605b-image.png" />

* **Tool Bar**: Options to delete, edit, publish/unpublish, duplicate, or exit the shift.
* **Shift General Information**:
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

When viewing a schedule, administrators can create fresh shifts:

1. **Click** **“Add new”** in the scheduler.
2. **Choose** **“New shift”.**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/57065088c5468fd2067028a4bbb9ad909d0ec70f6b5d67dad3ddd407336881e1-image.png" />

2. **Fill** in shift details:

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/70891c4790b49a3cc2ea84c3792fea946a2530ee73337ed62d91c798212265ef-image.png" />

* **Shift Title** (\*): Name visible to users.
* **Color** (\*): Inherits from the role by default, but can be changed.
* **Role**: Associates the shift with a predefined role (which has a color).
* **Date** (\*): Select using the interactive calendar.
* **Skills/Certifications**: Request specific skills or certifications.
* **Location**: Select or type in the shift location.
* **Description**/Notes: Any clarifying text for admins or employees.
* **File Attachment**: Additional reference material or images.

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/0b0233819fadc6cb71d6c1a1800c056f257c92a7f7b82c56b225d9e3d29aa81d-image.png" />

* **Assignments**: Specific users assigned. Or leave unassigned if you plan to let employees claim it.
* **Number of Spots**: Specify how many people can claim if it’s an unassigned shift.
* **Tasks/Forms/Scans**: Attach relevant tasks or forms for employees to complete. Set it to "2" if you want two persons doing the same job, on that same shift.

2. **Publish** the shift to make it visible. If you prefer employees can’t see it yet, **save as a draft**.
3. You can **edit** a shift at any time by hovering over the shift, and then pressing the "Edit button".

<Image align="center" width="60% " src="https://files.readme.io/3960b2a01b40f87cb5f6fab3f0aa9f3a42bdce483640428cf3c0b41f6b84a9b5-image.png" />

<br />

***

## Add New Drafts

**Draft** shifts remain invisible to mobile users until published:

1. **Click** **“Add new”** in the scheduler.
2. **Select** **“New shift.”**
3. **Fill** in the information (similar to adding a new shift above).
4. **Click** **“Save As Draft”.**

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/d21ecf6912a79a3fbcd17e801110b4c0365a45e02d01ea9e124079f81dec9565-image.png" />

5. This shift appears in the schedule with a **faded background**, indicating a draft state.

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/a4c148f2ab1ae968059f37cca6b5874bf67d7be1818d369ef6913cf024f00fae-image.png" />

<br />

***

## Add Multiple Shifts

A **shortened form** lets you quickly create multiple shifts in bulk at once with minimal details (e.g., basic date/time, role).

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/b32365fd16b916fd5120b0de517504ff4479baff628eaf358ff191a479b8b177-image.png" />

1. **Open** the **scheduler** and **click** the **“Add new”** button.
2. **Choose** **“Add Multiple Shifts”.**
3. **Fill in** the necessary shift details:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b5a150d7d44983bec70fc2b489d1a287619218cf936251fde0f5acb2edfa3f93-image.png" />

* **Start Date**: Select the date from the interactive calendar.
* **Start Hour** and **End Hour**: Define when the shift begins and ends.
* **Shift Title**: Provide a name your users will recognize.
* **Role**: Assign a role (which determines shift color) from previously created roles.
* **Assignments**: Pick which users will work these shifts. A pop-up lets you filter users by role, certification, or skills.

4. **Add Another Row**:

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/c2d412f1f4ed9deb877356421db74911f52f13672e2aa50fccbd5898f68b1b8c-image.png" />

* Click the **add (+)** button to create as many shift rows as you need.
* Click the **delete (-)** icon next to that entry to remove a row.

5. **Publish** or **Save as Draft**:

* **Publish** makes the shifts visible to your team on their mobile devices.
* **Save as Draft** keeps them hidden until you’re ready to publish.

> **Note**: You can revisit these shifts later to include more details (like location, tasks, forms, or scans) in the full shift editor if needed.

***

<br />

***

## Update Shifts

Even after publishing, you may edit a shift as long as it hasn’t **started**:

1. In the scheduler, **click** the shift to edit.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/95f1e09c0421059bc487ccf6ab743bfc28a9e35f49d2ac1c8e8c778e70186227-image.png" />

2. **Unpublish** if it’s already published (but not started).

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/a1c65962f30739ab06810bb90acf5421b2cc37bf31c3e6791061d897b5eed71e-image.png" />

3. **Edit** any fields necessary (title, time, tasks, assignments).

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/f730338d0df3abee3e34a4539eb952f335bf2595b5991d86ab46f7e72a13c962-image.png" />

4. **Click** **“Update Shift”**. If it’s still a draft, the button says **“Update Draft”**.
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

* **Shift Title*:*\* The name employees see.
* **Color*:*\* Defaults to the role’s color but can be changed.
* **Role:** Associates with a predefined role/color.
* **Date*:*\* Select a specific time using the calendar.
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

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/a6fae5f6dfa37f45dd8cbd478e06c8edb9cc585750707dac660dba2abf79f24a-image.png" />

3. **Review** the user, shift details, and request date.
4. **Use** the decision buttons:

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/842c11bcd970524866505d179aeab16accc54099fff4346c07e9427bdde48508-image.png" />

* **Accept:** The user is officially assigned and deducted the claimed spot.
* **Reject:** The user’s claim is denied; they get a rejection notification.
* **Pending:** Keeps the request unresolved until you decide.

> **Note:** You can set up or change approval requirements in **“Edit Request Settings”** within the schedule’s Mobile Settings.

***

By following these guidelines, you can manage each **Shift**—from drafts to final publishing, from setting up tasks and forms to verifying user assignments. Each shift remains the core building block of the schedule, allowing employees to know precisely when and where they’re needed.