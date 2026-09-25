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
have access to this section in this tenant." and nothing is loaded.

**Refresh:** the refresh icon at the top right reloads the tab you are looking at, and an
**Updated** time shows when it last loaded. Nothing refreshes on its own. A tab you have not
opened has not loaded yet: the Audit trail is requested the first time you open it.

**Choose columns:** the columns icon picks which columns show. On a wide screen the table
scrolls sideways when the columns do not fit, and the first column stays in place. On a phone
each row is a card.

**Filters:** the chips above the table filter every event, however many there are, not only the
rows already on screen. A column that cannot be filtered yet is shown disabled with "Not filterable yet".

## Activity

Activity lists activity that may need a look.

**Columns:** When, Who, Event, Detail and Flag.

**Events:** **Rejected order burst** is flagged **Exception**. **Sign-in from a new
device** and **Failed sign-in** are flagged **Review**. A row can also be flagged **Normal**.

**Search and chips:** the search box, **Needs review / All**, **Event** and the date range
work once they are available. Until then they are shown disabled and the search box
says "Search is not available yet".

**Open a row:** shows When, Who and Detail. **Open Clients** or **Open Trading** takes you
to that module, and the user or rule to look for is shown in the sheet so you can copy it
into that module's search.

**Empty:** "No flagged activity in this tenant." This is normal today, because flagged
activity is not being produced yet.

## Audit trail

The audit trail is the record of who did what.

**Columns:** When, Actor, Action, Target and From are shown. Client and User agent can be
added with **Choose columns**. When names are available, the Actor and Target columns
show them instead of ids, and platform staff read "Name · platform".

**Break-glass:** an emergency action is tinted and read out as break-glass. On a phone it
also carries a **Break-glass** badge.

**Search:** searches action, target, reason and the actor's or client's name. Until that is
available, the box reads "Search actor id" and matches the whole actor id.

**Filter chips:** **Actor**, **Action** and a date range of **All time**, **Last 24 h**,
**Last 7 d**, **Last 30 d** or a custom range. **Filters** opens every column in one sheet:
Actor, Action, Target type, Target id and Client. **From** and **User agent** cannot be
filtered yet. Chips match the whole value; values seen in the rows already loaded are offered
as one tap picks. **Clear filters** returns to the last 24 hours.

**Open a row:** shows the actor, client, target, reason, where it came from, the user
agent, and **Before** and **After** values where the event changed something.

**Export:** the Export icon exports every event that matches your current chips. It does
not use the search box: if you have typed a search you are told to clear it first, so the
file is never a different set from the one on screen. A line shows "Export … Running…",
"Ready" with the row count, "Failed" with the reason, or "Skipped". Use the refresh icon in
that line to reload the trail, where the export is itself logged, and dismiss the line when
you are done.

**Empty:** "No audit events match this tenant yet." With the default date range you see
"No audit events in last 24 h. Widen the date range to look further back." With other
filters set you see "No audit events match those filters."

## Not on this screen yet

**Cases:** see the Cases section below.

## Cases

**Raise a case:** you raise a case from a risk alert.

**States:** a case is **Open**, **In review** or **Closed**.

**Closing a case:** closing needs a resolution note, and it cannot be undone.

**View access:** you can read cases but not change them.
