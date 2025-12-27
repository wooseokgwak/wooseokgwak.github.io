---
layout: page
title: KV Streaming
description: Fast Long-Context LLM Serving via Streaming Layerwise-Compressed KV Cache
img: 
importance: 1
category: work
related_publications: false
---

The summary of the project is as follows.

- Led a project to overlap model inference, KV cache streaming, and decoding in a layerwise manner to reduce TTFT.
- Developed a layerwise inference engine, encoding and decoding tools, and a streaming server for pipelined execution.
- Achieved a 5–15% reduction in TTFT compared to the non-overlapped baseline.

<div style="text-align: center;">
  <!-- Paste your Google Slides iframe code here -->
  <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRN_uVVEE2gl7YDjCaQDy9nzPMNLMIGZQtddMVgSPp2bO-41SQSEWR3qtH5ptyBidBpSGXZdayAP-eK/pubembed?start=false&loop=false&delayms=3000" frameborder="0" width="640" height="389" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>


