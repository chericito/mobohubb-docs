---
title: 'Schedule: Advanced Settings'
excerpt: >-
  Explore **Schedule Features** in **mobohubb**, where you can manage shift
  assignments, configure notifications, add or remove unassigned shifts, and
  ensure users maintain a smooth workflow. Learn how to handle filters, view
  options, and actions within the scheduling interface for an efficient resource
  allocation process.
deprecated: false
hidden: false
metadata:
  robots: index
---
**Scheduling** is a **mobohubb** tool that enables the assignment of jobs or shifts to each user while simplifying oversight. With a well-organized schedule, you can efficiently allocate resources, uphold high-quality customer service, and enhance overall productivity.

## Manage the Schedule

1. **Navigate** to the portal’s top menu.
2. **Go to "General Settings".**

* Click **Settings** in the top menu to access various organization configuration options.

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/c5d9e156147887b6174ae0caedda0978803db3129893210e819ae4b143c3ff1d-image.png" />

3. Within the **Configuration** area, click **"Scheduling."**

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/aebcff11860782650df65c1f2ef3cb44e17657f675c1ba070d1a7e001c236ad2-image.png" />

4. **Click** directly on the **Schedule name** you want to open.

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/754f65322ba5ac861915bd8d75924b5d45efed987f6e89c74e3d8aa1e072f0b8-image.png" />

* You can use filters to find it quickly.

4. **General schedule view** opens, typically in **week view** by default.

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/627b81df049da76e897becf01ce5231ef45502fb0fcf087d5a85f343b61f4ee3-image.png" />

### Schedule Overview

A schedule is divided into the **toolbar**, **grid**, **users**, **unassigned shifts**, **schedule bar**, and **header**:

* **Header**: Displays the schedule name.

![](https://files.readme.io/08de989cb98ee0c0cd03480d7eedc743b5024e247cd8db8171609196be49bf7f-image.png)

* **Tool Bar**: Contains filters, search bar, date selector, time selector, request button, actions button, publish button, the 3-dots menu, and the Add New button.

<Image align="center" className="border" border={true} src="https://files.readme.io/941078bb3e853d2ffa2d00098e4d4eed5ae79d4941543b9bc46419ce34485466-image.png" />

* **Schedule Bar**: Displays the view, hours, total cost, and view options.

<Image align="center" className="border" border={true} src="https://files.readme.io/0a8993f545dfd08976bbca3d7342638f1f61a28924f4ddf408b1ff058c42672f-image.png" />

* **Shift View**: Shows user columns, assigned shifts, hours, and total cost details.

<Image align="center" className="border" border={true} src="https://files.readme.io/da7611fda1e120fba793dfbfe87130b74bb6f0f952c9c9c078a164f760ad77ba-image.png" />

* **Unassigned Shift View**: Displays shifts available for users to claim.

<Image align="center" className="border" border={true} src="https://files.readme.io/8f8c326efe81af995ec80968aba0a1b9df540fd8b2daa15231687f31b930c946-image.png" />

<br />

***

## Tool Bar

The toolbar includes functions to change how the schedule is displayed and to perform quick actions.

### Filter

You can apply **Quick** or **Advanced** filters by clicking the **“Filter”** button:

* **Quick Filters**: By default, you see quick filters divided into categories: **User**, **Shift Title**, **Role**, **Work Status**, and **Shift Status**. Click items to create new filters, then press **“Apply”.**
* **Advanced Filters**: Switch to advanced filters to define multiple logical conditions. Each filter is composed of **Label** (data categories), **Compare** (equals, not equals, contained in, etc.), and **Value** (the matching text). Press **“Apply”** once done.

### Search Bar

This is a graphical UI element that accepts keywords or phrases to quickly locate specific info—especially handy in list views.

### Time Selector

Choose between **day**, **week**, **month**, or **list** view:

* **Week View**: The default balance of current day, past few days, and upcoming days.
* **Day View**: Offers detailed, hour-by-hour visuals for a single day.
* **Month View**: Provides a broader overview of shifts in a calendar-like format.
* **List View**: Groups data by user with cost/hours info, and allows exporting as an Excel file.

### Date Selector

Select a specific date to view. This can open an interactive calendar, making it easy to pinpoint a day.

### Requests

Access user requests (e.g., **Time Off**, **Claim Shift**, **Replacement Requests**) within the scheduling interface. Admins can accept, reject, or set them as pending.

### Actions

Within the scheduler, clicking **“Actions”** reveals various operations:

* **Unpublish Week**: Converts published shifts to drafts, hiding them from mobile users.
* **Copy Form Template**: Opens a window with ready-to-use templates.
* **Clear Week**: Deletes all **not started** shifts in the current view.
* **Remove Assignments**: Marks all shifts as unassigned, letting users claim them.
* **Save as Week Template**: Saves the present week’s layout as a reusable template.
* **Copy Previous Week**: Brings over last week’s shifts into the current week.
* **Add or Edit Unavailability**: Manage the times users are marked as unavailable.
* **View Conflict**: Highlights warning or alert messages for immediate attention (e.g., overlapping shifts or missing acceptances).
* **Export PDF**: Downloads the current view as a PDF (appears in **“Downloads”** if it exceeds file size limits).

### Publish

The **Publish** button makes shifts visible to mobile users. Until published, shifts remain drafts and are hidden from employees. Confirm publishing after reviewing any alert messages to ensure correctness.

### Add New Button

The **Add New** button includes multiple scheduling features:

* **Add New Shift** (see “Add New Shift” section)
* **Add Shifts from Templates** (see “Add Shifts from Templates” section)
* **Add Multiple Shifts** (see “Add Multiple Shifts” section)
* **Add Users to the Schedule** (see “Add Users to the Schedule” section)

***

## Schedule Bar

#### View Options

In day, week, month, or list view, the **View Options** button can hide specific elements, like unassigned shifts or message icons. Any changes apply immediately and can be undone by toggling the same setting.

#### Day Column

Each day may display **alert messages** or **immediate attention** icons if conflicts arise (e.g., a not-accepted shift or missed shift). The schedule typically flags:

* **Immediate Attention (Red)**: Missed shifts, overlapping shifts, or not-accepted shifts.
* **Alert (Yellow)**: Incomplete tasks, uncalculated cost (missing fee), or exceeding hour limits.

#### Hours and Total Cost

Mobohubb calculates total labor costs based on shift assignments, recorded hours, and assigned pay. The schedule bar shows daily, weekly, or monthly costs, depending on your selected time range.

***

## Shift View

A **shift** is a specified time slot an employee is assigned to work. Administrators create these shifts in the scheduler, often linking them to tasks, scans, or forms if needed. Shifts are color-coded to differentiate them quickly. (See the **“Schedule Shifts”** section for details on creating/managing shifts.)

***

## User Column

This column can also reflect conflict icons or alert messages for each user:

* **Immediate Attention (Red)**: Missed shifts, overlapping shifts, or unaccepted shifts.
* **Alert (Yellow)**: Tasks incomplete, missing cost info, or hour limits exceeded.

***

By understanding the **Manage Schedule** interface—filters, actions, publish status, and additional functionalities—you can effectively organize shifts, track user acceptance, and monitor potential schedule conflicts. For deeper details on shift creation, templates, or user additions, see corresponding sections like **“Add New Shift,”** **“Add Multiple Shifts,”** or **“Add Users to the Schedule.”**