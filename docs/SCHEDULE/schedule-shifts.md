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
* **Number of Spots**: If it’s an unassigned shift, specify how many people can claim.
* **Tasks/Forms/Scans**: Attach relevant tasks or forms for employees to complete.

2. **Publish** the shift to make it visible. If you prefer employees can’t see it yet, **save as a draft**.

***

## Add New Drafts

**Draft** shifts remain invisible to mobile users until published:

1. **Click** **“Add new”** in the scheduler.
2. **Select** **“New shift.”**
3. **Fill** in the information (similar to adding a new shift above).
4. **Click** **“Save As Draft”.**

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/d21ecf6912a79a3fbcd17e801110b4c0365a45e02d01ea9e124079f81dec9565-image.png" />

5. This shift appears in the schedule with a **faded background**, indicating a draft state.

***

## Add Multiple Shifts

A **shortened form** lets you quickly create multiple shifts at once with minimal details (e.g., basic date/time, role). Publish them immediately or save them as drafts. See “Add Multiple Shifts” for further instructions.

***

## Add New Shifts from Templates

Shift templates are **pre-designed** forms for common shifts:

1. **Click** **“Add new”** in the scheduler.
2. **Select** **“New shift.”**
3. **Use** the search bar to locate a **saved template**.
4. **Click** **“Add from template.”**
5. **Save** or **publish** as desired.

> For more on creating/editing templates, see “Templates” section.

***

## Update Shifts

Even after publishing, you may edit a shift as long as it hasn’t **started**:

1. In the scheduler, **click** the shift to edit.
2. **Unpublish** if it’s already published (but not started).
3. **Edit** any fields necessary (title, time, tasks, assignments).
4. **Click** **“Update Shift.”**
5. If it’s still a draft, the button says **“Update Draft.”**
6. **Publish** again to make changes visible to users.

***

By following these guidelines, you can manage each **Shift**—from drafts to final publishing, from setting up tasks and forms to verifying user assignments. Each shift remains the core building block of the schedule, allowing employees to know precisely when and where they’re needed.