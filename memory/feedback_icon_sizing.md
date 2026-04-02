---
name: feedback_icon_sizing
description: For pictogram/icon grid charts, start with larger icons and proper aspect ratios
type: feedback
---

When building pictogram charts with small repeated icons, err on the side of larger icons. 22px was too small; 28px with 5px gap in a 40-col grid worked well for 2000 items.

**Why:** Small icons lose detail and look like dots rather than recognizable shapes. The user had to ask multiple times to increase size.

**How to apply:** For future icon-grid/pictogram charts, start with at least 28px icons. Also ensure SVG viewBox matches the icon's natural aspect ratio to avoid distortion.
