# Workforce Housing — Tax Modeling Application

A free, browser-based tool that models the **federal income-tax effect** of owning a Highland Steel / ReadyPod Workforce Housing unit. Built for the Growth Circle community.

**Live app:** https://jocelynrenaud-commits.github.io/gc-wfh-tax-model/

## What it does

For the inputs you choose (filing status, income, unit, loan strategy, exit year), it shows:

- The **Year-1 §168(k) bonus-depreciation** tax saving, walked bracket by bracket.
- The **taxable rental income and deductible interest** every year you hold the unit.
- The **§461(l)** excess-business-loss cap and **NOL** carryforward.
- The **§1245 recapture** when you exit, stacked on your exit-year income.
- Interest-only vs. **pay-down-from-rent** loan modes, with a full repayment schedule.
- The **net cash at exit** by resale value.

Click any headline box or any underlined number for a step-by-step breakdown with charts. Every figure is cross-referenced to the tax code in the **Tax Authority & Citations** section.

## Built on current law

2026 brackets, standard deduction, and the §461(l) threshold per **IRS Rev. Proc. 2025-32**; 100% bonus depreciation per **IRC §168(k) / OBBBA (P.L. 119-21)**; §172(a)(2) 80% NOL limit; §1245 recapture. Verified against the source.

## Not tax advice

This is an **educational model for illustrative purposes only**. It is **federal income tax only** — state tax, self-employment tax, NIIT, AMT, and QBI are not modeled, and several positions (placed-in-service, at-risk, material participation) are assumptions the deal makes. **Errors are possible. Verify every figure with your own qualified tax advisor before acting.**

## Technical

Single self-contained HTML file — the chart library is embedded, so it works fully offline. No build step, no dependencies, no data leaves your browser.

Version 1.0 · June 2026 · Built by a Growth Circle member.
