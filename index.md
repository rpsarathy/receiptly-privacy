# Privacy Policy

**Receiptly.ai** (shown on your iPhone as "Receiptly")
Last updated: 1 October 2026

---

## The short version

- **If you don't sign in:** your receipts and photos stay on your iPhone and
  are never sent to us.
- **If you sign in:** your receipts — and their photos, unless you turn that
  off — are backed up to your private account on Google Cloud, so they come
  back on a new iPhone, and you can share the ones you choose with your
  family.
- Receipts are read on your iPhone. If you turn on *cloud reading*, each
  receipt you scan is also sent to be read in the cloud (details below).
- No analytics, no advertising, no tracking, and nothing is sold. Your
  receipts and photos are never used to train any model.

---

## What's changed

### 1 October 2026 — receipt photos can be backed up

**Before:** with an account, your receipt *details* were backed up, and the
*photo* of each receipt stayed on the iPhone it was taken on unless you
shared that receipt with your family.

**Now:** with an account, the photo of each receipt is backed up to your
private account too, so it comes back if you change or lose your iPhone.

- **It is your choice.** Photo backup is on by default when you sign in, and
  the sign-in screen has a switch to turn it off before anything is sent. If
  you were already signed in, the app asks you once — "Back up photos" or
  "Keep photos on this iPhone" — and nothing of yours is uploaded until you
  answer. You can change it at any time in Settings → Cloud Sync → Photos.
- Photos of receipts imported from Gmail are not backed up.
- Where photos are kept, how they are protected and how to delete them are
  described below.

### 21 September 2026 — first version

---

## Using Receiptly without signing in

Scanning, reading, search, insights and export all work without an account.
In that case:

- Receipt details are kept in an encrypted database on your iPhone, and
  receipt photos in the app's private storage, protected by your iPhone's
  passcode. Neither is included in an iCloud or computer backup.
- Receiptly sends nothing about your receipts to us or to anyone else.
- Deleting the app deletes all of it.

## If you sign in

You can sign in with Apple, with Google, or with an email address and
password. Sign-in is handled by Google Firebase Authentication. If you sign
in with Apple and choose "Hide My Email", we receive only Apple's relay
address, never your real one. Deleting your account also revokes
Receiptly's access to your Apple ID.

### Your account

We keep a unique account ID, your email address, the name and profile
picture your sign-in provider gives us, which sign-in method you used, and
when you last signed in. You can edit your name and add an optional phone
number. Your email address and phone number are used only for your account
and are never shown to anyone else. Family members see your name and
profile picture.

### What is backed up to your account

- **Receipt details** — shop, date, total, subtotal, tax, currency, receipt
  number, items, prices, quantities, categories, product and store codes,
  the text of each item line as it was read, and where the receipt came
  from (camera, photo library or Gmail). The receipt's own barcode stays on
  your iPhone.
- **Your edits** — the details as you corrected them, and a note that you
  edited them, so another device does not overwrite your change.
- **Receipt photos**, if photo backup is on (see "What's changed"). A photo
  is reduced to at most 2000 pixels on its longest side before it is sent,
  and location and camera details are removed.

### Search

When you search while signed in, what you type is sent to our server to
find matching receipts in your account. It is used only to answer that
search and is not kept.

### Where it is kept, and how it is protected

Your account data is kept by Google Cloud in the United States (Cloud SQL
for receipt details, Cloud Storage for photos), private to your account —
and, for receipts you share, to your family. It is encrypted in transit and
in storage. A photo can only be fetched through a signed link that expires
after five minutes. This is not end-to-end encryption: our server can read
your receipt details in order to back them up, search them and restore them
to you.

### What it is used for

Only to back up, restore and search your own receipts, and — for receipts
you share — to show them to your family. We do not look at your receipts
unless you ask us to help with a problem. Receipt details and photos are not
sold, not used for advertising, and not used to train any model.

### Sharing with your family

If you create or join a family, you can share individual receipts with it.
With "Share everything", new receipts are shared automatically, except those
imported from Gmail. Family members see the receipts you share — including
the photo — with your name and profile picture. They cannot change your
receipts. Receipts you do not share stay private to you. You can stop
sharing a receipt at any time.

### Gmail import (optional)

If you connect Gmail, Receiptly asks Google for **read-only** access to your
email (`gmail.readonly`). It cannot send, delete, change or mark your emails
as read.

- **What it reads:** it looks at senders and subjects to find likely
  receipts, and opens only those messages and their receipt attachments.
  Promotions, newsletters, delivery updates and personal mail are skipped.
  Links and images inside emails are never loaded.
- **Where it is read:** on your iPhone. Emails are never sent to our server
  or to anyone else, and are never sent for cloud reading.
- **What is kept:** the receipts it finds — the same receipt details as for
  a scanned receipt (shop, date, amounts, items) — are saved in Receiptly
  and backed up to your account. Receipts it is unsure about wait for you to
  check. To avoid reading the same email twice, your iPhone keeps a record
  of which messages it has checked (message ID, sender's domain and date);
  this record stays on your iPhone. Email subjects, senders and message
  contents are not sent to our server, and pictures from emails are not
  backed up.
- **Not shared:** receipts imported from Gmail are never shared with your
  family automatically, even with "Share everything" on.
- **Stopping:** disconnect Gmail at any time in Settings → Gmail, and choose
  whether imported receipts stay or are deleted. You can also remove
  Receiptly's access at
  [myaccount.google.com/permissions](https://myaccount.google.com/permissions).

#### Google API Services: Limited Use

Receiptly's use and transfer of information received from Google APIs to
any other app will adhere to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements. In particular, data from your Gmail:

- is used only to find and import your receipts, a feature you can see and
  control in the app;
- is not used for advertising, and is not sold;
- is not used to develop, improve or train any AI or machine-learning
  model;
- is not transferred to anyone else, except as needed to provide the
  feature (backing up the receipts you import to your own account), to
  comply with the law, or with your consent (sharing a receipt with your
  family);
- is not read by any person, unless you ask us to help with a problem and
  agree to it, it is needed for security, or the law requires it.

### Cloud reading (optional)

Cloud reading is off until you turn it on, after its own consent screen.
While it is on, each receipt you scan is also sent to be read by a model
(Qwen3-VL) hosted by DeepInfra in the United States. We send one reduced
photo, with location and camera details removed, and the text your iPhone
already read. DeepInfra does not keep it or train on it. Our server does not
store the photo or the text; it keeps the reading it returned for up to
about a day, so that a retried request is not read twice, and a daily count
of how many receipts you had read. Your iPhone's own reading is always used
if cloud reading is unavailable.

## Service providers

- **Google Cloud** (Cloud Run, Cloud SQL, Cloud Storage; United States) —
  runs our server and stores your account data.
- **Google Firebase Authentication**, **Sign in with Apple** and **Google
  Sign-In** — sign-in.
- **Gmail API** (Google) — only if you connect Gmail, and only from your
  iPhone.
- **DeepInfra** (United States) — only if you turn on cloud reading.

Your data is processed in the United States.

## Server logs

When the app talks to our server, Google Cloud records technical request
information — such as your IP address, the time, and which part of the
service was used — to keep the service running and secure. Our own logs
leave out receipt contents, email addresses and sign-in tokens. Logs are
kept for up to 30 days.

## Permissions the app asks for

**Camera** — to photograph receipts. **Photo library** — iOS shows a picker
and gives the app only the images you choose. **Face ID / Touch ID** —
optional app lock; iOS tells the app only whether the check succeeded.

## What the app does not do

- No analytics, crash-reporting, advertising or tracking SDKs.
- No advertising identifier, and no tracking across other apps or websites.
- No selling or sharing of personal information.

## How long data is kept, and deleting it

Account data is kept until you delete it or delete your account.

- **A receipt:** deleting it in the app deletes it from your account too,
  including its backed-up photo.
- **Backed-up photos:** turning photo backup off lets you delete all of
  them. Photos of receipts you share with your family stay, so they can
  still see them, until you stop sharing those receipts.
- **Your account:** Settings → Cloud Sync → "Delete account and all data"
  deletes your account, receipts, photos and profile from our servers, and
  the receipts on this iPhone. Copies in our encrypted database backups are
  overwritten within 7 days, and server logs within 30 days.
- **Without the app:** email us from the address you signed in with and we
  will delete your account and data within 30 days.
- **Signing out** never deletes anything; your backup is there when you sign
  in again.

## Children

Receiptly.ai is not directed at children and is not intended for children
under 13.

## Your rights

Depending on where you live, laws such as the GDPR and the CCPA give you the
right to see, correct, delete or export personal information held about you,
and to ask that it not be sold. You can edit and delete receipts in the app,
export them as CSV or PDF, and delete your account from Settings. For
anything else, email us and we will reply within 30 days. We do not sell
personal information.

## Changes to this policy

When Receiptly adds something that changes what is sent or kept, this page
is updated before that version is released, the change is described under
"What's changed" with its date, and the app tells you what changed and gives
you the choice before anything new of yours is sent.

## Contact

Questions about this policy, or requests about your data:

**parthasarathy.ramaraj@gmail.com**

---

*Receiptly.ai is made by Parthasarathy Ramaraj.*
