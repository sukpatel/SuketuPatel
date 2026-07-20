# Freedom Number — Money Calculators

A single-page site with three private, no-login financial calculators — built for [suketupatel.me](https://suketupatel.me), styled in Half Past Chai's green-and-cream palette.

Everything runs client-side in the browser. No data is stored, no data is sent to a server — nothing to log in to, nothing to lose.

## What's inside

### 🎯 Freedom Number (retirement calculator)
A 4-step guided flow that turns your savings, debt, and goals into two numbers:

- **Freedom Number** — the portfolio size needed to sustain your target annual retirement income, based on your chosen safe withdrawal rate
- **Freedom Age** — the age you'll hit that number, projected year by year from your current savings and monthly contributions

Also included:
- Optional spouse/partner fields (age, accounts, and monthly contribution) to plan as a household
- House value + remaining mortgage input — home equity is calculated automatically, no manual math
- A **net worth snapshot** that includes vehicle value for a full picture — while keeping cars out of the Freedom Number itself, since they're depreciating assets, not retirement fuel
- A growth chart, a milestone table (value at +5/10/15/20/25/30 years), and a **personal playbook**: a few "what you're doing well" notes plus 3 prioritized, personalized next steps based on your actual numbers

### 📈 Investment Growth
A simple compound-growth calculator: starting amount, monthly contribution, years, and expected return in → projected future value out, with a chart splitting what you contributed from what the market grew for you.

### 🏠 Mortgage Payoff
Enter home price, down payment, rate, term, and an optional extra monthly payment to see:
- Your monthly principal & interest payment
- Your projected payoff date
- Total interest paid and total cost of the loan
- If you add an extra payment: how much interest and time it saves you, plus a chart comparing the standard payoff schedule against the accelerated one

## Tech

- Single `index.html` file — no build step, no dependencies to install
- Vanilla HTML/CSS/JS, with hand-drawn SVG charts (no charting library)
- Fonts loaded from Google Fonts (DM Serif Display, DM Sans, JetBrains Mono)
- Fully responsive down to mobile

## Running locally

Just open `index.html` in a browser — that's it. No server, no `npm install`.

## Deploying

This site is deployed via **GitHub Pages** with a custom domain pointed at `suketupatel.me`. To update it:

1. Replace `index.html` in this repo with your changes
2. Commit and push to the branch GitHub Pages is set to build from (usually `main`)
3. GitHub Pages rebuilds automatically — changes are usually live within a minute

## Disclaimer

These calculators give estimates based on the numbers you enter and simplified assumptions (fixed annual returns, no taxes, no market volatility). They're a starting point for thinking about your finances, not financial advice.
