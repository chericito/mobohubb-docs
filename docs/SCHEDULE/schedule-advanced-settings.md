---
title: 'Schedule: Overview'
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
**Scheduling** is a **mobohubb** tool that enables assigning jobs or shifts to each user while simplifying oversight. With a well-organized schedule, you can efficiently allocate resources, uphold high-quality customer service, and enhance productivity.

## Pay Rate Calculation

**mobohubb** calculates a user’s pay rate based on **two different settings**:

1. **Role Assigned to the Shift**: If a shift is linked to a specific role, mobohubb uses the pay rate from that role. You can view or modify these rates in the [Roles configuration menu](https://mobohubb.readme.io/docs/roles#edit-roles).

2. **User Configuration**: If the shift **has no role**, the system automatically pulls the pay rate set in the [User configuration menu](https://mobohubb.readme.io/docs/users#edit-users).

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

<Image align="center" className="border" border={true} src="https://files.readme.io/4b8ef6ecb06beeaee9b5752576bf4e2034af459ca13db51d02c477f81077ac4d-image.png" />

You can apply **Quick** or **Advanced** filters by clicking the **“Filter”** button:

**Quick Filters**: By default, you see quick filters divided into categories: **User**, **Shift Title**, **Role**, **Work Status**, and **Shift Status**. Click items to create new filters, then press **“Apply”.**

<Image align="center" className="border" border={true} src="https://files.readme.io/422925760c7c7d644d7d0ddd2fd7301cef1fedc97f52f2d07e00b42d8899f9b5-image.png" />

**Advanced Filters**: Switch to advanced filters to define multiple logical conditions. Each filter is composed of **Label** (data categories), **Compare** (equals, not equals, contained in, etc.), and **Value** (the matching text). Press **“Apply”** once done.

**You can return to Quick Filters by pressing "Switch to Quick Filters".**

### Search Bar

This is a graphical UI element that accepts keywords or phrases to quickly locate specific info—especially handy in list views.

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/b6fe728d76d5496099af2c45bd75bcd42cda491e2dc551f0509be45b010a2d37-image.png" />

### Time Selector

Choose between **day**, **week**, **month**, or **list** view:

<Image align="center" className="border" border={true} width="60% " src="https://files.readme.io/2448f6159650c9d91810e0578ae14f52233cc3ad4338d3a1713e9fadfa395d05-image.png" />

* **Week View**: The default balance of the current day, past few days, and upcoming days.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/dc1c41500198f181e24e31e6bf30f02d71eb380e2193264ff31a5b877028fcae-image.png" />

* **Day View**: Offers detailed, hour-by-hour visuals for a single day.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/e13d2bb01628cec29aea8a99df23ed945e80d57763e0231bb8d3ee513a7adcfd-image.png" />

* **Month View**: Provides a broader overview of shifts in a calendar-like format.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/c644d591ecf2d6244376dd7bbb43a7ff3f4c8a9660c366458bcf1dfcd4a8791d-image.png" />

* **List View**: Groups data by user with cost/hours info, and allows exporting as an Excel file.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/14cc24e076a4b690934fa2bf9d1784137b0e094c2e458f21b644d88fff9cee8b-image.png" />

### Date Selector

Select a specific date to view. This can open an interactive calendar, making it easy to pinpoint a day.

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/2c5e329b877fc901395bbab53d1f6cc0a5d378488a68de1c345e7976c9f97877-image.png" />

### Requests

Access user requests (e.g., **Time Off**, **Claim Shift**, **Replacement Requests**) within the scheduling interface. Admins can accept, reject, or set them as pending.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/32e819b1a16f142d8f5923695eb77b0b1f0418a25fe24e7fab46d537c03ccfdf-image.png" />

<br />

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/eb2e8d42eddca37a0d4c753c4d70f17a4c539d631d3e40e7794b167f7795ec7c-image.png" />

### Actions

Within the scheduler, clicking **“Actions”** reveals various operations. Visit our dedicated guide on [Actions](https://mobohubb.readme.io/docs/schedule-actions#/).

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/74dcb6cae3a4fd2cf7df22f7de297d51f98e9e04dd73e8763fa738104e0ae3e3-image.png" />

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

<Image align="center" className="border" border={true} src="https://files.readme.io/f110f8febab4226ea0baa8047ac00ef029e20762436f9f1947e8341dbe21ee5b-image.png" />

The **Publish** button makes shifts visible to mobile users. Until published, shifts remain drafts and are hidden from employees. Confirm publishing after reviewing any alert messages to ensure correctness.

### Add New Button

The **Add New** button includes multiple scheduling features:

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/4d32a805dd8e0619ece549f97d61737a2fabe91b1750c96df97f20a6afd808ac-image.png" />

* **Add New Shift** (see “Add New Shift” section)
* **Add Shifts from Templates** (see “Add Shifts from Templates” section)
* **Add Multiple Shifts** (see “Add Multiple Shifts” section)
* **Add Users to the Schedule** (see “Add Users to the Schedule” section)

***

## Schedule Bar

#### View Options

In day, week, month, or list view, the **View Options** button can hide specific elements, like unassigned shifts or message icons. Any changes apply immediately and can be undone by toggling the same setting.

<Image align="center" className="border" border={true} src="https://files.readme.io/0a8993f545dfd08976bbca3d7342638f1f61a28924f4ddf408b1ff058c42672f-image.png" />

<Image align="center" className="border" border={true} src="https://files.readme.io/93057c5fc564b015313ff87b52596aaad5ad958f09c29336f937d8d07fff7500-image.png" />

#### Day Column

Each day may display **alert messages** or **immediate attention** icons if conflicts arise (e.g., a not-accepted shift or missed shift). The schedule typically flags:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/5e186453b22d15e4bb892d06cb99ebda3772c5a0ba99f0cba22afaadb694877c-image.png" />

<br />

* **Immediate Attention (Red)**: Missed shifts, overlapping shifts, or not-accepted shifts.
* **Alert (Yellow)**: Incomplete tasks, uncalculated cost (missing fee), or exceeding hour limits.

#### Hours and Total Cost

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/87d587627e48db98c7042702637e4273efe12788348b60320efa6018a02a96c1-image.png" />

mobohubb calculates total labor costs based on shift assignments, recorded hours, and assigned pay. The schedule bar shows daily, weekly, or monthly costs, depending on your selected time range.

***

## Shift View

![](https://files.readme.io/8088c22f2bbb9a125d0cab49c63833e3224be0be6ca1cd43ad79fc83e0f8bced-image.png)

A **shift** is a specified time slot an employee is assigned to work. Administrators create these shifts in the scheduler, often linking them to tasks, scans, or forms if needed. Shifts are color-coded to differentiate them quickly. (See the **“[Schedule Shifts](https://mobohubb.readme.io/docs/schedule-shifts#/)”** section for details on creating/managing shifts.)

***

## User Column

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/d65bc9fa0d6093a7fc5bde9e5535a65f2e5db4f6978cd00c77a87bac205877e9-image.png" />

This column can also reflect conflict icons or alert messages for each user:

* **Immediate Attention (Red)**: Missed shifts, overlapping shifts, or unaccepted shifts.
* **Alert (Yellow)**: Tasks incomplete, missing cost info, or hour limits exceeded.

***

By understanding the **Manage Schedule** interface—filters, actions, publish status, and additional functionalities—you can effectively organize shifts, track user acceptance, and monitor potential schedule conflicts. For deeper details on shift creation, templates, or user additions, see corresponding sections like **“Add New Shift,”** **“Add Multiple Shifts,”** or **“Add Users to the Schedule.”**