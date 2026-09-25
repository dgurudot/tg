# Reports

Reports lets you run a ready-made report, save your own versions, schedule them and
download the results. It has four tabs: **Catalogue**, **My reports**, **Schedules** and
**Exports**.

## How to Open

**Wide screen:** choose **Reports** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Reports**.

**Tab:** Choose a tab under the title: **Catalogue**, **My reports**, **Schedules** or **Exports**.

**Access needed:** You need access to Reports. **View** lets you browse, run and export. **Edit** lets you save, rename, delete and schedule your own reports.

**Locked:** if you have access in another group but not the one you are working in, **Reports** shows a lock in the menu. Opening it says "You do not have access to Reports in this tenant" and names the group where you do have access. Switch group with **Tenant** at the top. If you have no access in any group, **Reports** is not in the menu at all.

**Access:** the header shows **View only** or **Edit**. With View you can browse, run and
export reports. Edit is needed to create, rename, delete and schedule your own reports.
These changes apply straight away and do not need approval, because they only affect your own saved reports. Every change is still recorded.

**Refresh:** the refresh button in the header reloads the tab you are on and shows an
**Updated** time. Nothing refreshes on its own.

If a tab cannot load, you see the reason and a **Try again** button.

## Catalogue

The catalogue lists the ready-made reports.

**Search reports:** type to narrow the list. "No results match your search." means nothing
matched.

**Open a report:** choose one, then use **Run report**. While it runs you see "Running the
report…". Choose **Run again** to run it again.

**Result:** you see the filters used, headline figures, and a table of rows. "This report
has no rows for the current filters." means the run worked but found nothing. If a run
fails you see "This report did not run" with the reason.

**Export:** choose **Export** and pick **CSV**, **Excel (.xlsx)** or **PDF**. You see
"Export started. Find it in Reports → Exports when it finishes."

**Exceptions:** rejected or expired orders, plus failed or stuck jobs. Filter **Source** is
ORDER or JOB.

**Operational metrics:** job outcomes and durations, and staff activity by action. Filter
**Section** is JOB_RUNS or ADMIN_ACTIVITY.

**Risk and exposure:** risk limits, then positions by exposure. Filter **Row type** is LIMIT
or POSITION.

**Summaries:** these three reports are summaries and cannot be grouped.

**Computed by the server:** **Group by** and the KPIs are computed by the server over every
matching row, not only the rows on screen. Orders has no Sum or Average KPI. If the server
cannot do a Group by or KPI you chose, you see "The server did not accept this report".

## My reports

My reports holds the reports you saved.

**Search my reports:** filter the list by name.

**New report:** with Edit access, opens a builder with a **Report name** and these steps:
**Start from**, **Filters**, **Group by**, **KPIs** and **Columns**. Use **Next** and
**Back** to move between steps, then **Save report**. With no saved reports you see "You
have not saved any reports yet."

**Run and export:** open a saved report to run it and export it, as in the Catalogue.

**Rename and Delete:** with Edit access. **Rename report** asks for a **Report name**.
**Delete this report?** removes it from My reports and Schedules. Past runs and exports are
kept.

**Scheduling:** with Edit access, open a saved report and choose **Schedule daily**,
**Schedule weekly** or **Schedule monthly**. A tick shows the one that is active. **Send
to (comma-separated emails)** takes the recipients; leave it blank to record runs without
emailing anyone. **Format:** is CSV. The screen notes that scheduled delivery is saved but
nothing sends it yet.

**Load 50 more:** shows the next page when the list is long.

## Schedules

Schedules lists every scheduled report.

**Columns:** Report, Runs (Daily, Weekly or Monthly), Format, Sent to, and Last run. Last
run shows "Not run yet", or the time and the outcome, and Failed if it failed.

**Empty:** "No report is scheduled yet."

**Changing a schedule:** do it from My reports. Emails are not sent yet.

## Exports

Exports lists the files your exports produced.

**Each row:** the export name and its state: **Running…**, **Ready** with the time and
row count, **Failed** with the reason, or **Skipped**.

**Empty:** "No export has been run yet."

Use the refresh button to see a running export finish. Use **Load 50 more** for older ones.
