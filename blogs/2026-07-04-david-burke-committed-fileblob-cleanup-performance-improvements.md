---
title: "David Burke committed FileBlob cleanup performance improvements"
url: "https://gitlab.com/glitchtip/glitchtip-backend/-/commit/656d22d98fd33938989ee5bb4d549f20a16ac776"
date: "2026-07-04"
author: "David Burke"
feed_url: "https://gitlab.com/glitchtip.atom"
---
David Burke committed changes to GlitchTip Backend that streamline FileBlob deletion, removing redundant database updates and counting only FileBlob rows against the MAX_DELETIONS_PER_RUN limit.
