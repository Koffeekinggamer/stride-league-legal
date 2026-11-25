---
layout: app
title: Privacy policy
app_name: Walkie
app_base: /walkie
accent: "#B4232C"
icon: /assets/walkie-icon.svg
permalink: /walkie/privacy/
---

# Privacy policy

**Walkie**

**Effective date: [set at publish]**

Walkie is an iPhone app for voice clips and text with a small circle of people. This policy says what the app collects, why, who handles it, how long it is kept, and how to delete an account.

Questions go to [nckoffeeking@gmail.com](mailto:nckoffeeking@gmail.com).

## What is encrypted

Texts, voice clips, and group names are end-to-end encrypted. Walkie uses Messaging Layer Security (MLS), the standard in RFC 9420, through the OpenMLS library. The server stores that data encrypted. It does not have the keys, so it cannot read the text, the voice, or the group name.

A voice clip is encrypted on your phone with a key used for that clip only. The key sits inside the encrypted message. The file on the server is the encrypted clip.

The server can still see who is in a conversation, who sent a message, when it was sent, whether it was text or voice, the size of a voice file, read status, and push tokens. Hiding that information is not part of this version.

The person who runs the Supabase project can see that delivery metadata. They cannot read the message text or the voice from the database dashboard.

## On your phone

- Encryption keys and the state of each conversation, in the iPhone Keychain. They stay on this phone. They are not synced to iCloud.
- Your contacts, if you allow access. The app reads email addresses on the phone, hashes them, and then drops the raw addresses. Phone numbers are not used.
- A cache of people who matched, their display names, conversation titles, and recent decrypted messages, so the app can open offline.
- A decrypted voice file only while it is playing. The app deletes that file when playback ends.

## What is sent and stored

The backend is Supabase. It hosts sign-in, the database, file storage, and the functions that ask Apple to deliver notifications.

For your account, Walkie stores:

- The login email from Sign in with Apple or from the email code. Sign in with Apple may give Walkie a private relay address that is unique to this app. That address is the login. Friends do not have it in their contacts.
- If you let friends find you, a hash of one email address. The server stores the hash, not the address. You can see your own address in settings. Other people cannot.
- Your display name and your account id.
- A row for each phone: a device id, the public encryption key, and push tokens.
- Key packages, which other phones use when they add your phone to an encrypted conversation.

For conversations, Walkie stores:

- Who is a member, their role, and when they joined or left.
- Encrypted texts, and the encrypted messages used when a phone is added or removed.
- Encrypted voice files and the size of each file.
- When each message was sent, a read cursor for each member, and the encryption epoch.
- Blocks, and the list of people you chose to contact.

Sign in with Apple and the email code are different accounts when the addresses differ. This version does not merge them.

## What is not collected

- Phone numbers. There is no phone number column, and Walkie does not use SMS.
- Your contact list. Raw contacts do not leave the phone. Hashes of people who are not Walkie members are not stored.
- Plaintext messages, group titles, or a search index of them.
- The keys for voice clips, or a preview of a clip made by the server.
- Ads or tracking. Nothing is sold. Nothing is used for advertising. Walkie is not used to track you across other companies' apps and websites.

## How friends find you

Friends find each other by email, not by phone number.

If you allow Contacts, the app reads email addresses on your phone and ignores phone numbers. It hashes each email on the phone and sends the hashes. The server returns the display name and account id of members who verified that email. It does not save the list of hashes. The app keeps the matches and discards the rest. It does not upload names from the contact card.

If you say no to Contacts, Walkie still works. You can share the email friends should use, and they can add it on their phone. Someone who already matched you can also add you to a group.

The hash is SHA-256 of the email, after trimming space and lowercasing it. It is not a secret. Someone who can use matching could test an email address they already thought of. The hash exists so the contact list is not uploaded.

This version uses one discoverable email. Changing it replaces the hash. You can turn discovery off, which deletes the hash. You can still use Walkie, and you can still find other people.

Sign in with Apple does not publish the private relay address for matching. You can add an email your friends have. Walkie sends a code to that inbox and stores the hash only after you enter the code.

## Who can message you

A match does not open a conversation by itself. Someone starts a conversation only after they choose you in the app. A block in either direction stops matching, new conversations, and adds to a group.

This version does not use message requests. You do not accept a request before a message can be sent. If you do not want someone to reach you, block them.

## Microphone

Walkie uses the microphone only while you are talking, to record voice clips for the people you choose.

## Notifications

Notifications go through Apple Push Notification service.

They do not include the text of a message, and they do not include the voice recording.

A voice notification includes the sender's display name, plus ids for the conversation, the sender, and the message. The name is the display name on the profile, so your phone can label who is talking before it decrypts the clip. It is not the message.

A text notification does not include the message. The banner says "New message". An encrypted preview that your phone would decrypt is planned, and it is not sent yet.

Apple sees the notification data the way it sees any app's notifications. Apple is not a member of the encrypted conversation.

## How long data is kept

Text is kept so people who were in the conversation when it was sent can still read it. A new phone does not get keys for older messages, and the server does not give that phone the old rows.

Voice files are not meant to stay forever. No deletion window is set yet, so voice files are not deleted on a schedule. When a window is set, the audio file will be deleted and the message will show that the clip expired. The encrypted message that held the clip key can remain. That key does not open a deleted file, and the file does not open without the key.

## Deleting your account

You can ask for the account to be deleted by email. The steps are on the [delete account page]({{ '/walkie/delete-account/' | relative_url }}).

Deleting an account removes the login, the profile, the discoverable email record, the device rows, and the push tokens, and marks your memberships as left. Encrypted messages you sent stay for the people still in the conversation. Deletion does not remove copies already on other phones.

Signing out does not delete the account.

## Children

Walkie is for a known circle of friends and family. It is not made as a children's app, and it does not have a child account. It does not ask for a date of birth. If you believe a child's information is on an account, email [nckoffeeking@gmail.com](mailto:nckoffeeking@gmail.com).

## Your choices

- Say no to Contacts. Walkie still works.
- Turn discovery off, so friends cannot match your email.
- Turn notifications off in iOS Settings.
- Block someone.
- Sign out.
- Ask for the account to be deleted.

You can email [nckoffeeking@gmail.com](mailto:nckoffeeking@gmail.com) to ask what the account holds, or to ask for a correction.

## Changes

If this policy changes, the new version will be posted at this same address with a new effective date.

## Contact

[nckoffeeking@gmail.com](mailto:nckoffeeking@gmail.com)
