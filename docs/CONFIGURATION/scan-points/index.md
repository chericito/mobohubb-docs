---
title: Scan Points
excerpt: >-
  A comprehensive guide to setting up, managing, and organizing scan points (QR
  codes or NFC tags) in Mobohubb. Learn how to add, edit, delete, import, and
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

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/bd2470343f809e55eba36a5a4cfc1c44bb3e20872cb1ba9359a41074f7c3dbd8-C596D59F-73A3-4705-B690-4994AB9FA1D5.png" />

4. **Save** your changes to finalize the site’s configuration.

## Add a QR Code Scan Point

Follow these steps to create a new scan point associated with a **QR code**:

1. **Navigate to the Portal’s Top Menu**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/609510573f5fffaea1ccca22de8106edf6fe46e201c34957cf08d17e4d700ea7-image.png" />

<br />

2. **Go to “General Settings”**

* In the top menu, click **Settings** (or use the **side menu** to find the **General Settings** option).

<br />

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/5d5d2925ad1d70a55100292938684e9c22a423d62a9049dd327324f456705e8e-image.png" />

<br />

3. **Select “Scan-Points Management”**

* Within **Configuration**, click on **Scan-Points**.

<br />

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/51e405b15c0b4df74a6e6833d0ce907354f15ff7096497f02aabcb69ceb23e08-image.png" />

<br />

4. **Click “Add New”**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/342fddd36289e74c1519f50a65489c3e9b6ec371a178536c7916693422efa24e-image.png" />

<br />

5. **Fill in the QR Code ID**

* Use a unique, sequential identifier that matches the QR (e.g., `Location001`, `Location016`). This ID is case-sensitive and will help you organize and differentiate scan points.
* Refer to **[How to create a QR code](https://mobohubb.readme.io/docs/qr-codes#/)** for details on generating the actual QR image.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/8280a8273c0216d1c8f6e361e9bc52c20ddb8ea8989772f2ec98da51885b10aa-image.png" />

4. **Add a Name**

Provide a clear name (e.g., “Security Camera Room”) to quickly locate the scan point.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/f1af3e37760526881563cb81233fe42143ca2afd7af19ddc2d1254d30f61015f-image.png" />

5. **Add a Description**

* Include room numbers, distinctive features, or exact locations to help users find it easily.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/d5efb09b757b71dfd1b65dd16c88463654400ea9559eec247666164911852586-image.png" />

6. **Choose a Time Interval**

* Enter the time in **HH:MM** format (e.g., `08:00`) if you need periodic scans or want to classify your scan points for log comparisons. This is required for Time Studies, a function that demonstrates the scanning frequency of QR captures that have the time interval parameter marked; for example, how security patrollers perform their patrols, scanning each time they pass by the designated locations. Time studies enable you to confirm how frequently this scan was finished.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b36b4b9582d9ccb4447f59d34b49c040ef563215d111e6583a502886175366f3-image.png" />

7. **Associate a Predefined Tag** *(Optional)*

* If you’ve created [tags](https://mobohubb.readme.io/update/docs/tags#/) beforehand, select one in the dropdown.
* **Tags** help segment data and simplify searches.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c8b4acd1b49cc62e15fd13f4ad4a81ee5eb04bcc7153b7b140f822e3c79aafeb-image.png" />

8. **Link to a Task or Form** *(Optional)*. You can associate the scan point with an existing task or form. To mark that task or form as **complete**, the user must **scan** the point. This ensures the activity is tracked and verified in the system.

* To associate this QR code with an **existing** [task](https://mobohubb.readme.io/update/docs/tasks#/) or [form](https://mobohubb.readme.io/update/docs/tasks#/), select it from the dropdown menu.
* Tasks/forms must be **active** to appear here.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/4bb14e9fce3aa76164dcd36e9b9d7d12ad6b482b81e0680a16231d038955e2c9-image.png" />

9. **Mark as Active** (active by default)

* **Check** the box to make this scan point visible to other users.
* If unchecked, it remains hidden but can be activated later.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/4aa677d41faddf691c661084b009da437a714c9be35900baae075a59d0d2b126-image.png" />

10. **Save and Close**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/d3087ea1b86a1bd7f759ef5d37edc20f5f0fafd08770fa6f04441170d4f6662c-image.png" />

> **Note:** **Repeat** these steps for each scan point you need to create.

## Add an NFC Tag Scan Point

1. **Configure** the [NFC using the Mobile App](https://mobohubb.readme.io/v1.2/update/docs/nfc-mobile#/).
2. **Fill in the NFC Code ID**

   * NFC (Near Field Communication) tags are **small, passive devices** containing a microchip and antenna.
   * You can **scan** any unassigned NFC tag with the mobile app, then update its details in the portal.
   * **Do not** modify the Scan-Point ID for any NFC, this will make the NFC configuration useless.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/fed242b601c6513ddf85b0f89a79db12088c3ccb960d3a736c34ef7b837842bf-image.png" />

   <br />
3. **Add a Name**

   * Provide a clear identifier (e.g., “Security Camera Room”) for quick reference.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/55feacf0361054cf96b11f8decf94565bbe5b009b5467399f53e77ecf5eb6e2d-image.png" />

   <br />
4. **Add a Description**

   * Include any relevant details such as room number or distinctive features.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/bb5aa7f72f7041ea6598067dc1240776ac049990b99485133d177845af23c253-image.png" />

   <br />
5. **Choose a Time Interval**

* Use **HH:MM** format (e.g., `08:00`) to classify periodic scans or log comparisons.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/15d458422eb08257b5faec60bd7d00cd375ca35baa09e84e8701ca1aecfcbc3d-image.png" />

6. **Associate a Predefined Tag** *(Optional)*

* If you have previously created tags, assign one here to **segment data** and simplify searches.

<br />

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/49d9b0e9cc975ddd0a287db8fe96bccc8c97fef24b598280e9e1c1a5044ddff4-image.png" />

<br />

7. **Link to a Task or Form** *(Optional)*

* If needed, associate this NFC tag with an **existing** task or form (they must be **active**).
* If you don’t wish to link anything, go to step 11.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/dde4ae4262408077d6c1f987bcf46826e4955d9e7775df5d01aa1c7c38963a2f-image.png" />

&#x20;&#x20;

8. **Mark as Active**

* Check the box to make this scan point visible to mobile users.
* Uncheck to **temporarily hide** it.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b283000fa02ae27b4cdd5ba3c0dd72505b28588238ce7da6bb6adb2c2d182782-image.png" />

<br />

12. **Save and Close**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/4743a6b19da096c410ed4d2d09e6ecb0e6b631d0b17256c087bc0d63edd7b9f9-image.png" />

> **Note:** **Repeat** the procedure for each NFC tag scan point you need to create.

## Edit Scan Points

Follow these steps to update any **existing** scan point (QR code or NFC tag):

1. **Check** the box next to the scan point you wish to modify.

* Only **one** scan point can be edited at a time.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/fd9c845d782cdbccb655b620ebfd044fba1941f2dd5c875f2aa709e2b72a23e6-image.png" />

<br />

2. **Click “Edit.”**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/8c167e2deea57940441d0ef6c1fc25d2fc911b3766cebaa76f583d5426b0a33e-image.png" />

3. **Modify the Current Data**

* **Scan-point ID**: Must be part of a sequential order and represent the scan point (QR or NFC).
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

2. **Upload the File**

* If you have a **prepared spreadsheet**, upload it directly.
* If not, **download the template** to fill in your scan point data. (Each row represents one scan point.)

<Image align="center" border={true} caption="Download Template" src="https://files.readme.io/bc4eb50a8d725ae6587b8b5c5645fd3a5eec54327a016ba8f78fd633d241fa3d-image.png" width="80% " />

<Image align="center" border={true} caption="Template" src="https://files.readme.io/fab1e239dc979ebb9d832dec09f1ef23ddba92fa8319667853d402183a3e5037-image.png" width="80% " />

* **Upload** the completed file in the form.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/3434cf341530adf539a6d08f050650b76c26859b88cecd80bc21c6ec14fe74c3-image.png" />

* **Click** **“Save.”**

3. **Wait** for the import to finish.

* Depending on the **size** of your data, the import may take some time.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/277cf2d0926efe09b5ed2924f47fa1b0722e9aa1958158dbed4e2a77b2354510-image.png" />

4. **Confirm** new scan points
5. Once complete, the **new scan points** will appear in your **Scan-Points Management** list.