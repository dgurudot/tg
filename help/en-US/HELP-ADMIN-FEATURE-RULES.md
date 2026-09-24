# Feature control

You decide which parts of the app each user can use. Each part is a **feature**. You
turn features on or off for everyone, for a group, or for one user.

## How to Open

**Where you see it:** in Setup, on the **Groups & features** tab, where you request a feature change. On a wide screen choose **Setup** in the side menu. On a tablet or phone open the menu drawer with the menu button at the top left, then choose **Setup**. You need Edit on Groups & features to ask for a change. Approve on Groups & features is needed to decide one. For one group or one user, use **Manage Group Features** or **Manage User Features** in the menu, below the main screens. A client's own features show on the **Access** tab of their profile in Clients.

## Which features you can control

You control the features on a fixed list. You cannot type in a new name.

**Modules:** the screens in the bottom bar and in the More menu.

| Feature | Turning it off for a user |
|---|---|
| Dashboards | Dashboards leaves their menu. The next screen in their menu opens first instead |
| Charts | Charts stays hidden, even if the user signs in from the charts site |
| Portfolio | Portfolio leaves their menu |
| Signals | Signals leaves their menu |
| Orders | Orders leaves their menu |
| Insights | Insights leaves their menu |
| Accounts | Accounts leaves their menu, so they cannot add or manage broker accounts from it |
| Learning | Learning leaves their menu |
| Markets | Markets leaves their menu |
| Messages | Messages leaves their menu |
| Preferences | Preferences leaves their menu, along with the settings it holds |
| Rebalancer | Rebalancer leaves their menu |
| Risks | Risks leaves their menu |
| Rooms | Rooms leaves their menu |
| Screeners | Screeners leaves their menu |
| Support | Support leaves their menu |
| Watchlists | Watchlists leaves their menu |

**Cloud sync:** these are off unless you turn them on.

| Feature | Turning it off for a user |
|---|---|
| Cloud sync: transactions | Their transactions stay on their device only |
| Cloud sync: orders | Their orders stay on their device only |
| Cloud sync: journal | Their journal entries stay on their device only |
| Cloud sync: positions | Their positions stay on their device only |
| Cloud sync: P&L | Their profit and loss stays on their device only |

**Bottom bar or More:** a module sits in the bottom bar or under More depending on its
place in the user's menu, and users can reorder their menu. Turning a module off removes
it from both.

**Administration:** you do not control it here. It appears for users who hold an admin
role.

## The four settings

**Global:** on or off for everyone. This is the starting point for every user.

**Kill switch:** turns a feature off for everyone, no matter what else is set. Use it when
a feature must stop right away.

**Group:** include or exclude a feature for everyone in a group.

**User:** include or exclude a feature for one user.

## How to predict what a user gets

Work through these steps in order and stop at the first one that gives an answer.

1. **Kill switch:** if it is on, the feature is off. Stop.
2. **User:** if the user has their own setting, it decides. Exclude means off, include
   means on. If both are set, exclude wins. Stop.
3. **Groups:** if any of the user's groups has a setting, look at all of them. If any
   group excludes the feature, it is off. If they only include it, it is on. Stop.
4. **Global:** the global setting decides.

The most specific setting wins: a user's own setting beats their groups, and their groups
beat the global setting. The kill switch beats all of them.

## Examples

| Global | Kill switch | Groups | User | The user gets | Because of |
|---|---|---|---|---|---|
| On | Off | None | None | On | Global |
| Off | Off | Traders: include | None | On | Group Traders |
| On | Off | Traders: include, Trial: exclude | None | Off | Group Trial, because exclude wins between groups |
| On | Off | Traders: include, Trial: exclude | Include | On | The user's own setting |
| Off | Off | Trial: exclude | Include | On | The user's own setting beats the group |
| On | Off | Traders: include | Exclude | Off | The user's own setting |
| On | On | None | Include | Off | Kill switch |
| On | Off | None | Include and exclude | Off | User, because exclude wins at the same level |

## Why a change needs approval

Every feature change is a **request**. A second admin approves it before it takes effect,
and every change is recorded. This stops one person from switching a feature off for many
users by mistake, and it shows who changed what and when.

**To request a change:** you need **Edit** on Groups & features.

**To approve a change:** you need **Approve** on Groups & features, and you cannot approve
your own request.

See Approvals for how a request moves.

## Where to see the result

In Administration, each feature shows its **effective state** and the **setting that
decided it**:

**For everyone:** the global setting and whether the kill switch is on.

**For a group:** the group's own setting, and what a member gets if they have no setting
of their own.

**For a user:** what the user gets, which setting decided it, and any other settings that
were overridden.

**When users see a change:** after it is approved, a user sees it the next time the app
refreshes their access. This happens within 15 minutes, or sooner when they reopen the
app.

## Good to know

**Live and test are separate:** a setting made in your live environment never affects your test environment, and the other way round.

**Users need no role:** regular users do not need a role to get features. Roles are only
for admins.
