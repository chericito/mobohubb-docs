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

1. **Navigate to the Portal’s Top Menu**\
   ![](https://files.readme.io/32a75929a740347cf39ef9e5eaa114504d70bd21f2206528a936f80c2af60c38-image.png)

2. **Go to "General Settings"**
   * Click **Settings** in the top menu (or use the side menu).\
     ![](https://files.readme.io/9d55b1cdab6f60118bca47b5831c7fba803cd510267a956d6f68ec7ee4f75f89-image.png)

3. **Navigate to "Security Groups"**
   * In the "Site Administration" section, select **Security Groups**.\
     ![](https://files.readme.io/836da34636d0c29f7652ec4a33ba888389aee2d61eb97425fd2eaab98aebded2-image.png)

4. **Identify the Desired Group**
   * Note: A user may belong to **more than one** security group.\
     ![](https://files.readme.io/9e1aad8aeb3897402dd8e93380483b9bcd86baa4feb1e5d3290990f1beee7ad2-image.png)

5. **Check the Group** You Wish to Edit
   * **Only one** group can be modified at a time.\
     ![](https://files.readme.io/af436bed82feae3dec7a5c886c574ec17d195fa5713dcf3c259a053ae89e7ae9-image.png)

6. **Click "Edit"**\
   ![](https://files.readme.io/c606abc4a496441416640d19800265d8133a2c0ddef80b52974bdc81f96a5a2b-image.png)

7. **Go to the "Users" Tab**\
   ![](https://files.readme.io/441cc57b6c27505c3b56c67023149ff5fc2a7675040dcf21aa5d8b9e6cf46b8f-image.png)

8. **Review or Modify** Which Users Belong to This Group
   * Add or remove users as needed, then **save** changes.\
     ![](https://files.readme.io/1bc32231907f1cfa61e7c39a3397a1851baaecd77b82775d2c4a093a65eabd47-image.png)

***

## **Add Users to a Security Group**

1. **Verify Users**
   * On the "Users" tab, click **Add User**.\
     ![](https://files.readme.io/8c0a087d7e2605938cd9259ed0896961efd20ade853473a96f91228b42e697f5-image.png)

2. **Check** the Users You Wish to Add\
   ![](https://files.readme.io/3fb99807a894b9a60fea49a57bf6481efad678e1703deac055952c895f21d159-image.png)

3. **Save** to Include Them in the Group\
   ![](https://files.readme.io/befa634ea6684f1b7703aa296ccdb0d15160232e150881de6d136e5b6cf77aa3-image.png)

4. **Save Changes and Close**\
   ![](https://files.readme.io/a8d69874af67c9b06fd6ca85a75e6331a7af03396a33a1872e1108b609f12b13-image.png)

***

## **Remove Users from a Security Group**

1. **Select** the Users to Remove\
   ![](https://files.readme.io/57785d673f0feea472c9b074e29e11e6c0a37b47b66e9710ecb22ffb23a77376-image.png)

2. **Click "Save"** to Exclude Them\
   ![](https://files.readme.io/56cc3544d2c78b1379950181c6babf17cfe027fb19e82934ab97469ba93e2537-image.png)

3. **Save Changes and Close**\
   ![](https://files.readme.io/6924c88e2b327618b1a62e6d38a27882f1121f58621d9a48ca1b891e580887ea-image.png)

> **Note:** **Repeat** this process for each security group that needs updating.