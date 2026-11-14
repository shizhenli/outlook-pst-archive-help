---
title: "Outlook PST Import Shows No Emails: A Targeted Fix"
description: "Import wizard finished but the target mailbox is empty? Follow these targeted checks to diagnose why Outlook PST import shows no emails and restore the expected result."
seo_title: "Outlook PST Import No Emails: Diagnose the Empty Import"
seo_description: "Import wizard finished but the target mailbox is empty? Follow these targeted checks to diagnose why Outlook PST import shows no emails and restore the expected result."
keywords:
  - "outlook pst import no emails"
date: 2026-11-14T19:29:30+08:00
publishDate: 2026-11-14T19:29:30+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You completed the import wizard into your classic Outlook profile, but the destination mailbox shows no imported mail, leaving you stuck before any controlled diagnosis.

## Confirm the import target and view

First, verify where the wizard actually placed the data. Open File > Open & Export > Import/Export and repeat the wizard only far enough to read the selected destination folder, then cancel. If it points to a subfolder rather than the mailbox root, expand that folder in the navigation pane. A common cause of **outlook pst import no emails** is simply that the messages landed in a nested folder you have not expanded.

## Check the source PST before blaming the import

Open the original PST directly with File > Open & Export > Open Outlook Data File. If the source file also shows no messages, the archive is empty or damaged, and the import had nothing to copy. If the source displays mail normally, the file is intact and the issue lies in the destination or view.

## Rule out filters and views

Switch the destination folder to View > Change View > Messages, then clear any active filter with View > View Settings > Filter > Clear All. Check the folder's item count in the status bar; a non-zero count with a blank list confirms a view problem, not data loss.

## Verification test

Send yourself a test message, confirm it appears in the destination folder, then re-import a single known subfolder. If the test message and that subfolder both appear, the mailbox is functioning and the earlier result was a view or target issue.

## Rollback and recovery

Before retrying, export the current destination folder to a backup PST so no existing mail is overwritten. If the source PST proves damaged, stop importing and repair it first. For a guided diagnosis of your specific file,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
