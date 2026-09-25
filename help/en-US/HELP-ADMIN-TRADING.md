# Trading

Trading shows your clients' orders and the tools that trade for many clients at once. It
shows the tabs your role can use and your group's server provides: **Orders**, **Trades**,
**Positions**, **Automation** and **Instruments**.

## How to Open

**Wide screen:** choose **Trading** in the side menu on the left. Use the menu button at the top right to collapse the menu to icons or expand it again.

**Tablet and phone:** below 1000 pixels wide the side menu becomes a drawer. Open it with the menu button at the top left, then choose **Trading**.

**Tab:** Choose a tab under the title: **Orders**, **Trades**, **Positions**, **Automation** or **Instruments**. A tab shows only when your role holds the matching capability and the server serves it. **Orders** always shows.

**Access needed:** You need access to at least one of Orders, Trades, Positions, Instruments or Automation. **View** lets you read. **Edit** lets you make requests. Each tab follows its own tool, so you may see some tabs and not others.

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

**Columns:** the column chooser adds order id, external id, time in force, source, value,
**Filled** and more. **Last change** shows who changed the order and when. Until order-event
recording is switched on for your group, **Last change** shows a dash. Market, average price,
IP address and approver appear when your group's data includes them.

**Open an order:** tap a row to see the order's details and its lifecycle: Created, Sent to
broker, Filled or rejected, and Settlement. Settlement shows "not tracked". Below it, the
**Change timeline** lists each recorded change to the order, oldest first. **Open in
History** shows every change to that order.

**History mode:** switch **Current** to **History** to see every change to orders, built from
change events, with the before and after values. Filter it by the kind of change and by who
made it. Until order-event recording is switched on, History and the change timeline are empty,
and the note under the list says what it covers and when recording started.

**Stale data:** a list you opened before shows at once with the time it was loaded. Nothing
refreshes by itself. Tap **Refresh** to load it again.

**Export:** the export runs in the background. Find the file under Reports, on the Exports
tab.

## Trades

This tab appears when your role can view transactions and the server has the trades list.

**What it lists:** executed fills, built from transactions, one row per trade, newest first.
A trade shows here only if fills were synced from a broker or imported from a journal CSV for
that account. Orders that were placed but never reported as fills are not trades.

**Columns:** time, client, account, symbol, side, quantity, price, value, realized P&L and
currency. The column chooser adds the rest. Green is a gain and red is a loss. A dash means the
value was not recorded.

**Currencies:** amounts are shown in the account's own currency and are never added together.

**Search and filters:** search by symbol, client, trade id or account id. Each column heading
opens its own filter and sort. Tap a row to see every field in a read-only sheet.

## Positions

This tab appears when your role can view positions and the server has the positions list.

**What it lists:** the positions of journal accounts only, meaning accounts a client imported
or journaled by hand, one row per account and symbol. Positions in accounts connected live to a
broker are not stored here and are not listed, so this is not a total of what your clients
hold. A note under the table says so.

**Columns:** symbol, client, account, quantity, average cost, market value, unrealized P&L,
P&L percent and currency. A negative quantity is a short position. Amounts are in each
account's own currency and are never added together. A dash means the import did not have the
value.

**Search and filters:** search by symbol, client or account id. Each column heading opens its
own filter and sort. Tap a row to see every field in a read-only sheet.

## Automation

This tab appears with your Automation access. **Auto-trading systems** lists each system
that has recorded trade signals, one row per system and client. **Status** is Active, Idle or
Failing, worked out from recent signals. **Last signal** shows in your local time; the detail
panel also shows the exact UTC time. The list is built from recorded signals, so it can be
empty or miss signals sent before recording began. The note under the table says what it
covers. You can filter and sort by system, client, status, last result, last signal and
signals in the last 24 hours. You cannot pause, resume or stop a system from here yet.

**Sent signals:** the second view under Automation lists each trade signal your systems sent:
when, system, symbol, side, status, order, client and account. The column chooser adds account
name, broker, updated, signal id and user id. The **System** column shows the name the strategy
sent, and a dash for signals recorded without one. The list is empty until signal recording is
on for your group, and the note under it says what it covers.

**Send trade signal** and **Rebalance a group** work as before and open the existing tools.
With View access you see a note that sending and rebalancing need Edit access. **Rebalance a
group…** and **Send trade signal…** are also available from the legacy tools menu.

## Instruments

This tab is a read-only catalogue of instruments: symbol, name, asset class, market, exchange
and sector. Tap a row to see every field. It appears when your role can view instruments and
the server has the catalogue.

Instrument settings and change requests appear when they become available. When your group has
them, the list also shows each instrument's settings and **Set at**, which tells you where each
setting comes from: platform, market, group or this security.

**Request a setting change…:** change the trading mode, minimum size, lot size or order
step for one security. Give a reason. This is a request.
