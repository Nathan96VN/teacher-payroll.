# Teacher Payroll · Lương Giáo Viên

A bilingual (Vietnamese / English) payroll calculator for language centres in Vietnam.
Single self-contained `index.html` — no build step, no dependencies.

## What it does
- Per-teacher weekly schedule + monthly calendar
- Admin marks time deductions per day (with optional reason) for dispute resolution
- Accurate Vietnam 2026 personal income tax + social/health/unemployment insurance
- Holiday multipliers, VND or USD-based pay, resident / non-resident / expat handling
- Clean bilingual payslip with PDF and Excel export
- Company logo and details on every payslip

## Deploy on Render (Static Site)
1. Push this repo to GitHub.
2. In Render: **New → Static Site**, connect this repository.
3. Settings:
   - **Build command:** *(leave blank)*
   - **Publish directory:** `.`
4. Create — Render gives you a live URL.

## Important
This is a **calculation tool**, not a filing system. Figures are estimates based on
published 2026 rates. The centre remains responsible for verifying and filing correct
tax and insurance. Have a Vietnamese lawyer/accountant review before commercial use.

Current version does **not** save data between sessions (no database yet).
Saved schedules, login, and dispute history require the backend build (next step).
