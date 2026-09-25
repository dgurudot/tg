# Setup

Setup is where you decide who on your team can do what, manage groups of clients and the
features they get, and send messages to your clients. It has four tabs: **Staff & access**,
**Groups & features**, **Features** and **Messaging**.

## How to Open

**Wide screen:** choose **Setup** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Setup**.

**Tab:** Choose a tab under the title: **Staff & access**, **Groups & features** or **Messaging**.

**Access needed:** You need access to at least one of Staff & access, Groups & features or Messaging. **View** lets you read. **Edit** lets you make changes and requests. **Approve** lets you approve requests on that tool.

**Locked:** if you have access in another group but not the one you are working in, **Setup** shows a lock in the menu. Opening it says "You do not have access to Setup in this tenant" and names the group where you do have access. Switch group with **Tenant** at the top. If you have no access in any group, **Setup** is not in the menu at all.

## Staff & access

Staff & access shows every admin who has access to your group, and what each one can do on
each screen.

**Search staff:** find an admin by name or Admin ID.

**Team matrix / List:** the matrix shows one row per admin and one column per screen:
Approvals, Clients, Trading, Risk, Funding, Reports, Compliance and Setup. The list swaps the
screen columns for a tool count and a one-line summary such as "Approvals Approve, Clients
Edit". On a phone each admin is a card that lists only the screens they can use.

**Access:** narrows the people shown by what they can do on a screen. For each screen pick
Any, None, View+, Edit+ or Approve. Every row you can see is already loaded, so the result
is complete. **Clear** removes the filters.

**Export:** copies the rows on screen as CSV.

**Reading a cell:** **A** is Approve, **E** is Edit, **V** is View, and a dash means no
access. A dot on the cell means the tools on that screen are at different levels; the cell
shows the highest. A cyan outline means the access covers every group, not only this one.
That marker appears only when the system reports it.

**Updated and refresh:** the header shows when the list loaded. Nothing refreshes by itself.
Choose the refresh button to load it again.

**Empty:** "No staff have access to this tenant yet."

**Open an admin:** tap a row to open their access, or tap a cell to open it at that screen.

### Changing an admin's access

The editor shows the admin's name and Admin ID, an **Effective now** strip with what they
hold, and one row per tool under each screen. With View access every control is off and there
is no save bar.

**Level:** for each tool, choose **None**, **View**, **Edit** or **Approve**. A level above
your own on that tool is hatched and cannot be picked; press and hold it to see why. Reports
tops out at Edit and Audit trail at View. **Changed** marks a tool you have changed.

**Preset:** a preset fills the grants for a common role. The editor lowers any level above
your own.

**Maintenance:** shows "Superadmin only. Not grantable per tenant."

**If the admin holds more than you:** saving replaces the admin's whole set of access, and
the save is refused if the set includes anything above your own level. The editor tells you
which access is the problem and turns Review off until it is lowered to your level. Access
the editor has no control for is kept as it is.

**Save bar:** shows how many changes you have made. **Discard** puts everything back.
**Review...** opens the review.

**Review:** lists each change as "None → Edit" and marks it "becomes a request". Every change
goes to a second approver, so nothing changes until it is approved. Give a **Reason
(required)**, then choose **Request N changes**, or **Back** to keep editing. The back arrow
asks before it throws away unsaved changes.

**After you save:** you see "Request submitted for approval. Nothing changes until it is
approved." The request shows on the Approvals screen. See Approvals.

## Groups & features

Groups & features lists the groups of clients in your tenant. Choose a group to see its
features and to ask for support actions. It does not explain how features are decided. For
that, and for what happens when a group and a user disagree, read Feature control.

If you have no access to the tab in this group, you see "You do not have access to Groups
& features in this tenant."

**Search groups:** looks through every group, not only the ones on screen. It may take a
moment on a tenant with many groups.

**The list:** the first entry is "Everyone in this tenant". Then one entry per group with its
member count. More groups load as you scroll; **Load more** does the same by tap. On a phone
choosing a group opens it full width, with a back arrow.

**Empty:** "No cohort groups for this tenant yet."

**Features set for this group:** each feature the group has a setting for, and whether it is
On or Off. This is a read-only view. Features are changed in one place, so choose **Change in
Features** to open the Features tab, where every change names its scope.

**Force sign-out group...:** asks for everyone in the group to be signed out. The dialog
shows how many members it applies to. Give a **Reason (required)**. Tick **Also clear local
data** to clear what is stored on their devices too. You see "Sign-out requested."

**Clear cache for group:** asks for the app's stored data to be cleared for the group. Give a
**Reason (required)**. You see "Clear cache requested."

For "Everyone in this tenant" the same two actions apply to every client in your tenant.
A second admin decides each request. With View access you see "View only. You cannot request
actions for this group."

**Members and Accounts:** a group has **Members** and **Accounts** sub-tabs, when your server
supports it.

**New group:** creates a group. This is a request.

To include or exclude a group for a
feature use the Features tab; for adding users to a group use Manage User Groups under Other
tools.

## Features

See Feature control.

## Messaging

Messaging sends a message to your clients and keeps a log of what you sent.

**No access:** without Edit access on News, Update or Notification, you see "You do not
have Edit access on News, Update, or Notification sending for this tenant." and no form.

**News / Update / Notification:** the type. A type you cannot send is hatched.

**Compose / Sent:** switches between writing and the log.

**Audience:** choose the whole tenant or one group.

**Title** and **Message:** both are required before you can continue. **Preview on a phone**
shows them as you type.

**Send...:** while it checks recipients it shows "Checking recipients...". You then confirm
with "Send this News?" (or Update, or Notification), which shows how many people it reaches,
the title and the message. Choose **Send to N** or **Cancel**.

**Schedule…:** when your server supports it, **Schedule…** sends later. Pick a date and time
in your own time zone, up to 30 days ahead. The confirmation shows the exact UTC time. The
audience is worked out again at send time, so the head count can change. Scheduled sending
works only when your organisation's scheduler is switched on.

**Scheduled tab:** lists your own pending scheduled messages. **Cancel** stops one before it
is sent. The Sent log shows a scheduled message only after it has been delivered.

**After you send:** you see "Sent to 120 people." (with your real count) and the form
clears. The message goes out straight away. It does not wait for approval.

### Sent log

**Columns:** Sent, Kind, Audience, Recipients and Sent by. It loads more as you scroll, and
scrolls sideways on a narrow screen. Search is not offered here, because a search over only
the entries already loaded would leave out older sends.

**Empty:** "Nothing sent for this tenant yet."

## Support link

**Support link:** under Groups & features, **Everyone in this tenant** shows the tenant's
support link. This is the address that **Open support tickets** opens in a client's profile.

**Request change…:** needs Edit access and a reason. The address must be https, with no user
name or password, and at most 2048 characters. It takes effect only after a second approver
approves it.

**Remove:** leave the address empty to request removal.

## Good to know

**Errors:** if a change fails you see a plain message, such as "You don't have permission to
do that in this tenant." or "Someone already has a pending request for this. Refresh to see
it." Refresh and try again.

**Groups:** everything here belongs to the group shown at the top of the screen. See Roles
and access.
