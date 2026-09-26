---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**Stride League**  
**Effective date:** September 25, 2026

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

The only health data Stride League reads is the **daily step total** already added up by Apple Health (HealthKit) on iPhone or by Health Connect on Android. That total already combines a phone and a watch, so the same steps are not counted twice. The app stores that day’s number, which platform it came from, and when it was synced.

The app does not read heart rate, sleep, workouts, calories, distance, weight, location trails, clinical records, or any other health metric. It does not read raw step samples. It does not write anything back to Apple Health or Health Connect. It does not store step data in iCloud.

You can say no. The app still opens. Totals stay empty or show the last real sync. The app will not show a zero that pretends a sync happened.

## Data collected, why, and who handles it

“Collected” here means the app sends the information off your phone to run Stride League. Service providers below process it only on Judson Miller’s instructions to run the app. They are not allowed to use it for their own advertising or to sell it.

**Account identifier.** When you sign in with Apple or Google, Stride League receives the identifier that provider gives it. There is no separate Stride League password. This is required to have an account. It is used to sign you in and keep your data attached to you. **Supabase** (database and sign-in host, in the United States) stores it. Apple or Google handles the sign-in you started. They do not receive the database of step totals.

**Email address.** Only if Apple or Google shares one. Sign in with Apple can hide it. The app does not require an email to work. It is used to match a support or deletion request. Supabase stores it if it is received. It is not shown to other people in a race.

**Display name.** Required. The app shows your initials, not a photo. The name labels your profile and, if you join a race, the board for that race. People in that race can see it. Supabase stores it.

**Phone timezone.** Used so your own day, week, and month match your calendar. A race uses one timezone saved when that race is created (the creator’s phone timezone at that moment). This is not GPS and not a location trail. Supabase stores it.

**Daily step total.** Optional. Read when you open the app, and in the background when the operating system allows it. Used to show your own today, day, week, month, and daily average, and to show standings in a private race you join. Supabase stores it in the United States. People in that race can see the step totals for that race, with display names. Your personal day history is not shown to them.

**Race details.** If you create or join a race: the name, invite code, timezone, start and end, who is in it, when you joined, and which days count. A race is private, holds up to 20 people, and is joined by code. There is no public league. Someone who enters the code can see the name, dates, member count, and timezone before they join. They do not see step totals until they are in the race. If you join after the start, only days from your join day forward count. Supabase stores this. Members of the race can see the roster and the race’s step totals.

**Push token.** Only if you allow notifications. Used to deliver a message that a race locked (including who won) or, optionally, that someone passed you. There is no daily nag. Apple Push Notification service or Google’s push service delivers that message. The message is not a copy of your step history.

**Crash and diagnostic data.** Before the app is released for testing, crash reports will be collected by **one** of these tools: **Sentry** or **Google Firebase Crashlytics**. The tool receives crash logs, app version, device model, operating-system version, and an install identifier so repeated crashes can be grouped. It does not receive step totals, your display name, or your email. Crash reports are not combined with your step history. The tool is not used for advertising. There is no separate product-analytics product in this version of the app. You cannot turn crash reports off separately from using the app.

The app does not take payment. It has no ads and no in-app purchases. It does not collect contacts, photos, precise location, the advertising identifier, a list of your other apps, or SMS.

## Service providers

- **Supabase** — database and account host, in the United States. Processes the account, name, email if any, timezone, step totals, and race data.
- **Apple** — sign-in, Apple Health on the device, and push delivery if you allow notifications. Handles the sign-in you start. The step total stays on the device until the app reads it. A race notification is not your step history.
- **Google** — sign-in, Health Connect on the device, and push delivery if you allow notifications. Handles the sign-in you start. The step total stays on the device until the app reads it. A race notification is not your step history.
- **Sentry or Google Firebase Crashlytics** (one of the two, chosen before release) — crash reports. Processes crash and device diagnostics, not step totals.

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

While your account exists, account information, personal step totals, and race information are kept so the app can show your history and your races. The account does not expire. There is no subscription.

Crash reports are kept by the crash tool for up to **90 days**, then deleted by that tool. They are not used to rebuild an account.

After you delete the account:

- Sign-in, email (if any), display name, phone timezone, push token, and **personal day-by-day step totals are deleted** from the live database when the deletion is completed.
- You are removed from races that have not locked yet, including a race still in its 12-hour catch-up window.
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
- Sign out, which stops the app’s use of Apple or Google sign-in until you sign in again.
- Delete the account in the app or from the [deletion page](https://koffeekinggamer.github.io/stride-league-legal/delete-account/).
- Email nckoffeeking@gmail.com to ask what is held about you, to ask for a copy, or to ask for a correction of account information. Step totals come from Apple Health or Health Connect. The app cannot type a replacement number.

**California.** If you live in California, you can ask Judson Miller to tell you the categories and specific pieces of personal information collected, the sources, the purpose, and who it is disclosed to; to delete personal information, subject to the locked-race totals described above; and to correct inaccurate account information. He will not discriminate against you for asking. Stride League does not sell personal information and does not share it for cross-context behavioral advertising, so there is no separate “Do Not Sell or Share My Personal Information” switch. Email nckoffeeking@gmail.com. He will respond within **45 days**. If he needs more time, he will email you and may take one extra 45 days, as California law allows. He will match the request to the account from the display name and the sign-in method. He will not ask you for a government ID.

**Other US states.** If your state gives you a right to access, correct, or delete personal information (including Colorado, Connecticut, Virginia, Utah, Texas, and Oregon), email the same address. He will not discriminate against you for asking. If a request is denied, reply to that email and ask him to review the decision.

Stride League is operated from the United States. Information is stored in the United States. If you use the app from another country, your information is processed in the United States.

## Changes

If this policy changes, the new version is posted at [this same address](https://koffeekinggamer.github.io/stride-league-legal/privacy/) with a new effective date. If a change materially affects step data or who it is shared with, Judson Miller will tell you in the app before that date and will ask you to agree in the app before using step data in the new way. If he has your email, he may email you as well. The copy at that address is the one that applies.

## Contact

Judson Miller  
106 E Rutherford St  
Landrum, SC 29356  
United States  
nckoffeeking@gmail.com  
(828) 817-6981

The [Terms of Use](https://koffeekinggamer.github.io/stride-league-legal/terms/) are a separate document. They are governed by the laws of the State of South Carolina, USA.
