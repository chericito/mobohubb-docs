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

## Shifts Indicators

Each shift can include various visual indicators, which help differentiate their statuses or key attributes:

| Category                | Description                                                                                                                             |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **Published**           | Visible to mobile users, allowing them to accept or reject. Published shifts have a **solid background color**.                         |
| **Immediate Attention** | A **red alert icon** indicating high-risk issues like missed shifts, not accepted shifts, or overlapping shifts.                        |
| **Alert Messages**      | A **yellow alert icon** indicating potential risks such as incomplete activities, missing cost data, or exceeding day/week hour limits. |
| **Completed**           | Once accepted, started, and finished, the shift text appears **crossed out** to signify completion.                                     |
| **Missed**              | Accepted but not started in time; displayed with a **solid color** yet a **faded border**.                                              |
| **Draft**               | Unpublished (invisible to users). Displays with a **faded background**. Can contain tasks, scans, or forms.                             |
| **Tasks Indicator**     | An **activity icon** showing associated tasks, scans, or forms for the shift.                                                           |
| **Spots Indicator**     | Indicates how many slots are available (or claimed) for **unassigned** shifts.                                                          |

***

## Shift Details

No matter which scheduling view you’re in (day, week, month, or list), you can always view individual shift details:

1. **Open** the schedule.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/0061e50d87a0dcdc651e5e08973f7478b9894bf7bb1046af6d12a6165139d7c9-image.png" />

2. **Click** on a shift to inspect.
3. A **popup** displays that shift’s core info:

   * **Tool Bar**: Options to delete, edit, publish/unpublish, or duplicate the shift.
   * **Shift General Information**:
     * **Role**: Assigned to a particular role color or label.
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

## Save Shifts as Templates

Templates in **mobohubb** let you define reusable shift structures—such as standard roles, times, tasks, or forms—so you can create similar shifts more quickly in the future. Any shift you save as a template can be selected again in the scheduler.

1. **Open** the scheduler, then **click** on a shift you'd like to convert into a template.

2. **Edit** the shift if necessary:
   * Shift times, roles, tasks, etc.
   * Use the **Tool bar** in the shift’s detail popup to modify these items.

3. **Scroll** down and **click** **“Save As Template”.**

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/c0115b53daee680444dd6879288d9970f9ee693a2a3798943f0b92f4596a6920-image.png" />

Once saved, the template will be available whenever you use **“Add New Shift from Template”** in the scheduler. This feature allows you to reproduce your most common shifts quickly, reducing the need to recreate details like roles and time periods.

> **Note**: If the shift already exists as a template, you can overwrite or update it by repeating these steps and saving again.

## Add New Shifts from Templates

Shift templates are **pre-designed** forms for common shifts:

1. **Click** **“Add new”** in the scheduler.
2. **Select** **“New shift from template”.**
3. **Use** the search bar to locate a **saved template**.
4. **Click** **“Add from template”.**

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/4c4de6675512c30585a6cd7429303680e8cc7f264ff91c4fd0f437559c02de31-image.png" />

6. **Save** or **publish** as desired.

> For more on creating/editing templates, see “Templates” section.

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

By following these guidelines, you can manage each **Shift**—from drafts to final publishing, from setting up tasks and forms to verifying user assignments. Each shift remains the core building block of the schedule, allowing employees to know precisely when and where they’re needed.