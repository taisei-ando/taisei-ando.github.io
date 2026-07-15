---
title: "CubeDVO: Cubemap-Spherical Deep Visual Odometry for a Monocular 360-Degree Camera"
date: 2026-06-01
layout: paper
toc: false
reading_time: false
show_reading_time: false
summary: "単眼360度カメラ向け視覚オドメトリ CubeDVO の著者最終稿 PDF と書誌情報。"
authors:
  - Taisei Ando
  - Junwoon Lee
  - Takuya Igaue
  - Kohtaro Nakamura
  - Mitsuru Shinozaki
  - Toshihiro Kitajima
  - Qi An
  - Atsushi Yamashita
display_authors:
  - Taisei Ando
  - Junwoon Lee
  - et al.
publication: "IEEE Robotics and Automation Letters, Vol. 11, No. 8, pp. 9543-9550, 2026."
hugoblox:
  ids:
    doi: "10.1109/LRA.2026.3706936"
pdf: "https://www.robot.t.u-tokyo.ac.jp/~yamashita/paper/A/A229Final.pdf"
---

<div class="cubedvo-page-marker"></div>

**Links:** [PDF](https://www.robot.t.u-tokyo.ac.jp/~yamashita/paper/A/A229Final.pdf) / [BibTeX](/bib/cubedvo/)

## Abstract

This paper proposes CubeDVO, a learning-based visual odometry system specifically designed for a monocular 360-degree camera. While recent methods apply spherical convolutions to equirectangular images, their core operations still rely on the distorted 2D domain, which inherently degrades tracking accuracy. To address this limitation, our method introduces a unified cubemap-spherical representation that decouples the pose estimation pipeline from the equirectangular image space. We extract features on cubemap planes to reduce projection-induced distortion while enabling standard 2D convolutions, and perform geometric optimization on the unit sphere for consistent pose estimation. Our architecture incorporates a geometry-aware flow estimation network and a differentiable spherical bundle adjustment module. CubeDVO is evaluated against state-of-the-art spherical and conventional perspective visual odometry methods. Experimental results demonstrate that our method achieves robust performance under aggressive motion while maintaining high accuracy and practical computational efficiency.

## Keywords

visual odometry, omnidirectional vision, spherical geometry, deep learning
