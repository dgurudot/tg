# Risk

Risk shows your group's exposure and the rules that watch it. It has **Exposure** and
**Rules**, and an **Alerts** tab that appears once alerts are switched on for your
platform.

## How to Open

**Wide screen:** choose **Risk** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Risk**.

**Tab:** Choose a tab under the title: **Exposure**, **Alerts** or **Rules**.

**Access needed:** You need access to Risk. **View** lets you read exposure and rules. **Edit** lets you request rule changes.

**Locked:** if you have access in another group but not the one you are working in, **Risk** shows a lock in the menu. Opening it says "You do not have access to Risk in this tenant" and names the group where you do have access. Switch group with **Tenant** at the top. If you have no access in any group, **Risk** is not in the menu at all.

## Exposure

Exposure is built from your clients' journals. It is not client assets and not broker
margin.

**Levels:** client, then account, then instrument. Open a row to see the level below it.
The **By asset class** view appears only when the platform can group that way.

**Columns:** Notional, Limit and Used. Limit names the limit that applies to the row.
Rows at 90% of a limit or more show gold, and rows at or over the limit show red. A dash
under Used means the usage is not measured for that limit yet.

**Over 90% only** and **Search:** both look across the whole tree, not only the rows you
have opened. The first time you use one, the full tree loads once.

## Alerts

The tab is hidden until alerts are available. When it appears:

**Open** and **All:** the shortcut for the State filter. **Filter icons** in the column
headers filter by rule, observed value, state, due time and owner. On a phone, use the
**Filters** chip. Active filters show as chips you can remove, with **Clear filters**.

**Acknowledge** and **Raise case:** open an alert and act on it. Acknowledge is direct
and recorded. Raise case hands the alert to Compliance.

## Rules

Rules raise an alert when a threshold is crossed. They never block an order.

**Current** and **History:** History shows every approved change, with who asked and who
approved.

**Search, Scope and column filters:** every column has a filter icon. Filters cover every
rule in your tenant. Where the platform cannot filter a column yet, its icon is greyed
with "Not filterable yet".

**New rule…** and **Request change:** with Edit access, give the details and a reason.
Every rule change is a request, and the rule shows **Pending change** until it is decided.

**Last observed:** "Not measured yet" means the rule has not been checked yet. It fills
in once the platform starts measuring limits.

## Loading and freshness

Lists load more as you scroll, and the table scrolls sideways when it is wider than your
screen. Nothing refreshes on its own. If you are looking at saved data that has gone
stale, the header time turns gold and a line says when it was fetched. Choose the refresh
icon to update.
