---
title: "Outlook PST Repair Tool: Diagnose 'Archive Cannot Be Opened' Before You Repair"
description: "When Outlook reports your archive PST cannot be opened or is corrupt, run these targeted checks before using any outlook pst repair tool. Restore access safely."
seo_title: "Outlook PST Repair Tool: Fix Archive Cannot Be Opened"
seo_description: "When Outlook reports your archive PST cannot be opened or is corrupt, run these targeted checks before using any outlook pst repair tool. Restore access safely."
keywords:
  - "outlook pst repair tool"
date: 2026-11-24T12:04:55+08:00
publishDate: 2026-11-24T12:04:55+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You double-click your archive PST in classic Outlook, and it refuses to open with a corrupt-file message. Before you reach for any repair utility, complete this controlled diagnosis so you know whether the file is truly damaged or simply locked.

## Confirm the file is not already open or locked

Close Outlook completely. Open Task Manager and end any lingering OUTLOOK.EXE process. Then try opening the PST again. If it opens now, the earlier error was a lock conflict, not corruption. If the same error returns, proceed.

## Check the file's location and attributes

Right-click the PST, choose Properties, and confirm it is not marked read-only. Also verify the path contains no special characters and that the drive has free space. A read-only or disconnected file often triggers the same cannot-be-opened message.

## Run the built-in Inbox Repair Tool in scan-only mode

Locate scanpst.exe (typically under Program Files\Microsoft Office\root\Office16). Run it, browse to your PST, and click Start. When it finishes, read the log: if it reports minor inconsistencies and offers repair, let it repair. If it reports the file is not a personal folders file or cannot be read, stop and do not overwrite the original. This is where a dedicated **outlook pst repair tool** becomes appropriate, but only after you have copied the PST to a safe location.

## Verification test

After any repair, reopen Outlook, expand the archive, and open three random folders plus one calendar item. If all open without error, the archive is usable.

## Rollback note

Keep the pre-repair copy until you have verified the archive. If repair worsens things, restore that copy and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before trying again.
