---
title: "Outlook PST File Too Large: Diagnose Before You Move or Open"
description: "Classic Outlook refuses to open or move a PST archive because it exceeds the size limit. Follow these checks to diagnose the file safely and restore access."
seo_title: "Outlook PST File Too Large: Fix Opening or Moving Errors"
seo_description: "Classic Outlook refuses to open or move a PST archive because it exceeds the size limit. Follow these checks to diagnose the file safely and restore access."
keywords:
  - "outlook pst file too large"
date: 2026-11-21T15:14:26+08:00
publishDate: 2026-11-21T15:14:26+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

## Troubleshooting

You are in classic Outlook with a local PST archive, and Outlook or the filesystem refuses to open or move the file because it has exceeded a size limit. First, confirm the actual size and format without opening the file in Outlook. In File Explorer, right-click the PST, choose Properties, and note the size in GB. A Unicode-format PST has a 50 GB default limit; ANSI-format PSTs cap at 2 GB. If the file is at or above the relevant ceiling, treat it as oversized. Next, check whether Outlook is still running in the background: open Task Manager, look for outlook.exe, and end it only if you have saved your work. Then try to copy the PST to a local drive with at least twice its size free. If the copy fails with a file-too-large or disk-full message, the destination filesystem is the blocker, not Outlook. If the copy succeeds, the original location is the problem. Run a verification test: create a new empty PST in Outlook via File > New > Outlook Data File, then close and reopen Outlook. If the new file opens normally, your profile is healthy and the issue is isolated to the oversized archive. For recovery, keep the original PST untouched and work on a copy; if a move fails midway, delete the partial copy and retry after freeing space. Do not run repair tools on the only copy. If the file is confirmed **outlook pst file too large** and you need a safe path forward,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
