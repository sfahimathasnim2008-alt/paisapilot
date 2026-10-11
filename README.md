# 💸 PaisaPilot – Make ₹10,000 last 30 days

**Live demo:** <PASTE_LIVE_LINK_HERE>

A Gen Z personal finance app where every financial decision has visible, connected consequences.

## Problem
Gen Z users juggle tight budgets, but income, bills, subscriptions, goals and surprise expenses live in separate silos, so they can't see how one choice ripples through the month.

## Solution
PaisaPilot links all of them into one model. Before committing, users **simulate** a decision and see its effect on balance, daily allowance, savings goals, the day-30 forecast, financial risk and a 0–100 health score.

## Features
- Dashboard: balance, safe daily allowance, health score, risk level, forecast chart, smart insights
- Decision simulator (Now vs After): spend once, subscribe, save to goal, cancel subscription
- Goals that reserve money and lower the daily allowance until funded
- Bills and subscriptions with yearly cost and share of income
- Surprise expenses (pay from balance or emergency fund)
- 30-day report card, replayable

## Model
- Allowance = (balance − unpaid bills − unfunded goal plans − ₹500 buffer) ÷ days left
- Forecast = balance − upcoming bills − goal reserve − smoothed avg daily spend × days left
- Health = forecast cash 30 + commitment ratio 20 + goal funding 25 + discipline 15 + buffer 10

## Tech stack
React 18 · Vite 5 · SVG charts · localStorage · GitHub Actions (Pages deploy)

## Run locally
```bash
npm install
npm run dev
```
Build: `npm run build`

## Built with
Vibe coding with Claude.
