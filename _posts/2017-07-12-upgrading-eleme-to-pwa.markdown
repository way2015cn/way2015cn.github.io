---
layout:       post
title:        "Dualsprache test"
subtitle:     "Double language"
date:         2017-07-12 12:00:00
author:       "lao Wang"
header-img:   "img/in-post/post-eleme-pwa/eleme-at-io.jpg"
header-mask:  0.3
catalog:      true
multilingual: true
tags:
    - test
    - Equipment
---

<!-- English Version -->
<div class="en post-container">
    {% capture about_en %}{% include posts/2017-07-12-upgrading-eleme-to-pwa/en.md %}{% endcapture %}
    {{ about_en | markdownify }}
</div>

<!-- Chinese Version -->
<div class="de post-container">
    {% capture about_de %}{% include posts/2017-07-12-upgrading-eleme-to-pwa/de.md %}{% endcapture %}
    {{ about_de | markdownify }}
</div>
