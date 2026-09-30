# Privacy Policy

**Receiptly.ai**
Last updated: 1 October 2026

---

## The short version

- **Without an account**, everything stays on your iPhone. Nothing is sent
  anywhere.
- **With an account**, your receipts — and, unless you turn it off, their
  photos — are backed up to your private Receiptly account so they come back
  on a new iPhone, and you can share the ones you choose with your family.
- Receipts are **read on your iPhone**. The one exception is *cloud reading*,
  which you switch on separately; it sends a photo to be read and keeps
  nothing.
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
- Everything else in this section — where photos are kept, how they are
  protected, and how to delete them — is described below.

### 21 September 2026 — first version

---

## Using Receiptly without an account

You can use every part of Receiptly that works on one iPhone — scanning,
reading, search, insights and export — without signing in. In that case:

- Receipt details are held in an encrypted database on your iPhone, and
  receipt photos in the app's private storage, readable only while your
  iPhone is unlocked. Neither is included in an iCloud or computer backup.
- Nothing about your receipts is sent to us or anyone else.
- Deleting the app deletes all of it.

## If you sign in

You can sign in with Google or with an email address and password (and, where
available, with Apple). Sign-in is handled by Google Firebase Authentication.
We receive a unique account identifier and, from the provider, your name,
email address and profile picture, which are used only to show who you are
to the family members you choose to share with.

### What is backed up to your account

- **Receipt details** — shop, date, total, tax, currency, receipt number,
  items, prices, quantities, categories, product and store codes, and the
  receipt's own barcode.
- **Your corrections**, so reading keeps improving for your account.
- **Receipt photos**, if photo backup is on (see "What's changed"). A photo
  is reduced to at most 2000 pixels on its longest side before it is sent,
  and location and camera details are removed.

### Where it is kept, and how it is protected

Your account data is kept on Google Cloud in the United States (Cloud SQL
for receipt details, Cloud Storage for photos), in a private area that only
your account can reach. It is encrypted in transit and in storage. A photo
can only be fetched through a signed link that expires after five minutes.
This is not end-to-end encryption: our server can read your receipt details
in order to back them up, search them and restore them to you.

### What it is used for

Only to back up, restore and search your own receipts, and — for receipts
you share — to show them to your family. Receipt details and photos are not
read by people, not analysed for any other purpose, not sold, not used for
advertising, and not used to train any model.

### Sharing with your family

If you create or join a family, you can share individual receipts with it
(or choose to share everything). Family members see the receipts you share —
including the photo — and your name as the person who added them. They
cannot change your receipts. Receipts you do not share stay private to you.
You can stop sharing a receipt at any time.

### Gmail import (optional)

If you connect Gmail, Receiptly asks Google for **read-only** access to your
email. Emails are fetched to your iPhone and read there; only the receipts
you keep are backed up to your account, like any other receipt. Email
content is never sent to our server. You can disconnect Gmail at any time in
Settings, and you can also remove Receiptly's access in your Google Account.

### Cloud reading (optional)

If you turn on cloud reading, after its own consent screen, a receipt that
is hard to read on the iPhone can be sent to be read by a model (Qwen3-VL)
hosted by DeepInfra in the United States. One reduced, metadata-free photo
and the text the iPhone already read are sent; DeepInfra keeps nothing and
does not train on it, and our server stores neither — only a count of how
many receipts were read. Your iPhone's own reading is always used if cloud
reading is unavailable.

## Permissions the app asks for

**Camera** — to photograph receipts. **Photo library** — iOS shows a picker
and gives the app only the images you choose. **Face ID / Touch ID** —
optional app lock; iOS tells the app only whether the check succeeded.

## What the app does not do

- No analytics, crash-reporting, advertising or tracking SDKs.
- No advertising identifier, and no tracking across other apps or websites.
- No selling or sharing of personal information.

## Deleting your data

- **A receipt:** deleting it in the app deletes it from your account too,
  including its backed-up photo.
- **Backed-up photos:** turning photo backup off lets you delete all of
  them. Photos of receipts you share with your family stay, so they can
  still see them, until you stop sharing those receipts.
- **Your account:** Settings → Cloud Sync → "Delete account and all data"
  deletes your account, every receipt and every photo from our servers.
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
anything else, contact us below. We do not sell personal information.

## Changes to this policy

When Receiptly adds something that changes what is sent or kept, this page
is updated before that version is released, the change is described under
"What's changed" with its date, and the app tells you what changed and gives
you the choice before anything new of yours is sent.

## Contact

Questions about this policy, or about how the app handles your data:

**parthasarathy.ramaraj@gmail.com**

---

*Receiptly.ai is made by Parthasarathy Ramaraj.*
