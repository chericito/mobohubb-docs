---
title: Security Groups
excerpt: >-
  Learn how to manage Security Groups in mobohubb—an essential feature for
  assigning permissions, and site access. This guide covers the available
  groups, how to view and how to add or remove users within each group for
  optimal security control.
deprecated: false
hidden: false
metadata:
  robots: index
---
Users are individuals who can access the portal and perform actions based on their role and permissions. Security Groups define these roles and permissions, ensuring that each user has the appropriate level of access. In mobohubb, pre-established security groups are fixed—they cannot be modified or deleted; you can only add or remove users from them. Furthermore, security groups are configured on a per-site basis, meaning the same group (often named with the site included) will appear across different sites within your organization. This site-specific configuration helps distinguish between mobile app users and portal users. In this new version, "People" and "Portal users" are simply referred to as Users. Updating security groups appropriately is crucial to ensure that each user is granted the correct permissions for the specific site they belong to.

***

## **Available Security Groups**

<br />

<Cards columns={2}>
  <Card title="Organization Administrator" icon="fa-user-shield">
    Full access to the **organization** and **all sites**. This is the most powerful group, controlling the entire Mobohubb portal.
  </Card>

  <Card title="Site Administrator" icon="fa-user-cog">
    Complete control over a **single site**, including all site-related settings. Cannot modify other sites.
  </Card>

  <Card title="Billing Administrator" icon="fa-credit-card">
    Access to **billing settings**, including subscriptions and financial details.
  </Card>

  <Card title="Editor" icon="fa-edit">
    Can edit most **site settings** in the mobohubb portal, but does not have full administrative privileges.
  </Card>

  <Card title="Read-only" icon="fa-eye">
    Can **view** site settings and data but **cannot** make any modifications.
  </Card>

  <Card title="Mobile" icon="fa-mobile-alt">
    Primarily uses the **mobohubb mobile app** for tasks like scanning QR codes, filling out reports, and communicating. This group also permits **limited access** to the **web app** (webapp.mobohubb.com), but it does not grant full portal modification rights. The user **cannot** perform administrative changes or advanced configurations in the portal.
  </Card>
</Cards>

You can view the specifics for each group—name, description, permissions, and site associations—in the **General Settings** → **Security Groups** area.

<Image align="center" className="border" border={true} width="40% " src="https://files.readme.io/469c67e94d0e87e58b2db5e0b066231afbcf95f1212696a7cea35aa1bbe7c6a7-206E4F70-E9AC-4764-A5D4-82695B93289D.png" />

<br />

<Image align="center" className="border" border={true} src="https://files.readme.io/3e890c2a7d09c845fc7501e8b973df14a03ede8bed214cb8c936602f46c00506-image.png" />

***

### **Users Tab**

Here, you can see all the users associated with a particular security group. From this tab, you can easily **delete** or **add** users to update security groups as needed.

<Image align="center" className="border" border={true} src="https://files.readme.io/f947aa9db0c3ed1bfbcd8002cb7704d062fda0ede39c3a7778d8d500433a1502-image.png" />

***

### **Permissions Tab**

Displays the group’s associated **permissions**, which cannot be modified.

<Image align="center" className="border" border={true} src="https://files.readme.io/6e5a5f0068dc39ed2d4a8cf7c72e433dd2654b34acb3e3f1c9986d352a5d961a-image.png" />

***

### **Site Associations Tab**

Lists all **sites** linked to the security group.

<Image align="center" className="border" border={true} src="https://files.readme.io/87fd4254388cf82f4599af20933fcc94666a930bafb98e9377060191ef9989c9-image.png" />

***

## **Viewing or Modifying a Security Group**

1. **Navigate** to the Portal’s Top Menu and **Click** on **Settings**.

<Image align="center" className="border" border={true} src="https://files.readme.io/84271ddfd277b67b32b0addce24e9e728b4ac48763aa0b92a63a0cf8c52f9a50-Screenshot_2025-04-03_at_12.41.34_PM.png" />

2. In the **Site Administration** section, select **Security Groups**.

<Image align="center" className="border" border={true} src="https://files.readme.io/beceed8dc52e3836dd59d77b91dcc45a18405e0d04365aa985c8efbe9ee2fe71-Screenshot_2025-04-10_at_12.22.28_PM.png" />

3. **Identify the Desired Group** and **Click** on the group's name you want to edit.

<Image align="center" className="border" border={true} src="https://files.readme.io/7b4189e6029272a2651b376b78b4f5747d01ed1df78ed44f2bc9d0d9bfc02719-image.png" />

> **Notes:**
>
> A user may belong to **more than one** security group.
>
> **Only one** group can be modified at a time.

4. **Go to the "Users" Tab**

<Image align="center" className="border" border={true} src="https://files.readme.io/7b02df1c976b781dea2bda44221b4cf711d05a1da420b583cd3d8f3a984016ac-Screenshot_2025-04-10_at_12.35.08_PM.png" />

4. **Review or Modify** which users belong to this group.

***

## **Add Users to a Security Group**

1. **Verify Users**

   * On the "Users" tab, click **Add User**.

   <br />

   <Image align="center" className="border" border={true} src="https://files.readme.io/54e4e423a9a8339823dd9f7a82c0c6cf802480422c632c4976ac174e182d2f4f-Screenshot_2025-04-10_at_12.37.29_PM.png" />

   <br />

2. **Check** the users you want to add.

<Image align="center" className="border" border={true} src="https://files.readme.io/39c926919497916db182440411d4fcbee2475456c9771ecd956e15c43e765d3a-Screenshot_2025-04-10_at_12.39.42_PM.png" />

3. **Save** to Include Them in the Group.

![](https://files.readme.io/b182ad9357a44b899de36ae56d5ba6498b1e830f32c25f2083c96ced01c7a924-Screenshot_2025-04-10_at_12.39.42_PM.png)

***

## **Remove Users from a Security Group**

1. **Select** the Users to Remove\
   ![](https://files.readme.io/57785d673f0feea472c9b074e29e11e6c0a37b47b66e9710ecb22ffb23a77376-image.png)

2. **Click "Save"** to Exclude Them\
   ![](https://files.readme.io/56cc3544d2c78b1379950181c6babf17cfe027fb19e82934ab97469ba93e2537-image.png)

3. **Save Changes and Close**\
   ![](https://files.readme.io/6924c88e2b327618b1a62e6d38a27882f1121f58621d9a48ca1b891e580887ea-image.png)

> **Note:** **Repeat** this process for each security group that needs updating.