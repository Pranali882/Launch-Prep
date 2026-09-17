# EstelMiti Privacy Policy

**Effective date:** [fill in before publishing to Play Console / App Store Connect]
**Contact:** estelmiti882@gmail.com

This policy covers the EstelMiti mobile and web application ("EstelMiti",
"the app"). It's written to match exactly what the app actually does -
nothing here is aspirational or boilerplate that doesn't apply.

## The short version

Everything you type into EstelMiti - your accounts, investments, loans,
goals, notes - stays on your own device. EstelMiti has no server, no
account system, and no way to see, store, or transmit your financial
data. The only thing the app fetches automatically over the internet is
a *public* foreign-exchange reference rate - data that flows *to* you,
not personal data flowing *away* from you. Stock and mutual fund prices
are looked up by you, on the official source's own website, not fetched
by EstelMiti - see "Third-party services" below for the full picture.

## What we promise, clearly

1. **Your financial data lives on your device.** Everything you track -
   investments, loans, goals, everything - is stored locally (Hive).
   EstelMiti has no server that holds it.
2. **Backup is always your choice, and it stays yours.** We never save a
   copy of your financial data ourselves. When you back up, you choose
   where it goes - your own device or your own cloud storage - and you
   can use it to restore, restart, or move your data privately, from
   any device, whenever you want.
3. **No ads, no promotion, no cross-sell - inside the app, ever.**
   EstelMiti doesn't try to sell you anything: not the investments you're
   tracking, not "accessories" around them, not a partner product, not
   a collaboration. If it isn't your own number on your own screen, it
   isn't in here.

## What's outside our control

EstelMiti is distributed through the **Google Play Store**. Google, as
the store operator, has its own standard visibility into things like
your installs, app crash reports, and basic device information (device
model, OS version) - that's true of every app on Google Play, governed
by Google's own Privacy Policy, and isn't something EstelMiti adds,
expands, or controls.

## What the app stores, and where

All entries you create (investments, loans, cash accounts, goals,
income, expenses, and any notes attached to them) are stored locally on
your device using on-device storage (Hive). This data is never uploaded
anywhere by EstelMiti. If you set a PIN or enable biometric app-lock,
that credential is also stored and checked entirely on your device.

## Backups are yours, and only yours

EstelMiti has an optional "Backup & restore" feature (More → Data). When
you use it, the app writes a single file containing your entries, which
you then choose where to save (your own device storage, a cloud drive
you control, etc. via your device's own share/save options) or where to
restore from. EstelMiti itself never holds a copy of this backup and
cannot recover, restore, or transfer your data for you - if a backup
file is lost, that data is genuinely gone. This is a deliberate
trade-off for never storing your data on a server we control.

## Third-party services we use, and why

The only data EstelMiti fetches automatically, from a backend we operate
(built on Supabase), is a **public foreign-exchange reference rate**
(USD/EUR/GBP to INR), updated daily. This connection:
- Sends no personal data, no entries, and no identifying information
- Is read-only - the app requests a public rate, nothing else
- Can be skipped entirely - the app is fully usable by entering your
  own values manually

For **stock, mutual fund, and other market prices**, EstelMiti does not
fetch or store anything on your behalf. Instead, the app shows you a
direct link to the relevant official public source (AMFI, NSE, BSE, RBI
Retail Direct, NPS Trust), which opens in your device's own browser -
you read the number there and type it into your own entry, the same as
looking up a price in a newspaper. One narrow exception: for stock
prices only, the app can still show a previously-collected reference
price from an automated feed that was switched off (as a precaution,
pending a compliance review of that data source's usage terms) - the
feed stopped updating as of 2026-09-11, so this number is a frozen
snapshot, not being refreshed, and this policy will be updated the
moment that feed is either resumed or fully removed.

EstelMiti also checks a single, non-personal remote setting (via the
same Supabase backend) that controls whether certain optional features
are turned on for everyone - this carries no user or device
information, only a yes/no flag.

We do not share data with, or receive data from, any advertising or
analytics company, because we don't use any.

## Permissions the app may ask for, and why

- **Internet** - to fetch the public market data described above
- **Biometric / device lock** - only if you choose to enable app-lock;
  used solely to unlock the app on your own device
- **File / storage access** - only when you choose to export a backup,
  import a backup, or import a CSV/Excel file of your own data; the app
  never accesses your files without you initiating that action

## Children's privacy

EstelMiti is not directed at children and we do not knowingly collect
data from children, in line with the fact that we do not collect
personal data from anyone, of any age.

## Your control over your data

Because everything lives on your device, you are always in full
control: delete any entry inside the app at any time, export a backup
whenever you choose, or uninstall the app to remove all locally stored
data. There is no account to delete and no server-side copy to request
removal of, because none exists.

## Changes to this policy

If EstelMiti's data practices ever change, this policy will be updated
first, in the same plain terms as above. One specific planned change,
not part of this launch: if an optional paid tier ships later with
Google/email sign-in, this section will be updated to say plainly that
sign-in stores only an email/Google ID and subscription status - never
your financial data, which stays local either way - and that our
support team can confirm you're a subscriber but cannot see a single
entry you've recorded.

## Contact

Questions about this policy or how EstelMiti handles data: estelmiti882@gmail.com
