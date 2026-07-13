---
title: "David Burke merged periodic orphaned FileBlob cleanup into GlitchTip Backend"
url: "https://gitlab.com/glitchtip/glitchtip-backend/-/merge_requests/2432"
date: "2026-07-04"
author: "David Burke"
feed_url: "https://gitlab.com/glitchtip.atom"
---
David Burke's periodic orphaned FileBlob cleanup was merged into GlitchTip Backend, adding a daily maintenance task that deletes unreferenced blobs older than 24 hours using a reference-based (not age-based) approach so blobs still used for symbolication are never touched.
