---
title: "Outlook PST Import No Emails: Diagnose Before You Recover"
description: "Import wizard finished but the PST shows no emails? Run these targeted checks to confirm where the messages went and recover the import safely."
seo_title: "Outlook PST Import No Emails: Fix the Empty Mailbox"
seo_description: "Import wizard finished but the PST shows no emails? Run these targeted checks to confirm where the messages went and recover the import safely."
keywords:
  - "outlook pst import no emails"
date: 2026-11-25T08:03:28+08:00
publishDate: 2026-11-25T08:03:28+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You finished the import wizard, but the target mailbox shows no imported mail, and you need to know whether the messages are missing or simply filed elsewhere.

## Confirm the import target and view

Open the destination mailbox, not the source archive. In the folder pane, check whether a new subfolder was created under the inbox or under a folder named after the PST. If you see that folder, expand it and compare its item count with the source PST. A populated subfolder means the import worked but landed in an unexpected location. If the folder is empty, continue.

## Check the import log and file state

In Outlook, go to File > Open & Export > Import/Export and repeat the wizard only to the point where it lists the source file. Cancel before finishing. Confirm the selected PST path and that the file is not marked read-only in Windows Explorer. A read-only PST can complete the wizard while importing nothing. Also verify the PST is not password-protected; a locked file may import zero items without an obvious error.

## Verification test

Create a test folder in the destination mailbox, import a single known subfolder from the PST into it, and count the items. If the test folder receives mail, the original import target was wrong. If it stays empty, the PST content is not being read and needs repair before another import. This is the point where **outlook pst import no emails** becomes a file-integrity question rather than a wizard question.

## Rollback and recovery

Before retrying, export the current destination mailbox to a backup PST so you can undo duplicate imports. If the test import also fails, run Scanpst.exe on a copy of the source PST, then import from the repaired copy. Keep the original untouched until the messages appear. For a guided diagnosis,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
