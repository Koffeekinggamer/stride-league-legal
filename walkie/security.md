---
layout: app
title: Security
app_name: Walkie
app_base: /walkie
accent: "#B4232C"
icon: /assets/walkie-icon.svg
permalink: /walkie/security/
---

# Security

**Walkie**

Walkie encrypts message text, voice clips, and group names on the phones in the conversation. It uses Messaging Layer Security (MLS), the standard in RFC 9420, through the OpenMLS library. It does not use a cipher written for Walkie.

## Where the keys are

Each phone creates its own encryption keys. They are stored in the iPhone Keychain on that phone only, and they are not synced to iCloud. The server does not keep a copy of the private keys.

A new phone does not receive older messages. There is no backup of message history in this version. People you talk to see that your safety number changed. They have to accept the new phone before it can read new messages.

A voice clip has its own key, used once. That key is inside the encrypted message. The stored file is the encrypted audio.

## What the server can see

Supabase stores the encrypted messages and forwards them. It orders them. It is not a member of the conversation, and it does not have the keys to read the text, the voice, or the group name.

It can see who is in a conversation, who sent a message, when, whether the message is text, voice, or a membership change, file sizes, read cursors, push tokens, the login email, the hash of a discoverable email, display names, and public keys.

## Safety numbers

Each contact has a safety number made from the public keys on their phones. Compare it in person, or on a call you already trust, to check you are talking to the right person. When the keys change, the conversation shows a warning until you accept the new number or remove the contact. The server is not that check.

## What this does not do

Encryption does not hide who you talk to or when. It does not remove a message that is already on someone else's phone. It does not protect an unlocked phone. Use a device passcode.

What Walkie collects, and how to delete an account, are in the [privacy policy]({{ '/walkie/privacy/' | relative_url }}).
