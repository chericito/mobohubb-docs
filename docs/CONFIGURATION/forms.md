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
* **How to Export and Import Your Data** in Excel format for offline analysis or record-keeping

# Forms Field Type Descriptions

Below is an overview of available field types for forms. Each field type defines the **format** and **input** of data you can collect:

| **Field Name**   | **Description**                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------- |
| **Checkbox**     | Allows the user to select or deselect an option. There’s no limit on how many boxes can be checked. |
| **Colored Text** | Displays text in a specific color for emphasis.                                                     |
| **Date**         | Lets the user pick a date via an interactive calendar.                                              |
| **Device**       | Displays a devices list.                                                                            |
| **Email**        | Restricts input to a valid email format.                                                            |
| **Hyperlink**    | Displays text that links to another web page or resource.                                           |
| **Password**     | Masks user input for secure entry.                                                                  |
| **Personnel**    | Shows a list of users.                                                                              |
| **Radio**        | A single-choice field (commonly known as “radio button”).                                           |
| **Read-only**    | Displays text that cannot be edited by the user.                                                    |
| **Scan**         | Allows the user to scan a QR code or NFC tag.                                                       |
| **Select**       | Lets the user pick an option from a drop-down list.                                                 |
| **Signature**    | Enables the user to draw a signature.                                                               |
| **Tags**         | Lets the user select one or more tags.                                                              |
| **Text**         | A single-line free text input.                                                                      |
| **Text area**    | A multi-line text field for longer inputs.                                                          |
| **Time**         | Lets the user pick a time via an interactive clock.                                                 |

# Field Types Setup

When creating forms or checklists in **mobohubb**, you can choose from a variety of **field types** to collect or display information. Each field type serves a different purpose, from basic text input to advanced scanning or conditional display logic.

***

### Checkbox

Allows the user to **select** or **deselect** an option. Multiple checkboxes can be checked at once, offering flexibility when you need more than one answer.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/bf8a11133b6aece122470c39d865fca1d5335ad9df509e7c6c1c9949d3d2491d-image.png" />

**How to set up:**

1. **Field Name (Title)** – Provide a label for the checkbox group.
2. **Values (Comma-separated)** – List the choices separated by commas.

***

### Colored Text

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/b99c7a2dfc8bbb90e499cda122d00729c2bef67b230b0e22d4138d7abd8fa86f-image.png" />

Emphasizes text by displaying it in a specific color.

**How to set up:**

1. **Field Name** – Enter the text you want to highlight.
2. **Font Color** – Choose a color from the dropdown menu.

***

### Date

Lets the user pick a **date** via an interactive calendar.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/383d7e88e3266ccd6053dbb598f388aa3b47f51c0bfdfafd6a69b5f7b4dc8577-image.png" />

**How to set up:**

1. **Field Name** – Provide a label for the date field.

***

### Device

Displays a list of **devices** (smartphones, tablets, etc.) recognized by mobohubb.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/7e89df96c5aa2c109febd478dfc8c3de8b1fc33f8eb63a8fe588e3ca674d29a4-Screenshot_2025-04-18_at_3.31.17_PM.png" />

**How to set up:**

1. **Field Name** – Give a name to the device field.

***

### Email

Restricts input to a **valid email format**.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/d76f206e43504fc017537634df43c36233dfca0e89dc041d7ce2bc99edc746c9-image.png" />

**How to set up:**

1. **Field Name** – Provide a label for the email field.

***

### Hyperlink

Displays text that links to another web page or resource.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/50e8620ee1419751a78d37b8d829ee566e6237d15e1eb5032ab8ca5fe7484fca-image.png" />

**How to set up:**

1. **Field Name** – Enter the text that will appear as the link.
2. **Values** – Include the URL that the text should link to.

***

### Password

Masks the **user input** for secure entry (e.g., sensitive codes).

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/434a4cb6c6f0836ae37efe9eefced11a4e7497475e8b48f8efbc6eb1acf9e244-image.png" />

***

### Personnel

Shows a list of **users** registered in **mobohubb**. They can be associated with a particular tag for filtering.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/ebec3493deb708d8fd5b35b7d5145f6cbbcc7a18c1dbeff6b209d8afd01b64bf-image.png" />

**How to set up:**

1. **Field Name** – Provide a label for this field.
2. **Tag** (optional) – Associate the field with a predefined tag if you want to filter the user list.

***

### Radio

A single-choice field (often called a **radio button**). Users can select only **one** option. For **Select** or **Radio** fields, you can activate “conditional” to display more fields based on user selections.

<Image align="center" border={true} caption="If the user chooses &#x22;Phone&#x22;, they will be required to complete the &#x22;Device's OS&#x22; step." src="https://files.readme.io/781479304152318f704de63d5885fa4d6bf6b9782bf07965da07f905186b1333-image.png" width="30% " />

**How to set up:**

1. **Field Name** – Provide a title for your radio group.
2. **Values (Comma-separated)** – List each choice separated by commas.
3. **Conditional** (optional) – Show additional fields if a user chooses a specific option. If a user completes a certain action, then another step is triggered.

***

### Read-only

Displays text that **cannot** be edited by the user.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/ee5ad75c3019ca40a36c5d3a05beaf0be5e70842cbbeefa39e99408979ac11fe-image.png" />

**How to set up:**

1. **Field Name** – Enter a label for the field.
2. **Values** – Specify the text to display.
3. Mark **include** if you want the text visible in the forms.

***

### Scan

Allows scanning a **QR code** or **NFC tag**.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/7448cb6d1716000898aa9f3924ce09556716235f19d4f94e24f171871977f8fc-image.png" />

**How to set up:**

1. **Field Name** – Provide a label for this field.

***

### Select

Lets the user pick an option from a **drop-down list**. You can also activate a “conditional” option to show more fields when a user selects a specific value.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/19b450bf0d90cea97c712d231e8679d98e4755f410ef27faa50e3b1f73893004-image.png" />

**How to set up:**

1. **Field Name** – Label the drop-down.
2. **Values (Comma-separated)** – List each selection item by item.
3. **Conditional** (optional) – Reveal extra fields based on the user’s choice.  If a user completes a certain action, then another step is triggered.

***

### Signature

Enables the user to **draw** their signature on the form.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/487cbcbd12a4945256652693ac561e404f64f500fdd80a73b651f9f446a121a3-image.png" />

**How to set up:**

1. **Field Name** – Provide a name for the signature field.

***

### Tags

Lets users pick one or more tags from a predefined list.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/dea554c425b6ebb5e3b3fd5ebd6af6044605af685b2c36c7819a5c592432dc23-image.png" />

**How to set up:**

1. **Field Name** – Provide a label.
2. **Tag Source** – Make sure the tags are already created in mobohubb.

***

### Text

A single-line **free text** input box.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/bce0e5b3b3a411134f69e0a2a6c13368ff9bae3aead304cfb1117e43b3e05113-image.png" />

**How to set up:**

1. **Field Name** – Title for the text field.

***

### Textarea

A **multi-line** text box for longer input.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/254304fbdb4a7812cf235ffe06b8b358be4937cc1ab849bc2fe2b88eca9e4bdb-image.png" />

**How to set up:**

1. **Field Name** – Provide a title for your text area.

***

### Time

Lets the user pick a **time** via an interactive clock.

<Image align="center" className="border" border={true} width="30% " src="https://files.readme.io/405e744eb8b5160463165d7df8265f81348f7e04c30fcd8ec649da3338dcf732-image.png" />

**How to set up:**

1. **Field Name** – Provide a label.

***

By combining these field types, you can create **tailored** forms and checklists for a variety of processes—anything from simple text capture to scanning codes and gathering signatures. This flexibility ensures each form is optimized for the data you need to collect within **mobohubb**.

***

## Add Forms or Checklists

1. **Navigate to the Portal’s Top Menu** and select **Settings** from the dropdown.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/84271ddfd277b67b32b0addce24e9e728b4ac48763aa0b92a63a0cf8c52f9a50-Screenshot_2025-04-03_at_12.41.34_PM.png" />

2. From the **Configuration** section, select **Checklists**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/1fd09da005088e0f98c1a348b43b1334ca734726974fed90792a15ba91e31c6b-Screenshot_2025-04-22_at_11.07.57_AM.png" />

2. **Click “Add New”.**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/ce4d88dce3703930a28726292f94ce5ecc56f5b5cdadbfb882e2cb5dba9f256d-Screenshot_2025-04-22_at_11.10.22_AM.png" />

3. **Fill in the Form Information**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/d9305ff4356192fe0957b1fee24696a5b3a66104b85a1af37fcf36061c0a3f34-Screenshot_2025-04-22_at_11.15.23_AM.png" />

* **Prefix**: A short, unique code (letters, numbers, symbols).
* **Name**: The form’s title—clear and descriptive.
* **Tag**: Select a predefined tag if needed.
* **Visibility**: Choose **web app**, **mobile app**, or both.
* **Assign Users**: Decide who can complete this form (individuals or groups). If left empty, it will be available for everyone.
* **Activate**: Check the box to enable the form immediately or leave it unchecked to hide it.

5. **Click “Next”** to Go to “Form Fields”
6. **Fill In the Form Fields**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/878520562f2476aa6a19b054fc3db4b8afd681dbb0941b2c61aaeffac70270c2-image.png" />

* **Add New Fields**: By default, one field exists. Click **“Add new”** to add more.
* **Configure Field Type**: Choose from text, date, time, select, checkbox, radio, signature, scan, etc.
* **Field Name**: The label visible to users (e.g., “Employee ID,” “Comments”).
* **Required**: Mark fields as required (checkbox) or optional.
* **Conditional Fields**: For **Select** or **Radio** types, activate “conditional” to display additional fields based on user choices.

5. **Click “Next”** to Go to “Advanced Options”
6. **Fill In Advanced Options**

<Image align="center" className="border" border={true} src="https://files.readme.io/2cc2d0c9c6b0977c24d4bacea8607ed414f28acad6210883a0a9b8e4ed60dac9-image.png" />

* **GPS Coordinate**: Enable or disable geolocation for your form.
* **Site Map**: Upload an image as a reference at the top of the form.
* **Media Options**: Allow photos, audio, video, attachments, or scans.
  * **Mandatory Media**: Check if a photo/audio/video is required or optional.
  * **Camera/Gallery**: Let users capture media with their device or choose from gallery (or camera-only mode).

5. **Immediate Notification** *(Optional)*

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/213727a77f6c4195dea136e27937f49a8485e95ed874b6cfadb630e5b9c39472-image.png" />

* Sends an **email alert** upon form submission.
* Specify **recipients**, **subject**, **body**, **format** (PDF, HTML, Excel), and **attachment name**.

11. **Save** and **Activate Preview**

* Finalize your form settings and see how it **looks** (especially on mobile).

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/25beb2061280b5ca932bd4010385bf4858cc7d78c1600ec08a66bdf7f74058dc-image.png" />

<br />

> **Note:** The preview reflects how your form or checklist will appear in the **mobile application**.

Once complete, your **form or checklist** can be accessed by the selected users, who can fill it out according to its defined rules and constraints.

## Edit Forms or Checklists

1. **Select** the form(s) or checklist(s) to modify

   * You can use filters to locate the one you want.
   * **Note:** Only one form/checklist can be edited at a time.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/a7505a5122393d4ab5428b54f22a02ea69facb4a1f50d7d10242b30000f8ee52-image.png" />

2. **Click** **“Edit.”**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/b4f598273f33b184f11826cdcd2572d56c635888c1e338e8b6a6099706b0cfe3-image.png" />

3. **Modify** the current data

* **Form Information**: Update prefix, name, tags, visibility, or assigned users.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/420a42bbd4821b182f6842909e9cdf555bf56f0c0c7e15b34c268148dfdefe7f-image.png" />

* **Form Fields**: Add or remove fields, change field types, names, mandatory status, or conditional settings.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/cbc58a3fba1157143542aa2a84081f798cc5ca72ddb9878e6a7e1489c340d8ea-image.png" />

* **Advanced Options**: Adjust GPS usage, site map, media settings, or immediate notification preferences.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/64d50f5b4e8c92912fa845384d628f1c313a1d0f1aa8cffc190448119b892634-image.png" />

4. **Save and Preview**

* When you click **“Save,”** you’ll automatically see a **smartphone preview** of how the form/checklist looks on mobile.
* **Close** the preview to return to **Forms/Checklists Management**.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/6b06f804e42a89c6d3fdc6d2d9be843fcbde461c4b3a0a34262e4986c343274f-image.png" />

<br />

> **Note:** The preview reflects the mobile app layout for the form or checklist.
>
> <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/bc5d0d5e7bad7a609d60c72a9393e3cccf4a2d7dc504c1b27ca4a997cab316cd-image.png" />
>
> <br />

## Delete Forms or Checklists

1. **Select** the items to remove

   * Use filters to find them easily.
   * You can select **multiple** forms/checklists at once.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/ada95498d2eb7901d0f653b134024a24269b6a471e5cb7885012d227b24fda8b-image.png" />

   <br />

2. **Click “Delete.”**

   * All selected forms/checklists will be discarded.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/953dbed0f7ae271e113d3bbeb01e6229c4d41708d0e8f82a0f70bbe28156bb76-image.png" />

   <br />

3. **Confirm and Close**

   * Verify the count of forms/checklists matches what you intend to remove.
   * Click **Delete** to finalize.

   <br />

   <Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/9eb7cb591342b69bb354501bc932ccaf1aad10838373f1185df17d4dcf0e5398-image.png" />

   <br />

***

## Export Forms or Checklists

To export forms/checklists (e.g., for archiving or analysis):

1. **Click “Export”.**

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/c22864de96e4856d5d9de8ef3382cd1eee07d1dcd24d8eab9bbc892c0a5329c9-image.png" />

2. **Choose** which data to export

* You can typically export **All** information from the current view.
* If the file is within size limits, it will **download** to your computer in Excel format.
* If it exceeds size limits, check the **“[Downloads](https://mobohubb.readme.io/docs/downloads#/)”** option in the platform.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/fd4774fb2bf5eb163345201bffe5e167caa8c4d7ebb0d03209a30aa08ceea520-image.png" />

Once complete, you’ll have an Excel file containing all relevant data for your forms or checklists.

## Import Forms and Checklists

1. **Click** the "Import" button.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/f8d134ccc7b2a3b329cff6675186eeb9e4279c50a1a73f05e33ed70276dfe1f5-FBD2CFA2-D598-4586-AC7B-2F745688CDD2.png" />

2. **Press** "Download Template".

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/24c0f991b7e956102ba80f1afe574d149c6b606047d3cd082269f01d2a582077-88479D85-361C-4701-B98D-4BB10E2D2771.png" />

3. **Fill** in the template.

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/e99e91eecbf9d90713b331f8107227866c7db7ac25b04e6324503a38d9a16163-6BD67DA0-4B7C-449A-B2C9-328ACFC466D7.png" />

4. Send the completed template with the required information to [support ](https://mobohubb.zendesk.com/hc/en-us/requests/new)so that we can assist you with the import process.