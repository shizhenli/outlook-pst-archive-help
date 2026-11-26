---
title: "Outlook PST Repair Scanpst Errors: When the Archive Won't Open"
description: "Troubleshoot classic Outlook when a local PST archive won't open and scanpst reports errors. Follow targeted checks, interpret results, and verify recovery safely."
seo_title: "Fix Outlook PST Repair Scanpst Errors: Archive Won't Open"
seo_description: "Troubleshoot classic Outlook when a local PST archive won't open and scanpst reports errors. Follow targeted checks, interpret results, and verify recovery safely."
keywords:
  - "outlook pst repair scanpst errors"
date: 2026-11-26T08:02:38+08:00
publishDate: 2026-11-26T08:02:38+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

## Troubleshooting

You try to open your local archive PST in classic Outlook, and it refuses, saying the file is corrupt or cannot be opened. Before you run any repair, do a controlled diagnosis so you know whether the file is truly damaged or just locked. First, close Outlook completely and check Task Manager for lingering outlook.exe processes; end them if present. Then locate the PST, right-click it, choose Properties, and confirm it is not marked read-only. Next, verify the file is on a local drive, not a network share or synced cloud folder that can lock it mid-access. Try opening it again via File > Open & Export > Open Outlook Data File. If Outlook still reports corruption, run scanpst.exe against a copy, not the original. The exact result matters: if scanpst finds errors and offers repair, let it finish and note the log path; if it says no errors but Outlook still fails, the problem is likely profile or permission related, not file corruption. For persistent **outlook pst repair scanpst errors**, keep the original untouched and work only on the copy. As a verification test, after repair, reopen the copy in Outlook and confirm the folder tree and a known recent message are visible; if they are, the archive is readable. Rollback note: if repair reduces folders or messages, discard the repaired copy and restore your pre-repair backup before trying another method. If the original still won't open after these checks, stop repeating scanpst and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) with the exact error text and log path.
