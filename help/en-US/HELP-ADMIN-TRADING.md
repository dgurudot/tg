# Trading

Trading shows your clients' orders and the tools that trade for many clients at once. It
shows the tabs your group has data for. Today that is **Orders**. **Automation** and
**Instruments** appear on their own once your group has that data.

## How to Open

**Wide screen:** choose **Trading** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Trading**.

**Tab:** Choose a tab under the title: **Orders**, **Automation** or **Instruments**. A tab only shows when your role gives you the matching tool and your group has that data. **Orders** always shows.

**Access needed:** You need access to at least one of Orders, Instruments or Automation. **View** lets you read. **Edit** lets you make requests. Each tab follows its own tool, so you may see some tabs and not others.

**Locked:** if you have access in another group but not the one you are working in, **Trading** shows a lock in the menu. Opening it says "You do not have access to Trading in this tenant" and names the group where you do have access. Switch group with **Tenant** at the top. If you have no access in any group, **Trading** is not in the menu at all.

## Orders

**Views:** **Open**, **Today** and **History**. **Needs attention** shows rejected and
expired orders.

**Search:** by symbol, order id or account id.

**Filters:** Side (Buy or Sell) and Source (Manual, Connected broker or Automation) sit next
to the views. Tap **Filters** to filter by any column: time, client, account, symbol, side,
type, status, order id, time in force, source, order state or broker. On a computer you can
also open the menu on a column heading. Every filter applies to all matching orders, so the list and the
count always agree. A filter you have set shows as a chip; tap the chip to remove it, or tap
**Clear filters**. A filter that is not available yet is dimmed and says "Not filterable
yet".

**Sort:** open a column heading's menu and choose ascending or descending. Sorting also applies to all matching orders.

**Columns:** the column chooser adds order id, external id, time in force, source, value and
more. **Last change**, market, filled quantity, average price, IP address and approver appear
when your group's data includes them.

**Open an order:** tap a row to see the order's details and its lifecycle: Created, Sent to
broker, Filled or rejected, and Settlement. Settlement shows "not tracked". **Open in
History** shows every change to that order.

**History mode:** switch **Current** to **History** to see every change to orders, with the
before and after values. Filter it by the kind of change and by who made it.

**Stale data:** a list you opened before shows at once with the time it was loaded. Nothing
refreshes by itself. Tap **Refresh** to load it again.

**Export:** the export runs in the background. Find the file under Reports, on the Exports
tab.

## Trades and Positions

These tabs are not shown yet. Filled orders show under Orders, and exposure by asset class
and by client is on the Risk screen.

## Automation

This tab appears with your Automation access. It holds two launchers, **Send trade signal**
and **Rebalance a group**, which open the existing tools. With View access you see a note
that sending and rebalancing need Edit access. A list of systems is added when it becomes
available. **Rebalance a group…** and **Send trade signal…** are also available from the
legacy tools menu.

**Systems:** the list of auto-trading systems, with their state, followers, last signal and
problems. Pause, Resume and Stop are requests, because they move every follower at once.

## Instruments

This tab is a read-only catalogue of instruments, with symbol, name, market, exchange,
sector and asset type. Instrument settings and change requests appear when they become
available. When your group has instrument data it lists the instruments your clients
trade, with their settings and **Set at**, which tells you where each setting comes from:
platform, market, group or this security.

**Request a setting change…:** change the trading mode, minimum size, lot size or order
step for one security. Give a reason. This is a request.
