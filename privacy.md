---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**Stride League**  
**Effective date:** November 27, 2026

Stride League is operated by **Judson Miller**, as an individual and not as a company. This is the Privacy Policy for the Stride League app on iPhone and Android.

This policy says what the app collects, why, who handles it, how long it is kept, and how to delete it. It is the policy linked in the app and on the store listing.

**Contact**

Judson Miller  
106 E Rutherford St  
Landrum, SC 29356  
United States  
nckoffeeking@gmail.com  
(828) 817-6981

Email is the best way to reach him about privacy. Please do not send medical records.

## The only health data

The only health data Stride League reads is the **daily step total** from Apple Health (HealthKit) on iPhone or from Health Connect on Android, filtered to **one step source you choose** (for example **iPhone**, **Apple Watch**, **this phone** on Android, or **Samsung Health** on Android). The app also reads which app or device recorded those steps. Short-lived records on your phone may be read to identify that source; only the daily total, source label, origin id, **device model** (handset audit field), and sync time are stored on our servers. People in a private race with you can see your **source label** on standings; they do **not** see your handset model or internal plausibility flags. The **device model** is visible only to you and to the Stride League team, and is used only for fair-play checks. Stride League does not connect to third-party fitness accounts; it only reads what you allow through Apple Health or Health Connect.

**Fair-play limits on step totals.** A single sync of more than **200,000 steps** for one day is rejected. A day over **60,000** may be flagged for the race **creator** only. A high day isn’t an automatic ban or removal from a race.

The app does not read heart rate, sleep, workouts, calories, distance, weight, location trails, clinical records, or any other health metric. It does not write anything back to Apple Health or Health Connect. It does not store step data in iCloud.

You can say no. The app still opens. Totals stay empty or show the last real sync. The app will not show a zero that pretends a sync happened.

## Data collected, why, and who handles it

“Collected” here means the app sends the information off your phone to run Stride League. Service providers below process it only on Judson Miller’s instructions to run the app. They are not allowed to use it for their own advertising or to sell it.

**Account identifier.** When you sign in with Apple, Google, or an **email sign-in link**, Stride League receives the identifier Supabase Auth assigns and, for Apple or Google, the identifier that provider gives it. There is no separate Stride League password stored by us. This is required to have an account. It is used to sign you in and keep your data attached to you. **Supabase** (database and sign-in host, in the United States) stores it. Apple, Google, or the email provider handles the sign-in you started. They do not receive the database of step totals.

**Email address.** When you use **Sign in with Apple**, Apple may hide your email. When you use the **email sign-in link**, you choose the address and Supabase stores it to deliver the link and to match support or deletion requests. The app does not require an email if you use Apple or Google only. It is not shown to other people in a race.

**Display name.** Required. The app shows your initials, not a photo. The name labels your profile and, if you join a race, the board for that race. People in that race can see it. Supabase stores it.

**Phone timezone.** Used so your own day, week, and month match your calendar. A race uses one timezone saved when that race is created (the creator’s phone timezone at that moment). This is not GPS and not a location trail. Supabase stores it.

**Daily step total.** Optional. Read when you open the app, and in the background when the operating system allows it. Used to show your own today, day, week, month, and daily average, and to show standings in a private race you join. Supabase stores it in the United States. People in that race can see the step totals for that race, with display names. Your personal day history is not shown to them.

**Race details.** If you create or join a race: the name, invite code, timezone, start and end, who is in it, when you joined, and which days count. A race is private, holds up to **5 people** on the free tier (or up to **20** with Stride League Plus), and is joined by code. There is no public league. Someone who enters the code can see the name, dates, member count, and timezone before they join. They do not see step totals until they are in the race. If you join after the start, only days from your join day forward count. Supabase stores this. Members of the race can see the roster and the race’s step totals.

**Push token.** Only if you allow notifications. Used to deliver a message that a race locked (including who won) or, optionally, that someone passed you. There is no daily nag. Apple Push Notification service or Google’s push service delivers that message. The message is not a copy of your step history.

**Reports and blocks.** If you report another member, the app stores the reason, an optional note, which race it came from, and who reported whom in Supabase. A notification is sent to **nckoffeeking@gmail.com** so the Stride League team can review it within **24 hours**. If you block someone, Supabase stores that you blocked them. Their name is hidden on your phone; other people in the race still see them on the shared board.

**Purchases.** If you subscribe to **Stride League Plus**, or you redeem an Apple or Google offer code for it, Apple or Google processes the subscription and stores the payment method when the store asks for one. Stride League receives a transaction identifier, the product, the time, and whether the subscription is active, refunded, or expired. It uses that to set how many people a race you create can hold and to restore the subscription on a new phone. **RevenueCat** processes the receipt for Judson Miller and notifies the Stride League server. RevenueCat does not receive step totals, display names, or health data. Supabase stores the transaction identifier and roster cap rules tied to your account. Purchase history is kept for as long as the account exists so restore, refund handling, and tax records still work. It is not used for advertising and it is not sold. Signing up, creating a race of up to 5 people, and joining a race do not ask you for a card inside Stride League.

**Crash and diagnostic data.** Stride League uses **Sentry** for crash and diagnostic reports. A report includes device and operating-system information, the app version, and an internal account ID (the Supabase auth id) so related errors can be connected. It does not include step data, messages, email, or display name. IP addresses are not stored. Sentry keeps reports for about **90 days**. These reports are used to find and fix problems in the app. They are not used for advertising. There is no separate product-analytics product in this version of the app. You cannot turn crash reports off separately from using the app.

The app has **no ads**. It does not collect contacts, photos, precise location, the advertising identifier, a list of your other apps, or SMS.

## Service providers

- **Supabase**: database and account host, in the United States. Processes the account, name, email if any, timezone, step totals, race data, reports, blocks, and purchase-related fields the server stores.
- **RevenueCat**: purchase receipts and the app user id only, so the server can set a race’s size cap and Plus status. Not step totals or health data.
- **Apple**: sign-in, Apple In-App Purchase, Apple Health on the device, and push delivery if you allow notifications. Handles the sign-in and purchase flows you start. The step total stays on the device until the app reads it. A race notification is not your step history.
- **Google**: sign-in, Google Play Billing, Health Connect on the device, and push delivery if you allow notifications. Handles the sign-in and purchase flows you start. The step total stays on the device until the app reads it. A race notification is not your step history.
- **Sentry** receives crash and diagnostic reports, including device and operating-system information, the app version, and an internal account ID (the Supabase auth id). Those reports do not include step data, messages, email, or display name. IP addresses are not stored. Sentry keeps reports for about **90 days**.

No other third party receives personal information or step totals for its own use.

## Health Connect and Apple Health — limited use

This is the limited-use promise for Apple App Store Review Guideline 5.1.3, Guideline 5.1.2(vi), Apple’s HealthKit rules, and Google Play’s Health Connect permissions policy and Health apps policy.

- The permitted use is fitness and wellness: your own step summary, and standings in a private race you joined. Those features are on screen in the app.
- Step data is used only for that. It is not used for a hidden second purpose.
- It is **never used for advertising or marketing**, including personalized or interest-based ads, and it is not put into an ad or measurement tool.
- It is **never sold**, and it is not given to data brokers or information resellers.
- It is not used to judge credit, lending, insurance, or employment.
- It is not used to train an advertising or general-purpose AI model.
- It is not used as a medical device, for diagnosis or treatment, or as HIPAA protected health information. Stride League is not a healthcare service.
- It is not written back into Apple Health or Health Connect.
- It is not stored in iCloud.
- It is shared only as needed to run the feature: stored by Supabase so the app can show it to you and, for a race, to people in that race. You agree to that storage when you connect health access and use the app.
- A race notification, if you allow notifications, goes through Apple’s or Google’s push service. That message is not your step history.
- Judson Miller does not browse step totals out of curiosity. He may see them only if you contact him and he needs them to answer you, to investigate abuse or keep the service secure, to comply with the law, or as a combined figure that is not tied to you.
- Other transfers, uses, or sale of Health Connect or HealthKit step data are not allowed. The only added cases are security (such as investigating abuse), a legal duty, or a sale or transfer of the app itself, and in that last case he will tell you before step data moves with it.

You can turn health access off in system settings at any time.

## Security

The app talks to the server over HTTPS. Supabase encrypts stored data at rest as part of its hosted database. Access is set up so your personal day totals are available to you, and a race’s totals are available to people in that race. Use a device passcode and the security on your Apple or Google account.

No storage method is perfect. Unauthorized access cannot be promised impossible.

## How long data is kept

While your account exists, account information, personal step totals, race information, and **Stride League Plus** status are kept so the app can show your history and your races and apply a race size cap. The account does not expire. **Stride League Plus** is optional. Apple or Google processes the subscription and stores the payment method. The app does not receive the card number. **RevenueCat** receives the Supabase account id and whether Plus is active, and notifies the Stride League server. Supabase stores that status with the account: whether Plus is active, the product id, when it expires, and whether it will cancel at the end of the period. The store transaction id is stored on the RevenueCat webhook record. Plus renews each month until the subscriber cancels it with Apple or Google. A race of up to **5 people** does not need Plus. Deleting the account removes Plus status on Stride League servers. It does not cancel the Apple or Google subscription. After deletion, the webhook record can keep the store transaction id with the account id removed.

Sentry keeps crash and diagnostic reports for about **90 days**, then deletes them. They are not used to rebuild an account.

After you delete the account:

- Sign-in, email (if any), display name, phone timezone, push token, and **personal day-by-day step totals are deleted** from the live database when the deletion is completed.
- You are removed from races that have not locked yet, including a race still in its 24-hour catch-up window.
- On a race that has **already locked**, the step totals already counted stay so the result does not change. Your name is removed. The board shows **Former member**. Those totals are kept for as long as that race result is kept while Stride League operates, and they are not used for anything else. They are deleted if the app is shut down.
- The profile row can remain as a blank tombstone so the locked race still has a member to point at. The name on it is cleared. This is not a frozen account. You cannot sign in again.
- Copies in provider backups are not used to restore your name or personal step history. They are removed within **30 days** after the live deletion.

Leaving a race, or being removed by the person who created it, is not the same as deleting your account. On a locked race, leave or removal may still show the display name you had.

## Deleting your account

You can delete the account in two ways. Neither one merely freezes it.

**In the app.** Open Stride League, go to the **You** tab, choose **Delete account**, and confirm. Deletion of the live account starts when you confirm.

**Without the app.** Use [Delete your Stride League account](https://koffeekinggamer.github.io/stride-league-legal/delete-account/). That page tells you what to email. You do not need to reinstall the app. A request that can be matched to an account is completed within **30 days**.

What is deleted and what is kept is in the section above, and on that page.

## Children

Stride League is for people **13 and older**. It is not directed at children under 13. It is not an Apple Kids Category app and it is not a Google Play Families app.

Do not create an account if you are under 13. The app does not knowingly collect personal information from a child under 13. If Judson Miller learns an account belongs to someone under 13, he will delete it the same way as an account deletion: off races still going, name cleared, **Former member** and the existing step totals only on a race that already locked, and personal step totals and sign-in deleted.

A parent or guardian can email nckoffeeking@gmail.com about an under-13 account.

If you are 13 or older but under 18, use the app only if a parent or guardian agrees. The [Terms of Use](https://koffeekinggamer.github.io/stride-league-legal/terms/) say the same thing. The app does not add a separate parent account.

## Your choices and US privacy rights

You can:

- Deny or revoke health access, and keep using the app.
- Leave a race.
- Turn notifications off in system settings.
- Sign out, which stops the app’s use of Apple, Google, or email sign-in until you sign in again.
- Delete the account in the app or from the [deletion page](https://koffeekinggamer.github.io/stride-league-legal/delete-account/).
- Email nckoffeeking@gmail.com to ask what is held about you, to ask for a copy, or to ask for a correction of account information. Step totals come from Apple Health or Health Connect. The app cannot type a replacement number.

**California.** If you live in California, you can ask Judson Miller to tell you the categories and specific pieces of personal information collected, the sources, the purpose, and who it is disclosed to; to delete personal information, subject to the locked-race totals described above; and to correct inaccurate account information. He will not discriminate against you for asking. Stride League does not sell personal information and does not share it for cross-context behavioral advertising, so there is no separate “Do Not Sell or Share My Personal Information” switch. Email nckoffeeking@gmail.com. He will respond within **45 days**. If he needs more time, he will email you and may take one extra 45 days, as California law allows. He will match the request to the account from the display name and the sign-in method. He will not ask you for a government ID.

**Other US states.** If your state gives you a right to access, correct, or delete personal information (including Colorado, Connecticut, Virginia, Utah, Texas, and Oregon), email the same address. He will not discriminate against you for asking. If a request is denied, reply to that email and ask him to review the decision.

Stride League is operated from the United States. Information is stored in the United States. If you use the app from another country, your information is processed in the United States.

## Changes

If this policy changes, the new version is posted at [this same address](https://koffeekinggamer.github.io/stride-league-legal/privacy/) with a new effective date. If a change materially affects step data or who it is shared with, Judson Miller will tell you in the app before that date and will ask you to agree in the app before using step data in the new way. If he has your email, he may email you as well. The copy at https://strideleague.me/privacy/ is the one that applies.

## Contact

Judson Miller  
106 E Rutherford St  
Landrum, SC 29356  
United States  
nckoffeeking@gmail.com  
(828) 817-6981

The [Terms of Use](https://koffeekinggamer.github.io/stride-league-legal/terms/) are a separate document. They are governed by the laws of the State of South Carolina, USA.
