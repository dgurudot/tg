# Other tools

Other tools are the single-purpose tools that sit below the main screens in the
Administration menu. They do the same jobs as before and have not moved. Some of them are
being replaced by the main screens over time.

## How to Open

**Wide screen:** the tools are in the side menu on the left, below a divider under the main screens. Choose a tool and it opens in the main area. Use the menu button at the top right to collapse the menu to icons, where you point at an icon to see its name.

**Tablet and phone:** below 1000 pixels wide, open the menu drawer with the menu button at the top left. The tools are at the bottom of the drawer, below the main screens. Choose one and it opens as its own full screen. Use the back button to return.

**Send Trade:** it does not open a screen. It opens a symbol search on top of the screen you are on.

**Access needed:** the seven superadmin tools need a superadmin role. Each group tool needs its own access in the group you are working in.

**Locked:** tools you cannot use are not listed. There is no lock. If a tool you expect is missing, switch group with **Tenant** at the top, or ask a superadmin for access.

## Who sees which tool

**Superadmin tools:** seven tools, shown only to superadmins. They work across every group.

**Group tools:** the rest belong to one group at a time. You see a tool only when your role
gives you access to it in the group you are working in, and they are listed A to Z. If you
have no group tools, the list is empty. See Roles and access.

Most of these tools act at once. They do not go through Approvals, so check before you
confirm.

## Superadmin tools

They are listed in this order.

### Add Admin

search for a user, then choose **Assign** to make them an admin. A refresh
button reloads the user list, and warns "Refreshing the data is an expensive operation.
Proceed only if the user data was updated." Choose **Proceed** or **Cancel**.

### Approve Subscribers

search for a subscriber and see the service they asked for. Choose
**Approve** to accept them, or **Delete** to turn them down.

### Delete Subscribers

search for a subscriber and choose **Delete** to remove them. With
none, you see "No data found".

### In App Services

the list of services sold inside the app. Use the plus button to
create one. With none, you see "No Services Created".

### Manage Campaigns

create and edit campaigns that award bonus points. Each has a
**Name**, **Description**, **Bonus Points**, **Trigger Type** and an **Active** switch.
Choose **Edit** or **Delete** on a campaign. Delete asks you to confirm, and "This cannot
be undone." With none, you see "No campaigns yet. Tap + to create one."

### Manage Rewards

create and edit rewards that clients spend points on. Each has a
**Name**, **Description**, **Cost (points)**, **Sort Order**, **Icon**, **Category** and an
**Active** switch. Edit and Delete work as they do for campaigns. With none, you see "No
rewards yet. Tap + to create one."

### Remove Admin

search for an admin and choose **Remove** to take their admin role away.

## Group tools

Each one appears only if you hold the matching access in the group you are working in.

### Add User Accounts

the screen is titled View User Account. Search for a user, see their
accounts and choose **Add Accounts**. With no match you see "No users found." A refresh
button reloads the list, with the same warning as Add Admin.

### Admin Rebalancer

opens the Rebalancer as an admin, so you can work with it on behalf of
your clients.

### Maintenance

removes old data in bulk. Choose a target (**News**, **Trades** or
**Updates**), set a start and end date, then choose **Purge Data**. An open signal and the
updates that belong to it cannot be deleted. This cannot be undone.

### Manage Group Features

choose a group under "Select a Group" and a feature under "Select
a Feature", then choose **Add to Include** or **Add to Exclude**. The screen lists what the
group already includes and excludes. For how the settings combine, see Feature rules
(`feature-rules.md`).

### Manage Services

the list of services for your group. Use the plus button to create
one. With none, you see "No Services Created".

### Manage Trades

the list of trades you have sent. Each row offers **Modify**, **Close**,
**Updates**, **Stop** and **Delete**. Stop, Delete and Close each ask you to confirm first.
With none, you see "No Trades yet".

### Manage User Features

search for a user, choose a feature, then **Add to Include** or
**Add to Exclude**, the same as for a group. A user's own setting beats their groups. See
Feature rules. A refresh button reloads the user list, with the usual warning.

### Manage User Groups

type a group name and choose **Add Group**. Each group has **Add**
and **Remove** to change who is in it, **Accounts** to see its accounts, **Delete** to remove
the group, and **Logout** to sign its members out. The built-in default group cannot be
changed.

### Send News

write a message, optionally add a photo (**Take Photo** or **Choose Photo**)
and send it. Earlier news shows below. With none, you see "No news yet. Start sending news".

### Send Notification

fill in the recipient, a **Title** and a message, then choose **Send
Notification**.

### Send Trade

opens a symbol search so you can pick what to send. The trade then appears
in Manage Trades.

### Send Update

the screen is titled Send Updates. It works like Send News, for updates.
With none, you see "No updates yet. Start sending".

### View Positions

a table titled Positions, with each position's symbol, quantity, price
and gain.

## Good to know

**Setup covers some of this:** Staff & access, Groups & features and Messaging in Setup do
the same jobs with review and a record. Prefer them where they fit. See Setup (`setup.md`).
