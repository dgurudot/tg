# Platform

Platform is for the people who run the whole service. It shows every tenant together, the
health of the service and the jobs that run in the background. It has four tabs:
**Tenants**, **Health & jobs**, **Plans & campaigns** and **Maintenance**.

## How to Open

**Wide screen:** choose **Platform** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Platform**.

**Tab:** Choose a tab under the title: **Tenants**, **Health & jobs**, **Plans & campaigns** or **Maintenance**.

**Access needed:** Only superadmins can open Platform.

**Locked:** you never see a lock here. **Platform** is not in the menu unless you are a superadmin. If you reach it another way, it shows "Platform is for superadmins only." The group selector does not apply.

**Who can see it:** superadmins only. It does not appear in the menu for any other admin,
and if it is reached another way it shows "Platform is for superadmins only."

**Not scoped to one group:** the screen is labelled "Superadmin only. Affects every
tenant." Its access label reads **Platform** rather than View, Edit or Approve. The group
selector at the top does not change what you see here.

## Tenants

**Search:** find a tenant by name or id. The search covers every tenant, not only the rows on screen.

**Columns:** Tenant (with its member count), Staff, State and Region. You can add Clients and
Tenant id from the column chooser. A value that is not available shows a dash. The `default`
row is the all-users group: it has no Break-glass button.

**More rows:** choose **Load 50 more** at the bottom of the list. The list is paged, so only
what you have loaded is on screen.

**Empty:** "No tenants yet." If a search finds nothing you see "No tenants match" followed by
what you typed.

**Open a tenant:** tap a row to see its name, id, members, staff, state and region. The detail
refreshes when it opens. If it cannot, you see "Could not refresh this tenant's detail.
Showing the last known values."

**Break-glass…:** in the row or in the detail. Opens the tenant with full access for an
emergency. You must give a **Reason (required)**. The dialog, titled "Break-glass into"
followed by the tenant name, warns that it "writes a distinguished audit action, and notifies
that tenant's admins. Every use is reviewed." Choose **Break glass**, or **Cancel**. Access
applies straight away, with no second approver. You see "Break-glass access to" the tenant
"granted and audited."

**Region:** the Region column shows a dash when no region is set.

**New tenant** and **Retire:** both are requests that another superadmin must approve. Nothing
changes until then. A tenant cannot be retired while it has members or groups.

**Not here:** there is no Export, because it is not available yet.

## Health & jobs

One table: **Component**, **Status**, **Detail** and **When**. The parts of the service come
first, worst first, then the job runs, newest first. Times are your local time.

**Status:** components show **Up**, **Degraded**, **Down**, **Maintenance** or **Unknown**.
Jobs show **Running**, **OK**, **Error** or **Skipped**. A failed job or a down component has
a red row.

**Detail:** a response time in ms, or the error. For a job, when it ran, how long it took and
how many rows it handled.

**Search:** type a job key exactly (for example `daily_checks`) to see only that job's runs.
The parts of the service are hidden while you search. You see "No runs for job key" followed
by what you typed when there are none.

**More rows:** **Load 50 more**. Type and Triggered by are in the column chooser.

**Empty:** "Nothing has reported yet."

**Open a row:** tap it to see the details. A job run also offers **Run now…**.

**Run now…:** with Edit or Approve access, asks for the job to run immediately for every
tenant it covers. Give a **Reason (required)**, then **Submit request**. You see "Request
submitted. Waiting for another approver." Another superadmin must approve it. See Approvals.

## Plans & campaigns and Maintenance

These open the existing screens, unchanged. **Plans & campaigns** has **Services**, **In-app
services**, **Campaigns** and **Rewards**. **Maintenance** removes old data in bulk (see
Other tools). On a phone each one opens full screen. The same tools stay under Other
tools.

## Security

**Security:** the tab shows the platform default security policy and, once you pick a tenant,
that tenant's own policy: the IP allowlist, the longest session, the re-authentication
window, the new device alert and the audit retention period. Until the policy is enabled for
your environment the tab says it is using built-in defaults. Enforcement is controlled by the
server, not from this screen, so a value can be recorded but not yet applied. Audit retention
is display only: audit history is append-only and nothing deletes from it. Choose **Request
change** to propose a new value. A second approver has to approve it before it applies. A
wrong IP allowlist can lock admins out, but superadmins are never blocked. Until it is
enabled the tab shows Not enabled for this tenant.

**Refresh:** the header shows when the list was loaded ("Updated hh:mm"). Nothing refreshes by
itself. Choose the refresh button to load again.

## Good to know

**Errors:** you may see "You do not have permission to do this on the platform." or "This
could not be completed. A matching action may already be pending." Nothing is changed when
a request fails.
