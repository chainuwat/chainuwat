---
layout: entries
title: "Insights"
permalink: /th/insights/
author_profile: true
entries_layout: grid       # <--- บังคับให้แสดงผลแบบตาราง (Grid)
header:
  overlay_color: "#333"
  overlay_filter: 0.6
---

### บทความและมุมมองเชิงกลยุทธ์
ตกผลึกความคิดเรื่องการบริหารจัดการ ระบบ และผู้คน จากประสบการณ์จริงในการวางกลยุทธ์องค์กร

---

{% assign posts = site.categories.Insights %}
<div class="entries-grid">
  {% for post in posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
