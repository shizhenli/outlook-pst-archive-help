---
title: "Archive PST Won't Open: Diagnose the Corrupt File Error Before Repair"
description: "Step-by-step diagnosis for a classic Outlook archive PST that won't open due to a corrupt file error. Check file access, run Scanpst, and verify recovery safely."
seo_title: "Outlook PST Corrupt File Error: Fix 'Archive Cannot Be Opened'"
seo_description: "Step-by-step diagnosis for a classic Outlook archive PST that won't open due to a corrupt file error. Check file access, run Scanpst, and verify recovery safely."
keywords:
  - "outlook pst corrupt file error"
date: 2026-11-21T15:11:10+08:00
publishDate: 2026-11-21T15:11:10+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

## Troubleshooting

You try to open your archive PST in classic Outlook, but it reports the file cannot be opened or is corrupt, and you are stuck before any controlled diagnosis. Start by confirming the file is reachable and not locked. In File Explorer, navigate to the PST location, right-click it, and choose Properties. Confirm the file size is non-zero and that your Windows account has read/write access. If the file is on a network share or removable drive, copy it to a local folder first; Outlook cannot reliably open a PST over a network. Next, close Outlook completely. Open Task Manager and end any lingering outlook.exe process. Then reopen Outlook and try File > Open & Export > Open Outlook Data File. If the same error appears, the file itself is the likely cause. Run the built-in Inbox Repair Tool: search for scanpst.exe, browse to your PST, and start the scan. If it reports errors, allow it to create a backup when prompted, then run the repair. After repair, reopen the PST in Outlook. Verification: create a test folder in the archive, move one message into it, close Outlook, reopen it, and confirm the folder and message persist. If the PST still fails to open, do not overwrite the original; keep the scanpst backup and the original file untouched. This is a classic **outlook pst corrupt file error** that may need deeper recovery. For a guided next step,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).

Repeat the same check after a restart and confirm the result twice.
