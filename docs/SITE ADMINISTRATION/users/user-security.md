---
title: User Security
excerpt: >-
  Learn how to modify user permissions and access settings in mobohubb by
  updating roles, security groups, and device configurations via the user
  profile's Security tab. This guide ensures that each user has the correct
  access to the portal and mobile app.
deprecated: false
hidden: false
metadata:
  robots: index
---
# User Security

You can easily modify the permission and usage levels so that a user can access the portal, the mobile app, or both. You can configure roles and tags to associate these parameters with the user, allowing for quick identification and control of the associated device and actions. Please note that to see options in the Role and Tags fields, these must be created beforehand; if not, no options will appear.

Additionally, permissions can vary in the level of actions that a user can perform within the platform.

## Security Groups and Permissions

Users can be assigned one or more security groups, each defining a specific set of permissions:

* **Organization Administrator**: Full control over the entire mobohubb portal, including all sites and settings.
* **Site Administrator**: Complete access to a specific site, with the ability to modify site-related information, though not settings for other sites.
* **Billing Administrator**: Manages billing settings such as subscriptions and payment methods.
* **Editor**: Can edit most site settings and content within the portal.
* **Read-only**: Can view site settings and data but cannot make any modifications.
* **Mobile**: Accesses the platform via the mobile app; permitted to perform actions like scanning, filling out forms, and completing tasks, but cannot alter web portal settings.

> **Note:** A user can have more than one active security group, allowing for a flexible combination of permissions based on their responsibilities.

## Steps to Update User Security Settings

1. **Navigate** to the portal’s top menu.

2. **Go to "General Settings."**\
   Click **Settings** in the top menu to access various configuration options for your organization. You may also use the side menu to access General Settings.

3. **Navigate** to the **"Users"** section. In the Site Administration area, click on **Users**.

4. **Select** the user you wish to personalize by checking the corresponding box.
   > **Note:** You can modify only one user at a time, so do not select multiple users.

5. **Click** on the **"Edit"** button located on the right side of the interface, or click on the **User Name**.

6. **Click** on the **"Security"** tab.

7. **Fill in** or modify the following fields:

<Image align="center" className="border" border={true} width="80% " src="https://files.readme.io/75b283f5490cdd7df491c30f717576d829712ca6cb9e3d1e1a414105626b8126-image.png" />

* **Role**: Update the user’s role. *Remember: Role options appear only if roles have been pre-created in the Role configuration menu.*
* **Security Groups**: Assign one or more security groups to the user to define their access and permitted actions. Each group provides different levels of permissions as listed above.
* **Device(s)**: Specify the devices from which the user may access the platform.
* Additional settings for mobile and portal web permissions can be configured as needed.

1. **Click** the **"Save"** button to apply your changes.

By updating these settings, you ensure that each user has the appropriate access rights and capabilities within mobohubb.