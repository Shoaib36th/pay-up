# 💳 PayUp! — Group Bill Splitter

A simple, interactive Python CLI tool that helps you calculate bill splits, tips, and service charges effortlessly among friends or colleagues.

---

## 🌟 Features

* **Custom Event Tagging:** Keep track of what the expense was for (e.g., Dinner, Road Trip, Gift).
* **Flexible Service Charge / Tip Calculation:** Input tip percentages seamlessly.
* **Automatic Per-Person Breakdown:** Calculates exact individual contributions based on group size.
* **Formatted Currency Output:** Cleans up decimals into readable standard monetary formats (`$XX.XX`).

---

## 🚀 How It Works

1. Prompts for the event name or occasion.
2. Asks for the total bill cost before tip.
3. Prompts for the tip or service charge percentage (e.g., `20` for 20%).
4. Asks for the number of people splitting the bill.
5. Displays a neat cost breakdown including total service charge, grand total, and per-person cost.

---

## 📋 Example Usage

```text
Welcome to PayUp!

What was the event or occasion? Team Lunch
How much was it? 125.50
Was there a tip or a service charge? Enter a whole number (e.g. 20 for 20%): 15
How many people were in your group? 4

Here's the breakdown for Team Lunch:

Cost: $125.50
Service charges: $18.82
Group size: 4
Grand total: $144.32

Each person must PayUp: $36.08
