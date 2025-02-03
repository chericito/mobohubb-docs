---
title: Scan Points
deprecated: false
hidden: false
metadata:
  robots: index
---
A **scan point** is an element that can be read with a mobile device to obtain information. Mobohubb supports two types of scan points: **QR codes** and **NFC tags**. These allow you to manage your locations—such as **sites, zones, or checkpoints**—in a structured way. For each site you create, decide whether you'll use **QR codes** or **NFC tags** so employees can easily scan them in the field.

* **Tip:** Make sure you’ve identified your **places of interest** before defining any scan points.

***

## Add a QR Code Scan Point

Follow these steps to create a new scan point associated with a **QR code**:

1. **Navigate to the Portal’s Top Menu**\
   ![](https://files.readme.io/609510573f5fffaea1ccca22de8106edf6fe46e201c34957cf08d17e4d700ea7-image.png)

2. **Go to “General Settings”**
   * In the top menu, click **Settings** (or use the **side menu** to find the **General Settings** option).\
     ![](https://files.readme.io/5d5d2925ad1d70a55100292938684e9c22a423d62a9049dd327324f456705e8e-image.png)

3. **Select “Scan-Points Management”**
   * Within **Configuration**, click on **Scan-Points Management**.\
     ![](https://files.readme.io/51e405b15c0b4df74a6e6833d0ce907354f15ff7096497f02aabcb69ceb23e08-image.png)

4. **Click “Add New”**\
   ![](https://files.readme.io/342fddd36289e74c1519f50a65489c3e9b6ec371a178536c7916693422efa24e-image.png)

5. **Fill in the QR Code ID**
   * Use a unique, sequential identifier (e.g., `Location001`, `Location016`). This ID will help you organize and differentiate scan points.
   * Refer to **[How to create a QR code](#)** for details on generating the actual QR image.\
     ![](https://files.readme.io/8280a8273c0216d1c8f6e361e9bc52c20ddb8ea8989772f2ec98da51885b10aa-image.png)

6. **Add a Name**
   * Provide a clear name (e.g., “Security Camera Room”) to quickly locate the scan point.\
     ![](https://files.readme.io/f1af3e37760526881563cb81233fe42143ca2afd7af19ddc2d1254d30f61015f-image.png)

7. **Add a Description**
   * Include room numbers, distinctive features, or exact locations to help users find it easily.\
     ![](https://files.readme.io/d5efb09b757b71dfd1b65dd16c88463654400ea9559eec247666164911852586-image.png)

8. **Choose a Time Interval**
   * Enter the time in **HH:MM** format (e.g., `08:00`) if you need periodic scans or want to classify your scan points for log comparisons.\
     ![](https://files.readme.io/b36b4b9582d9ccb4447f59d34b49c040ef563215d111e6583a502886175366f3-image.png)

9. **Associate a Predefined Tag** *(Optional)*
   * If you’ve created tags beforehand, select one in the dropdown.
   * **Tags** help segment data and simplify searches.\
     ![](https://files.readme.io/c8b4acd1b49cc62e15fd13f4ad4a81ee5eb04bcc7153b7b140f822e3c79aafeb-image.png)

10. **Link to a Task or Form** *(Optional)*

* To associate this QR code with an **existing** task or form, select it from the dropdown menu.
* Tasks/forms must be **active** to appear here.
* If you do not wish to associate anything, simply proceed to step 11.\
  ![](https://files.readme.io/4bb14e9fce3aa76164dcd36e9b9d7d12ad6b482b81e0680a16231d038955e2c9-image.png)

11. **Mark as Active**

* Check the box to make this scan point visible to other users.
* If unchecked, it remains hidden but can be activated later.\
  ![](https://files.readme.io/4aa677d41faddf691c661084b009da437a714c9be35900baae075a59d0d2b126-image.png)

12. **Save and Close**\
    ![](https://files.readme.io/d3087ea1b86a1bd7f759ef5d37edc20f5f0fafd08770fa6f04441170d4f6662c-image.png)

> **Note:** **Repeat** these steps for each scan point you need to create.

<br />

## Add an NFC Tag Scan Point

Follow these steps to create a new scan point associated with an **NFC tag**:

1. **Navigate to the Portal’s Top Menu**\
   ![](https://files.readme.io/f0ad9f10a15a691cb8b1e75313f9602c21955e6418003d0f66193cec06d7c223-image.png)

2. **Go to “General Settings”**
   * In the top menu, **click** **Settings** (or use the **side menu** to find the **General Settings** option).\
     ![](https://files.readme.io/03e5c9995a1e496ce44eb663904db9da8d87bf9bf2462c0237bf1642e5c8e920-image.png)

3. **Select “Scan-Points Management”**
   * Within **Configuration**, **click** on **Scan-Points Management**.\
     ![](https://files.readme.io/baf85da3bd651b42e1de2bcada425e52f4f0d0166c82625e83eb83166ff2de2f-image.png)

4. **Click “Add New”**\
   ![](https://files.readme.io/79840a40c1d29a79398427ee944a88e32311de21dd0bc5af3fb40143fd67dc40-image.png)

5. **Fill in the NFC Code ID**
   * NFC (Near Field Communication) tags are **small, passive devices** containing a microchip and antenna.
   * If you already have **configured** NFC tags, assign a **unique, sequential** ID (e.g., `Location001`, `Location016`), aligning them with other scan points.
   * Alternatively, **scan** any unassigned NFC tag with the mobile app, then update its details in the portal.\
     ![](https://files.readme.io/fed242b601c6513ddf85b0f89a79db12088c3ccb960d3a736c34ef7b837842bf-image.png)

6. **Add a Name**
   * Provide a clear identifier (e.g., “Security Camera Room”) for quick reference.\
     ![](https://files.readme.io/55feacf0361054cf96b11f8decf94565bbe5b009b5467399f53e77ecf5eb6e2d-image.png)

7. **Add a Description**
   * Include any relevant details such as room number or distinctive features.\
     ![](https://files.readme.io/bb5aa7f72f7041ea6598067dc1240776ac049990b99485133d177845af23c253-image.png)

8. **Choose a Time Interval**
   * Use **HH:MM** format (e.g., `08:00`) to classify periodic scans or log comparisons.\
     ![](https://files.readme.io/15d458422eb08257b5faec60bd7d00cd375ca35baa09e84e8701ca1aecfcbc3d-image.png)

9. **Associate a Predefined Tag** *(Optional)*
   * If you have previously created tags, assign one here to **segment data** and simplify searches.\
     ![](https://files.readme.io/49d9b0e9cc975ddd0a287db8fe96bccc8c97fef24b598280e9e1c1a5044ddff4-image.png)

10. **Link to a Task or Form** *(Optional)*

* If needed, associate this NFC tag with an **existing** task or form (they must be **active**).
* If you don’t wish to link anything, go to step 11.\
  ![](https://files.readme.io/b1e723a8fa4ccd74139b1b364391f6fb19e5fb079a6e9cc17f069c9c0759a726-image.png)
  ![](https://files.readme.io/dde4ae4262408077d6c1f987bcf46826e4955d9e7775df5d01aa1c7c38963a2f-image.png)

11. **Mark as Active**

* Check the box to make this scan point visible to users.
* Uncheck to **temporarily hide** it.\
  ![](https://files.readme.io/b283000fa02ae27b4cdd5ba3c0dd72505b28588238ce7da6bb6adb2c2d182782-image.png)

12. **Save and Close**\
    ![](https://files.readme.io/4743a6b19da096c410ed4d2d09e6ecb0e6b631d0b17256c087bc0d63edd7b9f9-image.png)

> **Note:** **Repeat** the procedure for each NFC tag scan point you need to create.