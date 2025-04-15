---
title: Scan Points
excerpt: >-
  A comprehensive guide to setting up, managing, and organizing scan points (QR
  codes or NFC tags) in mobohubb. Learn how to add, edit, delete, import, and
  export scan points to streamline your on-site operations.
deprecated: false
hidden: false
metadata:
  robots: index
---
A **scan point** is an element that can be read with a mobile device. **mobohubb** supports two types of scan points: **QR codes** and **NFC tags**. These allow you to manage your locations—such as **sites, zones, or checkpoints**—in a structured way. For each site you create, decide whether you'll use **QR codes** or **NFC tags** so employees can easily scan them in the field.

* **Tip:** Make sure you’ve identified your **places of interest** before defining any scan points.

***

**In this guide you'll learn**

* **Add QR Code Scan Points**: Learn how to create and configure new QR codes to identify specific locations or checkpoints.
* **Add NFC Tag Scan Points**: Discover how to set up and manage NFC-enabled locations for swift, contactless scanning.
* **Edit Existing Scan Points**: Update names, IDs, intervals, and other details as your operations evolve.
* **Delete Scan Points**: Remove outdated or unused scan points to keep your data clean and relevant.
* **Export Scan Points**: Generate an Excel file for off-platform analysis or archiving.
* **Import Multiple Scan Points**: Use an Excel template to quickly upload a batch of scan points, saving time and effort.

## Choose QRs or NFCs

Each site can be configured to use **either QR codes or NFC tags**, but not both at once. To specify which scan point type a site should use, follow these steps:

1. **Navigate** to **Settings** → **Site Management**.

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/15e880921891b7d52c30b7ed81b352c61cb79d921d9eb123a566dad1bbf8889d-06C62B98-9B3E-46A4-8CBB-B952FF054AD9.png" />

2. **Select** the **site** you wish to configure from the list.

<Image align="center" className="border" border={true} width="70% " src="https://files.readme.io/2314ec1f55a0e34fe4ccf397af1dbaad08ee9492c780e8f22b8092be3586d327-9B192797-48D7-4287-A6DC-FF33A270F221.png" />

3. In the **Site Information** section, **choose** either **QR Codes** or **NFC Tags** as the scan type.

<Image align="center" className="border" border={true} width="76% " src="https://files.readme.io/11366422606d899b4d28b3af4fc2649dc6d21e264bf191dacb39114867ae51bf-Screenshot_2025-04-15_at_3.17.45_PM.png" />

4. **Save** your changes to finalize the site’s configuration.

## Add a QR Code Scan Point

Follow these steps to create a new scan point associated with a **QR code**:

1. **Navigate to the Portal’s Top Menu** and select **Settings** from the dropdown.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/84271ddfd277b67b32b0addce24e9e728b4ac48763aa0b92a63a0cf8c52f9a50-Screenshot_2025-04-03_at_12.41.34_PM.png" />

2. From the **Configuration** section, select “Scan-Points".

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/3cf9e55fcc76b359347766a7debe9f5c3fb4b6a450cb56ca4a3417255a149457-Screenshot_2025-04-15_at_3.24.10_PM.png" />

3. **Click “Add New”**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/31aa735b9c8e70a144713c633c97dfd0fa24b61e6dde788db8fde64931cd47f7-Screenshot_2025-04-15_at_3.26.09_PM.png" />

4. **Fill in the details**:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/72ef1fea50a0ad72f1fbc9ac2b079c2a447559246fae278cded8a9d8380e547e-image.png" />

* **Fill in the QR Code ID**
  * Use a unique, sequential identifier that matches the QR (e.g., `Location001`, `Location016`). This ID is case-sensitive and will help you organize and differentiate scan points.Refer to **[How to create a QR code](https://mobohubb.readme.io/docs/qr-codes#/)** for details on generating the actual QR code.
* **Add a Name**

Provide a clear name (e.g., “Security Camera Room”) to quickly locate the scan point.

* **Add a Description**
  * Include room numbers, distinctive features, or exact locations to help users find it easily.
* **Choose a Time Interval**
  * Enter the time in **HH:MM** format (e.g., `08:00`) if you need periodic scans or want to classify your scan points for log comparisons. This is required for Time Studies, a function that demonstrates the scanning frequency of QR captures that have the time interval parameter marked; for example, how security patrollers perform their patrols, scanning each time they pass by the designated locations. Time studies enable you to confirm how frequently this scan was finished.
* **Associate a Predefined Tag** *(Optional)*
  * If you’ve created [tags](https://mobohubb.readme.io/update/docs/tags#/) beforehand, select one in the dropdown.
  * **Tags** help segment data and simplify searches.
* **Link to a Task or Form** *(Optional)*. You can associate the scan point with an existing task or form. To mark that task or form as **complete**, the user must **scan** the point. This ensures the activity is tracked and verified in the system.
  * To associate this QR code with an **existing** [task](https://mobohubb.readme.io/update/docs/tasks#/) or [form](https://mobohubb.readme.io/update/docs/tasks#/), select it from the dropdown menu.
  * Tasks/forms must be **active** to appear here.

5. **Mark as Active** (active by default)

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/763f47cbcfcc41be28b534462fcdac8219c7ba768c657299b4996737c1dd8d6e-Screenshot_2025-04-15_at_5.08.17_PM.png" />

* **Check** the box to make this scan point visible to other users.
* If unchecked, it remains hidden but can be activated later.

6. **Save and Close**

> **Note:** **Repeat** these steps for each scan point you need to create.

## Add an NFC Tag Scan Point

1. **Configure** the [NFC using the Mobile App](https://mobohubb.readme.io/v1.2/docs/nfc-mobile#/).
2. **Fill in the details**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/72ef1fea50a0ad72f1fbc9ac2b079c2a447559246fae278cded8a9d8380e547e-image.png" />

* **Fill in the NFC Code ID**
  * NFC (Near Field Communication) tags are **small, passive devices** containing a microchip and antenna.
  * You can **scan** any unassigned NFC tag with the mobile app, then update its details in the portal.
  * **Do not** modify the Scan-Point ID for any NFC, this will make the NFC configuration useless.
* **Add a Name**
  * Provide a clear identifier (e.g., “Security Camera Room”) for quick reference.
* **Add a Description**
  * Include any relevant details such as room number or distinctive features.
* **Choose a Time Interval**
  * Use **HH:MM** format (e.g., `08:00`) to classify periodic scans or log comparisons.
* **Associate a Predefined Tag** *(Optional)*
  * If you have previously created tags, assign one here to **segment data** and simplify searches.
* **Link to a Task or Form** *(Optional)*
  * If needed, associate this NFC tag with an **existing** task or form (they must be **active**).

3. **Mark as Active**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/763f47cbcfcc41be28b534462fcdac8219c7ba768c657299b4996737c1dd8d6e-Screenshot_2025-04-15_at_5.08.17_PM.png" />

* Check the box to make this scan point visible to mobile users.
* Uncheck to **temporarily hide** it.

4. **Save and Close**

> **Note:** **Repeat** the procedure for each NFC tag scan point you need to create.

## Edit Scan Points

Follow these steps to update any **existing** scan point (QR code or NFC tag):

1. **Click** the name in the QR Code you want to edit.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/fd9c845d782cdbccb655b620ebfd044fba1941f2dd5c875f2aa709e2b72a23e6-image.png" />

2. **Modify the Current Data**

* **Scan-point ID**: Must be part of a sequential order and represent the scan point (QR or NFC) and once configured **can not be modified.**
* **Name**: A quick identifier to help locate it.
* **Description**: Extra details (location, room number, distinctive features).
* **Time Interval**: E.g., “once per hour,” prompting periodic scans.
* **Predefined Tag**: Associate an existing tag to assist with segmentation or searches.
* **Task/Form Association**: Choose whether to link the scan point to an existing **task** or **form** (must be **active**).
* **Active Box**: If checked, makes the scan point visible to users.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/ebdd9352df59d5f3a21235f97aad51942372ec1a9d438d8ebdf0f0c95ffcd278-image.png" />

4. **Save and Close**.

## Delete Scan Points

1. **Check** the scan point(s) you wish to remove

   * You can select **multiple** scan points at once.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c99688a7db9130eb1604dd327872a6f3a18c543c80325b1b9a5dccbb3d36ddc3-image.png" />

   <br />

2. **Click “Delete.”**

   * All selected scan points will be discarded.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/6d35f9516e10060fa9ac261d6a93ad572cf77db888b2df7f26827eced3da36d7-image.png" />

   <br />

3. **Confirm** and **close**

   * Verify the count of selected scan points matches what you intend to remove.
   * Click **Delete** to finalize.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/8779cf3ff836c906c74b4254df7a7c3ace4e39c8217467dd26d1f68f6370a19a-image.png" />

   <br />

## Export Scan Points

Exporting scan points to an **Excel file** can help you manage data offline or share with others.

1. **Click** the **“Export"** button.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/179f0399a76b5afcefd8768bfe473d83bd13edb70518733a897f5372b3cc902e-image.png" />

2. **Export** the Excel file. Choose **all data** or only the **current view**. Export **All Data** exports all the required information in the format necessary for importing, including every column needed for the process. In contrast, **Export Current View** exports the data exactly as the user has configured it, preserving the applied filters, sorting, and the order of columns as seen in the current view.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/8cceee5ac145703fd226636b0538ee35a035d43818e99c72d7c30606f45d0357-image.png" />

> **Note:**
>
> * If the file is **within size limits**, it will download directly to your computer.
> * If it **exceeds size limits**, it will appear in the **“[Downloads](https://mobohubb.readme.io/docs/downloads#/)”** section on the platform.

## Import Scan Points

If you have **multiple scan points** to add at once, you can **import** them from an Excel template. Follow these steps to speed up your setup process:

1. **Click** the **“Import”** button.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/d4b945de4e1f651cadedb44bea1dc18d4c390da1b5382d429b79b23785150710-image.png" />

2. **Download the template** to fill in your scan point data. (Each row represents one scan point.)

<Image align="center" border={true} caption="Download Template" src="https://files.readme.io/bc4eb50a8d725ae6587b8b5c5645fd3a5eec54327a016ba8f78fd633d241fa3d-image.png" width="80% " />

<Image align="center" border={true} caption="Template" src="https://files.readme.io/fab1e239dc979ebb9d832dec09f1ef23ddba92fa8319667853d402183a3e5037-image.png" width="80% " />

3. Send the completed template with the required information to [support ](https://mobohubb.zendesk.com/hc/en-us/requests/new)so that we can assist you with the import process.