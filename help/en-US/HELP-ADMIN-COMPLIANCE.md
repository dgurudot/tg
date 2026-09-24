# Compliance

Compliance shows what happened in your group and lets you export it. It has two tabs:
**Activity** and **Audit trail**. Both are read only.

## How to Open

**Wide screen:** choose **Compliance** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Compliance**.

**Tab:** Choose a tab under the title: **Activity** or **Audit trail**.

**Access needed:** You need access to Compliance or Audit trail. Both tabs need **View** on Audit trail. Nothing here needs Edit or Approve.

**Locked:** if you have access in another group but not the one you are working in, **Compliance** shows a lock in the menu. Opening it says "You do not have access to Compliance in this tenant" and names the group where you do have access. Switch group with **Tenant** at the top. If you have no access in any group, **Compliance** is not in the menu at all.

**Access:** you need View on the audit trail to open either tab. Nothing on this screen
changes data, so it never creates a change request. If you lack access you see "You do not
have access to Activity flags in this tenant." on Activity, or "You do not have access to
Audit trail in this tenant." on Audit trail.

**Refresh:** the refresh icon reloads the tab, and an **Updated** time shows when it last
loaded. Nothing refreshes on its own. **Choose columns** picks which columns show.

## Activity

Activity lists activity that may need a look.

**Columns:** When, Who, Event, Detail and Flag.

**Events:** **Rejected order burst** is flagged **Exception**. **Sign-in from a new
device** and **Failed sign-in** are flagged **Review**.

**Search:** filters by user or detail.

**Open a row:** shows When, Who and Detail. To act on it, open the user from Clients or the
related rule from Trading.

**Empty:** "No flagged activity in this tenant." This is normal today, because flagged
activity is not being produced yet.

## Audit trail

The audit trail is the record of who did what.

**Columns:** When, Actor, Action and Target are shown. Client, From and User agent can be
added with **Choose columns**.

**Break-glass:** an emergency action carries a **Break-glass** badge.

**Search:** filters by actor.

**Filters:** **Action**, **Target** and **Client**, plus a date range of **All time**,
**Last 24 h**, **Last 7 d** or **Last 30 d**.

**Open a row:** shows the actor, client, target, reason, where it came from, the user
agent, and **Before** and **After** values where the event changed something.

**Export:** the Export icon exports every event that matches your current search and
filters. A line shows "Export … Running…", "Ready" with the row count, "Failed" with the
reason, or "Skipped". Use the refresh icon in that line to reload the trail, where the
export is itself logged, and dismiss the line when you are done.

**Empty:** "No audit events match this tenant yet." With filters set you see "No audit
events match those filters."
