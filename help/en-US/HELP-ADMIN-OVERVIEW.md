# Overview

Overview is your daily starting point: the main numbers for your group, the daily checks,
and what is closest to a limit.

## How to Open

**Wide screen:** choose **Overview** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Overview**.

**Access needed:** Overview opens first. You see it if your role gives you access to any screen. **View** is enough to read it. **Edit** or higher also lets you use **Run checks**.

**Locked:** if you hold no access anywhere, **Overview** is not in the menu. If you switch to a group where you have no access, it shows a lock and the message "You do not have access to Overview in this tenant". Switch group with **Tenant** at the top.

**Period:** choose **Today**, **7 days** or **30 days**. Each tile shows its value and the
change against the previous period as a percentage, for example **+41.7% vs last week**, green
when it went up and red when it went down. Beneath it you see the two counts the percentage
comes from, for example "17 now, 12 the previous 7 days". When the previous period had none
to compare with, the tile says "up 5 vs last week" in words instead of a percentage.

**Tiles:** tap a tile to open the screen behind it. **Traded value today** shows its currency
and is never added across currencies, so each currency has its own total. When the server does
not state the currency, the tile says "currency not stated" instead of guessing a symbol.

**Daily checks:** each check shows OK, a warning or a failure, with a count. Tap a check to
open the screen that owns it. With Edit access you can use **Run checks** to run them again.
**Orders rejected or stuck** shows the total and, beneath it, how many were rejected and how
many are stuck. Tap it to open Trading on **Needs attention**. **Broker connections up** reads
"5 of 6" and names any broker that is down or not monitored. **Open risk alerts** opens Risk
on **Alerts**.

**Not measured:** a check or tile the data cannot answer shows a grey **Not measured** pill and
the reason, never a zero and never OK. Tap it to read the whole reason. **KYC expiring** and
**Failed imports** show this until that data is recorded.

**Side menu numbers:** **Approvals**, **Risk**, **Trading** and **Overview** can show a small
number for what is waiting: approvals for you, open alerts, orders rejected or stuck, and
checks that fail or warn. The number is hidden when nothing is waiting or when it cannot be
measured, and reads **99+** from one hundred.

**Nearest a limit:** the items closest to a risk limit, taken from your clients' journals,
with a bar for how much of the limit is used. Each row names the client, or the symbol, and the
limit. Items at 90% or more show gold, and items at or over the limit show red. Where limits
are measured but none has been yet, the card says "No limits measured yet".

**Nothing to show:** a new group with no activity shows "Nothing to show for this tenant
yet."

**On a phone:** the top of the page shows **Approvals** (open approvals) and **Checks**
(how many checks need attention). Tap Approvals to open it, or Checks to jump to the list.
Pull down to refresh, or tap **Refresh** beside the update time.

**Fresh and stale data:** Overview shows the last result it loaded, with the time it was
loaded, and never refreshes on its own. Results are kept for a few minutes and reused when
you come back. If the data on screen is older than that, or a refresh failed and you chose
**Show last loaded**, a gold line says "Showing data from hh:mm. Refresh to update." Press
**Refresh** when you want current numbers.
