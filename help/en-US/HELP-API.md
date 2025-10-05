# 🔑 API Management

The **API Management** screen allows you to manage your TradeGrub API keys — used for secure integrations with external services like **TradingView** or **custom REST APIs**.

---

## 📋 API Keys Table

All existing API keys are displayed in a simple, easy-to-read table.

| Name | Key | Permissions | Created Date | Actions |
|------|-----|--------------|---------------|----------|
| My Trading Key | `tgx4c...9uP` | TradingView | 2025-09-20 | 🗑️ Delete |
| REST Access | `tgx5a...7dF` | REST | 2025-09-22 | 🗑️ Delete |

### Table Columns
- **Name** → The label you assign when creating the key.
- **Key** → The unique identifier used for authentication.
- **Permissions** → Defines what the key can access (e.g., `TradingView`, `REST`).
- **Created Date** → The date when the key was generated.
- **Actions** → Use the 🗑️ **Delete** icon to remove the API key permanently.

> ⚠️ **Important:** Deleting an API key immediately revokes its access.  
> Any connected services (like TradingView webhooks) using that key will stop working.

---

## ➕ Creating a New API Key

Tap the **“+” (Add)** button in the top-right corner to create a new key.  
You will be prompted to specify:

| Field | Description |
|--------|--------------|
| **Name** | A friendly name to identify this key (e.g., *TradingView Signals*). |
| **Permissions** | Choose one or both: <br> - **TradingView** → Required to receive and process TradingView webhook signals. <br> - **REST** → Required for accessing TradeGrub REST APIs. |

Once created, the new API key will appear instantly in your table view.

> 💡 You can create multiple keys — for example, one for your personal TradingView account and another for your automated REST integration.

---

## ⚙️ Best Practices

- Keep your API keys **private and secure**.
- Use **separate keys** for different integrations.
- Revoke (delete) unused or compromised keys immediately.
- Never share your API key publicly or in screenshots.

---

## 🧩 Example Use Cases

| Scenario | Required Permission |
|-----------|---------------------|
| Sending TradingView buy/sell signals | TradingView |
| Making REST API calls to TradeGrub | REST |
| Combined trading automation setup | TradingView + REST |

---

## 🆘 Tips
- Tap the **info (ℹ️)** icon in the top-right corner for quick help.
- You can always re-create a key if it’s accidentally deleted.
- API key actions are synced instantly with your account — no app restart required.
