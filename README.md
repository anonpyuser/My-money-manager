# My Money Manager

A simple iPhone-friendly, offline-capable paycheck and bill planning web app.

## Features
- Weekly paycheck budget and eight-week forecasts
- Upcoming bills, recurring due dates, and paid tracking
- Confirmed vs. estimated bill amounts
- Income and expense entries
- Calendar reminder export (.ics)
- Local JSON backup and restore
- Add to Home Screen on iPhone


## Debt Payoff & Credit Health
- Open the **Debt** tab or `debt.html` to enter card balances, APRs, credit limits, and minimum payments.
- Compare debt avalanche (higher APR first) versus snowball (smaller balance first) with a user-entered extra monthly payment.
- See approximate monthly interest and the average weekly paycheck allocation for the selected debt payment scenario.
- Record credit score check-ins by report date and score model; the app cannot access your actual credit report or predict score increases.
- Debt entries are stored only in local browser data and included in app backup exports. No private debt details are committed to this repository.
- Debt minimums are **not** added to the separate Bills forecast automatically; check for overlapping entries to avoid double counting.
- Projections assume constant APRs, monthly interest approximations, no new purchases or fees, and no changes to payment terms. Confirm actual charges with statements.

## Privacy
The repository contains only the **blank app**. No linked bank information, statements, personally identifiable account data, or personal bill data is included. Your entries are stored in your browser's local storage, **not** synced to GitHub or to banking accounts. Back up your data regularly. Browser data may be lost if you clear website data or switch devices.

Never commit personal setup files, exported backups, transaction CSVs, or account statements.

## Publish with GitHub Pages
1. Open the repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Choose branch **main**, folder **/(root)**, then **Save**.
4. Once GitHub confirms deployment, open the Pages URL in Safari on your iPhone.
5. In Safari, choose **Share → Add to Home Screen**.

Note: Under **GitHub Free**, Pages requires a **public repository**. GitHub Pro and some organization plans can host Pages from private repositories. A Pages website may be publicly accessible even when the repository is private; don't put financial details in the website files.

## First-time setup
1. Open the app in Safari.
2. In **Settings**, enter weekly net pay and your next payday, or import your **private setup JSON** (do not upload it to GitHub).
3. Review and confirm all due dates and amounts; automatically detected recurring charges can be estimates.
4. Enter missing bills, weekly essentials, and savings goals.
5. Export reminders from the app to your calendar. These do not become push notifications until you import them into a calendar.

This app is a local planning tool. It **does not connect to banks directly, make payments, or automatically send push reminders**.
