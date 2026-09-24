# Setup

Setup is where you decide who on your team can do what, manage groups of clients and the
features they get, and send messages to your clients. It has three tabs: **Staff & access**,
**Groups & features** and **Messaging**.

## How to Open

**Wide screen:** choose **Setup** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Setup**.

**Tab:** Choose a tab under the title: **Staff & access**, **Groups & features** or **Messaging**.

**Access needed:** You need access to at least one of Staff & access, Groups & features or Messaging. **View** lets you read. **Edit** lets you make changes and requests. **Approve** lets you approve requests on that tool.

**Locked:** if you have access in another group but not the one you are working in, **Setup** shows a lock in the menu. Opening it says "You do not have access to Setup in this tenant" and names the group where you do have access. Switch group with **Tenant** at the top. If you have no access in any group, **Setup** is not in the menu at all.

## Staff & access

Staff & access shows every admin who has access to your group, and what each one can do on
each screen.

**Search:** find an admin by name or Admin ID.

**The grid:** one row per admin, with the columns Name, Admin ID and Grants. On a wide
screen the grants show as a row of small cells, one per screen: Approvals, Clients, Trading,
Risk, Funding, Reports, Compliance and Setup. On a phone each admin is a card that lists
only the screens they can use.

**Reading a cell:** **V** is View, **E** is Edit, **A** is Approve, and a dash means no
access. A dot after the letter means the level differs between tools on that screen. A
shaded cell means the access covers every group, not only this one.

**Empty:** "No staff have access to this tenant yet."

**Open an admin:** tap a row to open their access.

### Changing an admin's access

With View access you see a plain list of the tools the admin holds, or "No grants for this
tenant." With Edit access or higher you can change them.

**Tools:** the sheet lists the tools under each screen. Under Clients you see Client 360,
Accounts and Onboarding & KYC. Under Trading you see Orders, trades, positions,
Instruments and Automation. Under Reports you see Reports. Under Compliance you see Audit
trail and Cases. Under Setup you see Staff & access, Groups & features and Messaging (news,
updates, notifications). Approvals, Risk and Funding each have one tool.

**Level:** for each tool, choose **None**, **View**, **Edit** or **Approve**. You can never
give a level higher than your own. Reports tops out at Edit and Audit trail at View.

**Maintenance:** shows "Superadmin only. Not grantable per tenant."

**Reason (required):** say why you are changing the access.

**Review…:** turns on once you have changed something and given a reason. The review lists
each change as "None → Edit" and marks it "(applies now)" or "(becomes a request)".
Approve-level grants always need a second approver. Choose **Back** to keep editing, or
**Save** (for example "Save 2 and request 1") to confirm.

**After you save:** you see "Request submitted for approval." Anything that is a request
shows on the Approvals screen. See Approvals.

## Groups & features

This tab lists the groups of clients in your tenant and lets you ask for a feature to be
turned on or off. It does not explain how features are decided. For that, and for what
happens when a group and a user disagree, read Feature rules.

If you have no access to the tab in this group, you see "You do not have access to Groups
& features in this tenant."

### Cohort groups

**The grid:** one row per group, with Group, Members and Features. Each feature the group
has shows as a small label on the row.

**Empty:** "No cohort groups for this tenant yet."

**Open a group:** tap a row to see the group's name, its member count and its features. With
Edit access you also get two actions. With View access you see "View only. You cannot
request actions for this group."

**Request sign-out…:** asks for everyone in the group to be signed out. Give a **Reason
(required)**. Tick **Also clear local data** to clear what is stored on their devices too.
Choose **Submit request**, or **Cancel**. You see "Sign-out requested."

**Request clear cache…:** asks for the app's stored data to be cleared for the group. Give a
**Reason (required)**, then **Submit request**. You see "Clear cache requested."

**All clients in this tenant:** the same two actions, but for every client in your tenant
instead of one group. This button sits in the grid toolbar.

### Request a tenant-wide feature change

**Choose a feature:** pick from the list.

**Enable** or **Disable:** the change you want.

**Reason (required):** say why.

**Request change:** sends the request. It applies to every client in your tenant, not to
one group. This screen only sends the request. It does not show the feature's current
state. A second admin decides the request, as described in Feature rules.

**View only:** with View access you see "View only. Ask someone with Edit access on Groups
& features to request a feature change for this tenant." and no form.

To include or exclude a feature for one group or one user, use Manage Group Features or
Manage User Features under Other tools.

## Messaging

Messaging sends a message to your clients and keeps a log of what you sent.

**No access:** without Edit access on News, Update or Notification, you see "You do not
have Edit access on News, Update, or Notification sending for this tenant." and no form.

**Kind:** **News**, **Update** or **Notification**. The list shows only the kinds you can
send.

**Audience:** always "every client in this tenant." You cannot narrow it here.

**Title** and **Message:** both are required before you can continue.

**Preview and send:** while it checks recipients it shows "Checking recipients…". You then
confirm with "Send this News?" (or Update, or Notification), which shows how many people it
reaches, the title and the message. Choose **Send** or **Cancel**.

**After you send:** you see "Sent to 120 people." (with your real count) and the form
clears. The message goes out straight away. It does not wait for approval.

### Sent log

**Columns:** Sent, Kind and Recipients.

**Search:** filters the entries already loaded, by kind.

**Empty:** "Nothing sent for this tenant yet."

## Good to know

**Errors:** if a change fails you see a plain message, such as "You don't have permission to
do that in this tenant." or "Someone already has a pending request for this. Refresh to see
it." Refresh and try again.

**Groups:** everything here belongs to the group shown at the top of the screen. See Roles
and access.
