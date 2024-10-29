---
show: true
width: 6
date: 2023-10-15 00:01:00 +0800
height: 295px
images:
- src: https://picsum.photos/seed/first1111/800/800
  title: Shangri-la, Yunnan, China
  desc: May 20, 2023
- src: https://picsum.photos/seed/second22/800/800
  title: Photo 2
  desc: Description 2
- src: https://picsum.photos/seed/third33/800/800
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
