---
title: "Outlook PST Corrupt File Error: Diagnose Before Reopening Your Archive"
description: "When Outlook reports your archive PST is corrupt and won't open, follow these controlled checks to confirm the fault before attempting repair or replacement."
seo_title: "Outlook PST Corrupt File Error: Safe Diagnosis Steps"
seo_description: "When Outlook reports your archive PST is corrupt and won't open, follow these controlled checks to confirm the fault before attempting repair or replacement."
keywords:
  - "outlook pst corrupt file error"
date: 2026-11-24T10:03:24+08:00
publishDate: 2026-11-24T10:03:24+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You try to open your local archive PST in classic Outlook, and it refuses with a message that the file cannot be opened or is corrupt.

## Confirm the exact error and file state

Close Outlook completely. Navigate to the PST file in File Explorer, right-click it, and choose Properties. Confirm the file size is not 0 KB and that the read-only attribute is cleared. A 0 KB file usually means the archive was never properly closed; a read-only flag can block access without any corruption. If either is wrong, correct it and retry opening the archive once.

## Run the Inbox Repair Tool in scan-only mode

Locate scanpst.exe (typically under Program Files\Microsoft Office\root\Office16). Run it, browse to your PST, and click Start. Let the first pass finish. If it reports errors, do not immediately apply the repair. Instead, copy the PST to a safe folder first, then run the repair on the copy. This preserves your original in case the repair worsens the **outlook pst corrupt file error**. After repair, reopen Outlook and attempt to open the archive.

## Verification test

Create a new Outlook profile and add the repaired PST as a data file. If the archive opens and folders display, the original profile was the issue. If the same error appears, the PST itself remains damaged.

## Rollback and next step

Keep the untouched original PST until you confirm the repaired copy opens reliably. If both copies fail, stop repeated repair attempts and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before further changes.
