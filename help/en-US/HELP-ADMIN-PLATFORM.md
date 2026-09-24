# Platform

Platform is for the people who run the whole service. It shows every tenant together, the
health of the service and the jobs that run in the background. It has five tabs:
**Tenants**, **Health & jobs**, **Plans & campaigns**, **Maintenance** and **Security**.

## How to Open

**Wide screen:** choose **Platform** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Platform**.

**Tab:** Choose a tab under the title: **Tenants**, **Health & jobs**, **Plans & campaigns**, **Maintenance** or **Security**.

**Access needed:** Only superadmins can open Platform.

**Locked:** you never see a lock here. **Platform** is not in the menu unless you are a superadmin. If you reach it another way, it shows "Platform is for superadmins only." The group selector does not apply.

**Who can see it:** superadmins only. It does not appear in the menu for any other admin,
and if it is reached another way it shows "Platform is for superadmins only."

**Not scoped to one group:** the screen is labelled "Superadmin only. Affects every
tenant." Its access label reads **Platform** rather than View, Edit or Approve. The group
selector at the top does not change what you see here.

## Tenants

**Search:** find a tenant by name.

**Columns:** Tenant, members, Staff, State and Region. A value that is not available shows
a dash.

**Empty:** "No tenants yet." If a search finds nothing you see "No tenants match" followed by
what you typed.

**Open a tenant:** tap a row to see its name, members, staff, state and region. The detail
refreshes when it opens. If it cannot, you see "Could not refresh this tenant's detail.
Showing the last known values."

**Break-glass…:** opens the tenant with full access for an emergency. You must give a
**Reason (required)**. The dialog, titled "Break-glass into" followed by the tenant name,
warns that it "writes a distinguished audit action, and notifies that tenant's admins. Every
use is reviewed." Choose **Break glass**, or **Cancel**. Access applies straight away, with
no second approver. You see "Break-glass access to" the tenant "granted and audited."

## Health & jobs

**Component status:** at the top, one row per part of the service. Each shows its name, a
state (**Operational**, **Degraded**, **Down**, **Maintenance** or **Unknown**), a response
time in ms or the error, and when it was last checked. While it loads you see a progress
bar. If none are reported you see "No component status reported yet." If it fails you see
"Could not load component status."

**Jobs:** below that, the background jobs and their runs. Columns are Job, Status, Started
and Triggered by. You can also add Rows and Error. Status is **Running**, **OK**, **Error**
or **Skipped**.

**Empty:** "No platform jobs have run yet."

**Open a run:** tap a row to see its status, start and finish time, who triggered it, the
rows it handled and any error.

**Run now…:** with Edit or Approve access, asks for the job to run immediately for every
tenant it covers. Give a **Reason (required)**, then **Submit request**. You see "Request
submitted. Waiting for another approver." Another superadmin must approve it. See Approvals.

## Plans & campaigns, Maintenance and Security

Coming soon. Each tab shows "is not built yet" for now.

**Plans & campaigns:** until then, use Manage Services, In App Services, Manage Campaigns
and Manage Rewards under Other tools.

**Maintenance:** until then, use the Maintenance tool under Other tools.

**Security:** nothing to use yet.

## Good to know

**Errors:** you may see "You do not have permission to do this on the platform." or "This
could not be completed. A matching action may already be pending." Nothing is changed when
a request fails.
