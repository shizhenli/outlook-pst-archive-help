---
title: "Imported PST Shows No Messages: Verify the Import Target Before Re-Importing"
description: "Import wizard finished but no mail appears? Check the import target, view filters, and archive scope to fix an Outlook PST import that shows no messages."
seo_title: "Outlook PST Import Shows No Messages: Targeted Fix"
seo_description: "Import wizard finished but no mail appears? Check the import target, view filters, and archive scope to fix an Outlook PST import that shows no messages."
keywords:
  - "outlook pst import shows no messages"
date: 2026-11-26T10:02:34+08:00
publishDate: 2026-11-26T10:02:34+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You ran the import wizard on your local PST archive, it reported success, yet the target mailbox shows no imported mail.

## Confirm where the wizard actually delivered the data

Open the import wizard result summary and note the destination it names. In classic Outlook, importing into an existing mailbox can place items under the mailbox root or into a subfolder rather than the Inbox. Expand every top-level folder under the target account and look for a folder matching the PST name or an "Imported" style label. If the summary names a different mailbox or profile than the one you are viewing, the import succeeded elsewhere; close Outlook, reopen the correct profile, and recheck before doing anything else.

## Check the view and filter state

Switch the message list to an unfiltered view: View tab, Reset View, then confirm Filter Email is off and the reading pane is not hiding items. A filtered or grouped view can make a populated folder look empty, which is a common reason **outlook pst import shows no messages** even when the copy worked.

## Verify the PST content and import scope

Open the source PST directly with File, Open, Outlook Data File and count messages in the folders you expected. If the source folders are empty, the problem predates the import. If they are populated, rerun the wizard and select the specific folders rather than the whole file, watching the item count on the confirmation screen.

## Verification test

Send yourself a test message, then import a single small folder from the same PST. Confirm the test message and the imported items appear in the same view. If the test folder appears but the original did not, the earlier import targeted a different location.

## Rollback note

Before retrying, export the current target folder to a new PST so any partial import can be removed without losing existing mail. If results stay inconsistent,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
