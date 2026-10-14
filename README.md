# ActionMate — Your AI Financial Copilot
> **Think Smarter. Act Financially.**

ActionMate is a premium, modern fintech web application built for college innovation hackathons and student expos. It pairs an intelligent conversational **AI Financial Copilot** with an **Autonomous Action Agent** operating under a **Safe Human-in-the-Loop Protocol**.

---

## ✨ Features Built & Live

1. **Executive Financial Dashboard (`DashboardView.tsx`)**:
   - Total Net Balance, Monthly Income, Monthly Outflow, and Projected Savings.
   - Interactive 6-Month Cashflow Area Chart & October Category Breakdown Pie Chart using [Recharts](https://recharts.org).
   - Real-time Safety Net / Reserve Runway indicator (e.g., 72 Days).
   - Live Anomaly Alert badges for runaway expenses.

2. **AI Financial Copilot (`CopilotChatView.tsx`)**:
   - Dynamic conversational chat tailored for Indian student/young professional finances in Rupee (`₹`).
   - Intelligent spending leak diagnostics, SIP simulations, and reasoning about anomalies.
   - Generates action plans dynamically from chat prompts with instant cross-view deep-links.

3. **Autonomous Action Agent (`ActionAgentView.tsx`)**:
   - Natural language goal ingestion (e.g. *"Help me save ₹5,000 this month"*, *"Optimize Swiggy and Zomato spending"*).
   - Autonomous synthesis into granular action items with estimated savings and impact tiers (*Quick Win*, *High*, *Medium*).
   - **Zero-Unilateral-Debit Guarantee**: Requires user click confirmation before executing actions.
   - Real-time celebratory micro-confetti feedback upon action execution.

4. **Transaction Management & Anomaly Audit (`TransactionsView.tsx`)**:
   - Search by vendor/account/category.
   - Filters for Category, Inflow/Outflow, and Anomaly-only audits.
   - Interactive deletion and dynamic balance recalculation.

5. **Goal-Based Savings Vaults (`GoalsView.tsx`)**:
   - Visual progress bars, target deadlines, and required monthly SIP calculation.
   - Interactive "Deposit Funds" modal to simulate micro-allocation sweeps into liquid vaults.
   - "Create New Goal" modal with customizable accent themes.

6. **Smart Alerts & Sentinel Engine (`AlertsView.tsx`)**:
   - Notifications for dining overspending (e.g., 82% budget reached in 12 days), zombie subscriptions (Netflix 4K), and upcoming utility bills.
   - One-click action triggers directing users into the Action Agent.

7. **Quick Add Transaction Modal (`AddTransactionModal.tsx`)**:
   - Built-in heuristic sentinel that automatically detects and flags unusual single transactions (e.g. Dining > ₹1,200).

---

## 🚀 Running the Project

The application is running live:
- **Local URL:** `http://localhost:5173/`
- **Network URL:** `http://192.168.1.12:5173/`

To start or build manually:
```bash
# Start development server
npm run dev

# Production build test
npm run build
```
