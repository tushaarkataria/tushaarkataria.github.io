---
title: "Anchored Slice Propagation with Boundary Transport for 3D CT Segmentation from Three Orthogonal Annotated Slices"
collection: publications
permalink: /publication/2026-11-03-AnchoredSlicePropagation
excerpt: "ABSTRACT PENDING (summary below is a stand-in, not the verbatim arXiv abstract). Three orthogonal annotations reduce dependence on any one propagation chain, yet they offer more than three starting masks: each annotated plane is also a checkpoint that the other two chains cross. Building on Sli2Vol-style label-free mask propagation, we anchor every chain by correcting it where it intersects another annotated plane, and we fuse chains by weighting each one according to its agreement with those labels. We additionally compare signed-distance-field transport against a learned contour tracker as the boundary-propagation mechanism. On 2,091 held-out structure instances drawn from roughly 403 CT scans spanning 17 abdominal structures, anchored propagation raises mean Dice from 0.737 to 0.769 over the unanchored three-seed baseline."
date: 2026-11-03
venue: "arXiv preprint arXiv:2611.05693"
archive: https://arxiv.org/abs/2611.05693
code: https://github.com/tushaarkataria/AnchoredSlicePropagation
citation: "Tushar Kataria, Md Rakibul Haque, Shireen Y. Elhabian. \"Anchored Slice Propagation with Boundary Transport for 3D CT Segmentation from Three Orthogonal Annotated Slices.\" arXiv preprint arXiv:2611.05693 (2026)."
---
