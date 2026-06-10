---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '3rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      headings:
        about: 'About'
        education: ''
        interests: ''
    design:
      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'Selected Papers'
      text: |-
        **CubeDVO: Cubemap-Spherical Deep Visual Odometry for a Monocular 360-Degree Camera**  
        Taisei Ando, Junwoon Lee, Takuya Igaue, Kohtaro Nakamura, Mitsuru Shinozaki, Toshihiro Kitajima, Qi An, and Atsushi Yamashita  
        IEEE Robotics and Automation Letters, Vol. 11, 2026. Accepted.

        **Efficient Distortion Mitigation in Equirectangular Images for Two-View Pose Estimation**  
        Taisei Ando, Junwoon Lee, Mitsuru Shinozaki, Toshihiro Kitajima, Qi An, and Atsushi Yamashita  
        International Journal of Automation Technology, Vol. 19, No. 3, pp. 226-236, May 2025.  
        [Paper](https://www.fujipress.jp/ijat/au/ijate001900030226/)
    design:
      columns: '1'
---
