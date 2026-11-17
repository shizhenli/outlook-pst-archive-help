---
title: "Archive PST Will Not Open: Diagnose Before You Repair"
description: "A targeted troubleshooting guide for classic Outlook users whose archive PST will not open, with checks, result interpretation, a verification test, and a rollback note."
seo_title: "Outlook PST Repair Tool: Archive Cannot Be Opened Fix"
seo_description: "A targeted troubleshooting guide for classic Outlook users whose archive PST will not open, with checks, result interpretation, a verification test, and a rollback note."
keywords:
  - "outlook pst repair tool"
date: 2026-11-17T12:03:19+08:00
publishDate: 2026-11-17T12:03:19+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You double-click your archive PST in classic Outlook and get "cannot be opened" or "file is corrupt," and you want to know whether the file is truly damaged before you run any repair.

## Confirm the file is reachable and not locked

Close Outlook completely. Open File Explorer, navigate to the archive PST, right-click it, and choose Properties. Confirm the location and size are readable. If the size shows as zero or the path is on a disconnected network drive, copy the PST to a local folder first. Then reopen Outlook and try File > Open & Export > Open Outlook Data File. If it opens from the local copy, the original path or drive was the problem, not the file.

## Run the built-in scan and read the result

If the local copy still fails, run Scanpst.exe (the inbox repair tool) against it. A clean result means the file structure is intact and the failure is likely a profile or permission issue. A result listing errors means corruption is present, and you should not overwrite the original. Before using any third-party **outlook pst repair tool**, keep a copy of the PST in a separate folder so you can roll back if the repair makes things worse.

## Verification test

After any repair attempt, open the PST in Outlook and check that the folder tree and a sample of messages are present. Then close and reopen Outlook once more to confirm the archive opens consistently.

## If it still will not open

Stop repeating repairs on the same file. Preserve the original and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) with the exact error text and the scan result so the next step is controlled rather than guesswork.
