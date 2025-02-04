---
title: Forms and Checklists
excerpt: >-
  Discover how to create, edit, delete, and export forms or checklists in
  Mobohubb. Learn about available field types—from dates and signatures to
  conditional radio buttons—and advanced options like GPS, media uploads, and
  instant notifications to streamline your data collection process.
deprecated: false
hidden: false
metadata:
  robots: index
---
**Forms** and **checklists** are essential tools for gathering information or tracking tasks. A **form** collects data in a structured way, while a **checklist** details a sequence of steps that must be followed and verified. By setting up custom fields, specifying visibility, and adding optional features like GPS or media uploads, you can tailor each form/checklist to your organization’s needs.

***

**In this guide you'll learn**

* **How to Add New Forms/Checklists** with custom fields and user assignments
* **How to Edit Existing Forms/Checklists** and preview them on a mobile-like interface
* **How to Delete Multiple Items** at once to keep your workspace clean and organized
* **How to Export Your Data** in Excel format for offline analysis or record-keeping

## Forms Field Descriptions

Below is an overview of available field types for forms. Each field type defines the **format** and **input** of data you can collect:

| **Field Name**   | **Description**                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------- |
| **Checkbox**     | Allows the user to select or deselect an option. There’s no limit on how many boxes can be checked. |
| **Colored Text** | Displays text in a specific color for emphasis.                                                     |
| **Date**         | Lets the user pick a date via an interactive calendar.                                              |
| **Device**       | Displays the device name or type being used.                                                        |
| **Email**        | Restricts input to a valid email format.                                                            |
| **Hyperlink**    | Displays text that links to another web page or resource.                                           |
| **Password**     | Masks user input for secure entry.                                                                  |
| **Personnel**    | Shows a person’s name or role.                                                                      |
| **Radius**       | A single-choice field (commonly known as “radio button”).                                           |
| **Read-only**    | Displays text that cannot be edited by the user.                                                    |
| **Scan**         | Allows the user to scan a QR code or NFC tag.                                                       |
| **Select**       | Lets the user pick an option from a drop-down list.                                                 |
| **Signature**    | Enables the user to draw or upload a signature.                                                     |
| **Tags**         | Lets the user enter or select one or more tags or keywords.                                         |
| **Text**         | A single-line free text input.                                                                      |
| **Text area**    | A multi-line text field for longer inputs.                                                          |
| **Time**         | Lets the user pick a time via an interactive clock.                                                 |
| **User**         | Displays a username in a drop-down menu.                                                            |

***

## Add Forms or Checklists

1. **Navigate to the Portal’s Top Menu**\
   ![](https://files.readme.io/7bb76818925ec19d8c5ee4be1858c617c9891ea0df7c31fec25af5d756f0a697-image.png)

2. **Go to “General Settings”.**
   * Click **Settings** (top menu) or use the side menu.\
     ![](https://files.readme.io/2854be5e03f267054deac41012b3fc16d2a2f55209de2f1e18b525705d7e6903-image.png)

3. **Select “Forms/Checklists”.**
   * Within **Configuration**, click **Forms/Checklists**.\
     ![](https://files.readme.io/76cf06273a528befb56196cfb14c886d88d4504ab7c6d2860096c5cd2f1da24b-image.png)

4. **Click “Add New”.**\
   ![](https://files.readme.io/fa419ada315e0908048636b1e2a17f33ef616884f23bd04f353a3e4d9d1b4b65-image.png)

5. **Fill in the Form Information**\
   ![](https://files.readme.io/c4ad8226d197442dc503eb522e1a7a063f195d5a770d7667afad6778c46a3a74-image.png)

   * **Prefix**: A short, unique code (letters, numbers, symbols).
   * **Name**: The form’s title—clear and descriptive.
   * **Tag**: Select a predefined tag if needed.
   * **Visibility**: Choose **web app**, **mobile app**, or both.
   * **Assign Users**: Decide who can fill out this form (individuals or groups).
   * **Activate**: Check the box to enable the form immediately or leave it unchecked to hide it.

6. **Click “Next”** to Go to “Form Fields”
   * Saves your changes and moves you to the **Form Fields** tab.\
     ![](https://files.readme.io/f47816874addb5432123e5e81a0aa20538d9cc333efcad74b70527e0b4ab9f5a-image.png)

7. **Fill In the Form Fields**\
   ![](https://files.readme.io/bbb7f9908bd5b73e91aa5cc0d250022de564496116516f0ec3214e4b5069fd9f-image.png)

   * **Add New Fields**: By default, one field exists. Click **“Add new”** to add more.
   * **Configure Field Type**: Choose from text, date, time, select, checkbox, radio, signature, scan, etc.
   * **Name of the Field**: The label visible to users (e.g., “Employee ID,” “Comments”).
   * **Mandatory**: Mark fields as required (checkbox) or optional.
   * **Conditional Fields**: For **Select** or **Radio** types, activate “conditional” to display additional fields based on user choices.

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/5160de7263bc5b3ffcacc5fd90fbea329d904b93712c8e47ca42876f3d5fe110-image.png" />

8. **Click “Next”** to Go to “Advanced Options”
   * Again, saves your changes and moves to the final **Advanced Options** tab.\
     ![](https://files.readme.io/d7dec0b236911a4f7e9a0322471e86def43ce5aeb1c155c636ee13703981319b-image.png)

9. **Fill In Advanced Options**\
   ![](https://files.readme.io/5479781d7bd9ebc94c5a9c43e22eec6b642f9a4d47f1576441ed206713c9ef48-image.png)

   * **GPS Coordinate**: Enable or disable geolocation for your form.
   * **Site Map**: Upload an image as a reference at the top of the form.
   * **Media Options**: Allow photos, audio, video, attachments, or scans.
     * **Mandatory Media**: Check if a photo/audio/video is required or optional.
     * **Camera/Gallery**: Let users capture media with their device or choose from gallery (or camera-only mode).

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/77e73fffeda7d853bd9df571213ddb0a3cfe4492a77348883e69e52951237b7c-image.png" />

10. **Immediate Notification** *(Optional)*\
    ![](https://files.readme.io/8c18184d76bbfa6272f3c8dcd6c8d79da7137ff87b77e0d5f600b382eb3100b5-image.png)

* Sends an **email alert** upon form submission.
* Specify **recipients**, **subject**, **body**, **format** (PDF, HTML, Excel), and **attachment name**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/28bf9b479a77937efd9a387373cf216f688a9af5ff09dfdb590fd41e4897c796-image.png" />

11. **Save** and **Activate Preview**

* Finalize your form settings and see how it **looks** (especially on mobile).\
  ![](https://files.readme.io/819c942cc0cd7dfd6686ad85666ddcb734083933b9dfedc5d7e20523edb53328-image.png)

> **Note:** The preview reflects how your form or checklist will appear in the **mobile application**.\
> ![](https://files.readme.io/c7313f74f2b1d550297ccd5f6a76bd7991b62cf9d3030ebe96b0c6958cfcce8b-image.png)

Once complete, your **form or checklist** can be accessed by the selected users, who can fill it out according to its defined rules and constraints.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c7313f74f2b1d550297ccd5f6a76bd7991b62cf9d3030ebe96b0c6958cfcce8b-image.png" />

<br />

## Edit Forms or Checklists

1. **Select** the form(s) or checklist(s) to modify
   * You can use filters to locate the one you want.
   * **Note:** Only one form/checklist can be edited at a time.\
     ![](https://files.readme.io/a7505a5122393d4ab5428b54f22a02ea69facb4a1f50d7d10242b30000f8ee52-image.png)

2. **Click** **“Edit.”**\
   ![](https://files.readme.io/b4f598273f33b184f11826cdcd2572d56c635888c1e338e8b6a6099706b0cfe3-image.png)

3. **Modify** the current data
   * **Form Information**: Update prefix, name, tags, visibility, or assigned users.\
     ![](https://files.readme.io/420a42bbd4821b182f6842909e9cdf555bf56f0c0c7e15b34c268148dfdefe7f-image.png)
   * **Form Fields**: Add or remove fields, change field types, names, mandatory status, or conditional settings.\
     ![](https://files.readme.io/cbc58a3fba1157143542aa2a84081f798cc5ca72ddb9878e6a7e1489c340d8ea-image.png)
   * **Advanced Options**: Adjust GPS usage, site map, media settings, or immediate notification preferences.\
     ![](https://files.readme.io/64d50f5b4e8c92912fa845384d628f1c313a1d0f1aa8cffc190448119b892634-image.png)

4. **Save and Preview**
   * When you click **“Save,”** you’ll automatically see a **smartphone preview** of how the form/checklist looks on mobile.
   * **Close** the preview to return to **Forms/Checklists Management**.\
     ![](https://files.readme.io/6b06f804e42a89c6d3fdc6d2d9be843fcbde461c4b3a0a34262e4986c343274f-image.png)

> **Note:** The preview reflects the mobile app layout for the form or checklist.\
> ![](https://files.readme.io/bc5d0d5e7bad7a609d60c72a9393e3cccf4a2d7dc504c1b27ca4a997cab316cd-image.png)

***

## Delete Forms or Checklists

1. **Select** the items to remove
   * Use filters to find them easily.
   * You can select **multiple** forms/checklists at once.\
     ![](https://files.readme.io/ada95498d2eb7901d0f653b134024a24269b6a471e5cb7885012d227b24fda8b-image.png)

2. **Click “Delete.”**
   * All selected forms/checklists will be discarded.\
     ![](https://files.readme.io/953dbed0f7ae271e113d3bbeb01e6229c4d41708d0e8f82a0f70bbe28156bb76-image.png)

3. **Confirm and Close**
   * Verify the count of forms/checklists matches what you intend to remove.
   * Click **Delete** to finalize.\
     ![](https://files.readme.io/9eb7cb591342b69bb354501bc932ccaf1aad10838373f1185df17d4dcf0e5398-image.png)

***

## Export Forms or Checklists

To export forms/checklists (e.g., for archiving or analysis):

1. **Click “Export.”**\
   ![](https://files.readme.io/c22864de96e4856d5d9de8ef3382cd1eee07d1dcd24d8eab9bbc892c0a5329c9-image.png)

2. **Choose** which data to export
   * You can typically export **All** information from the current view.
   * If the file is within size limits, it will **download** to your computer in Excel format.
   * If it exceeds size limits, check the **“Downloads”** option in the platform.\
     ![](https://files.readme.io/fd4774fb2bf5eb163345201bffe5e167caa8c4d7ebb0d03209a30aa08ceea520-image.png)

Once complete, you’ll have an Excel file containing all relevant data for your forms or checklists.