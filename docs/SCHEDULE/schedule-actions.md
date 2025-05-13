---
title: 'Schedule: Actions'
excerpt: >-
  Discover how to manage **Actions** in **mobohubb’s Scheduling** feature. This
  guide explains the “Actions” menu, where you can unpublish or clear an entire
  week, remove shift assignments, copy or save templates, and add/edit
  unavailability. Learn to streamline schedule management and maintain accurate,
  efficient planning.
deprecated: false
hidden: false
metadata:
  robots: index
---
# Schedule: Actions

Access this menu via the toolbar within the scheduler.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c76c17947ba391243bf419e3ebc01991fbf733a7901b92e3c4ddb6aabf87b263-image.png" />

Administrators can perform various actions in the schedule using the **Actions** menu.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/b12d9cd8f5a9d93c60cae66136055c1dca40c9111ffd12e5c6678d8855b73a5f-image.png" />

**Menu Options:**

* **Unpublish Week**: Converts published shifts to drafts, hiding them from mobile users.
* **Copy From Template**: Opens a popup with ready-to-use templates.
* **Clear Week**: Deletes all **non-started** shifts in the current view.
* **Remove Assignments**: Changes all assigned shifts to unassigned, letting users claim them.
* **Save as Week Template**: Captures the current week’s shifts and layout for future reuse.
* **Copy Previous Week**: Copies shifts from the last week into the current one.
* **Add or Edit Unavailability**: Manage hours/days when employees are not available.
* **Export PDF**: Downloads the current schedule view as a PDF (if file size is large, it appears in “Downloads”).

***

## Unpublish Week

Turning a published week into a draft state hides all shifts from mobile app users:

1. **Navigate** to the correct week using the **Date Selector** (week view).
2. **Click** **Actions** in the schedule’s toolbar.
3. **Select** **Unpublish Week**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/87d0688090a2675fd1c8e0fa7335952888ac78fa9897d334ee764f7d107f3812-image.png" />

4. **Confirm** to revert published shifts to drafts.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/cdde78fe1fd08a23f547c8fef2ad3ba6ea03fbff0ab2369e6df979580a584a6a-image.png" />

5. **All shifts** are now **drafts**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c5a7949e3ef8a813f15e202d411c1c3f4cb36cc056d592c74863e6eab3c3d6ee-image.png" />

***

## Clear Week

The **Clear Week** option removes all shifts—draft, published, or unassigned—provided they haven’t been started:

1. **Go** to the desired week using the Date Selector.
2. **Click** **Actions**.
3. **Choose** **Clear Week**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/9d7585751a6e041d9733e7e20e35ad16aae19fed28564123d4b6652572506ad3-image.png" />

4. **Confirm** by clicking **Delete**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b760d4e0b34a5f5a892ecdb41325999da35d33281ffdc37b44d6cb924c1b5995-image.png" />

5. The **week** is now **empty**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b8dd3ebd6d76ac9821879a080905e088dc952382a4d44a586081a0898784c67a-image.png" />

> **Note**: Shifts already started/completed by a user (checked in) remain intact.

***

## Remove Assignments

This action unassigns all shifts in the selected week, turning them into open (unassigned) shifts. Users can then claim them via the Mobile App:

1. **Select** the week in the Date Selector.
2. **Click** **Actions** in the scheduler.
3. **Choose** **Remove Assignments**.
4. **Submit** to confirm.

All user links are cleared, but the shifts remain visible for claiming.

***

## Save Templates & Copy From Templates

You can **save** entire weeks (or days) as templates for quick re-creation:

1. **Select** the timeframe (week/day) with the Time Selector.
2. **Press** **Actions** → **Save as Week/Day Template**.
3. **Name** the template and **save** it.

To **apply** a template to a future week/day:

1. **Move** to the next or target timeframe.
2. **Press** **Actions** → **Copy from Template**.
3. **Confirm** to import the layout.

<Image align="center" alt="Save As Template" border={true} caption="Save as Template" src="https://files.readme.io/0fc9ef5736c12b00439e8e940d04d9f5267621c1e2d3ce43d90764b4aae7eee5-image.png" width="50% " />

<br />

<Image align="center" border={true} caption="Copy from Template" src="https://files.readme.io/aa832f677e32824f10a3bde3f30c166bfac0e1e1f96924bb1b9a2873e49636b3-image.png" width="50% " />

<br />

<br />

***

## Add or Edit Unavailability

Unavailability marks specific times or dates when employees **can’t** take shifts. Examples: holidays, or events.

1. **In** the scheduler, **click** **Actions** → **Add or Edit Unavailability**.
2. A popup lists current unavailabilities.

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/53ce070987ffe205a81548ca8a9789c1264312ae1692eabdf19c495d174b8bae-image.png" />

3. **Click** **ADD NEW** to create a new unavailability or **Edit** an existing one:

<Image align="center" className="border" border={true} width="50% " src="https://files.readme.io/eb019df6faf8b9e459dcdca3b490070b43086c6b287f1f1362b93f132745902d-image.png" />

* **Unavailability name**: A descriptive label, e.g., “Saint Julius Day”
* **Holiday** (optional): Check if it’s a recognized holiday.
* **Start date** / **End date**: Use the interactive calendar; end date must not precede start date.
* **Save** changes.

If you need to delete an unavailability:

1. **Check** the item from the popup list.
2. **Click** **Delete** and confirm.

<Image align="center" border={true} caption="Employees marked unavailable cannot be scheduled for shifts during those times." src="https://files.readme.io/d563bec935bc2cf63bdb4b40872fca708a4d820b0942c998667b4f7ec0f019b4-image.png" />

***

# View Conflict

When **conflicts** arise in your schedule—like missed shifts, not accepted shifts, or overlaps—you can see all issues at once for quick resolution.

1. **Open** the scheduler interface.

2. **Click** **“Actions.”**

3. **Choose** **“View conflict.”**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/7c473abe55777b2bd137f5c38365ddcd1e7a9ea28d41276199365f9ffff4a148-image.png" />

4. A list of **messages** (conflicts) appears, which you can scroll through to find each issue:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/6eca170bea7891dce28947a08c85ab16ecc9d2d87456939dbb83979bb6c0c597-image.png" />

<br />

* **Immediate Attention (Red Alert)**:
  * **Missed shift**
  * **Not accepted shift**
  * **Overlapping shifts**
* **Alert Messages (Yellow Alert)**:
  * **Not completed** activities (tasks, scans, forms)
  * **Cannot calculate cost** (missing fee)
  * **Exceed limit hours** per day or week

Review these conflicts to address scheduling shortfalls and keep your workforce operations running smoothly.

# Export PDF

**Export PDF** allows you to download the currently displayed schedule, making it simple to print or share offline.

1. **Open** the scheduler and use the **Date Selector** in the toolbar to pick the **week** you want to export.
2. **Click** **Actions** in the schedule toolbar.
3. **Choose** **“Export PDF”.**

<Image align="center" className="border" border={true} src="https://files.readme.io/a8a7a200816ba6503d6d4119866a1bc38d564ee8ba42c7fdefc403b62cccb439-image.png" />

4. The PDF **downloads** to your device.
5. **Open** the file locally to view or print the schedule.

> **Note**: If the file size is large, the PDF might appear in **“Downloads”** on the platform instead of an immediate device download.