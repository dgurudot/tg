# 🔔 Set Alert

The **Set Alert** feature allows you to create alerts or automated order triggers based on real-time market conditions.

---

## 🧭 Overview

You can configure alerts for any trading symbol (e.g., **BTC/USDT**) and define conditions such as **price**, **volume**, or **mark** value that will trigger an **Alert** or **Place Order** action.

---

## ⚙️ Fields Description

| **Field** | **Description** |
|------------|-----------------|
| **Symbol** | The instrument or trading pair for which you want to set the alert (e.g., BTC/USDT). |
| **Alert** | Select the metric to track — options include **MARK**, **BID**, **ASK**, or **VOLUME**. |
| **Trigger** | Choose the trigger condition — typically `>=`, `<=`, `==`, etc. It determines when the alert activates. |
| **Threshold** | Define the numeric value that will trigger the alert once reached or crossed. Use **+** or **–** to adjust the threshold incrementally. |
| **Action** | Select what happens when the trigger condition is met:<br> - **Alert** – Receive an in-app notification.<br> - **Place Order** – Automatically execute a buy or sell order. |
| **Side** *(Visible for Place Order only)* | Choose **Buy** or **Sell** to define the trade direction. |
| **Value** *(Visible for Place Order only)* | The trade size. Can represent **units** or **amount** depending on the selected type. |
| **Type** *(Visible for Place Order only)* | Choose between **Unit** (number of shares or coins) or **Amount** (total value in currency). |

---

## 🧩 Actions

- **Create** – Saves and activates the alert.
- **Cancel** – Discards the current configuration.

---

## 💡 Tips

- The **MARK**, **BID**, **ASK**, and **VOLUME** values displayed at the top update in real-time to help you fine-tune your threshold.
- Alerts remain active until manually deleted or triggered (based on your configuration).
- When setting a **Place Order** alert, ensure you have sufficient balance and trading permissions enabled.

---

## 🛡️ Example Use Cases

1. **Price Alert:**  
   Trigger an alert when BTC/USDT **MARK ≥ 125,000**.

2. **Automated Order:**  
   Place a **Sell order** when BTC/USDT **MARK ≤ 120,000** with a quantity of **0.5 Units**.

---

## 🧭 Accessing Help

Tap the **ℹ️ (info)** icon on the top-right corner of the screen for quick in-app guidance.
