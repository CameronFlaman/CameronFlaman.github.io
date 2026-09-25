---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 295px
group: Cloud Chamber
images:
- src: "{{ 'assets/images/photos/PhotoTracking.png' | relative_url }}"
  desc: CAD Assembly of the "Cooling Stack".
- src: "{{ 'assets/images/photos/FinalCoolerStack.png' | relative_url }}"
  desc: Phototracking algorithm recording tracks left by alpha and beta radiation.
- src: "{{ 'assets/images/photos/3DRender.png' | relative_url }}"
  desc: 3D Rendering of cloud chamber CAD Model.
- src: "{{ 'assets/images/photos/Peltier Diagram.png' | relative_url }}" 
  desc: Schematic for the wiring if the Peltier Cooling modules.
- src: src="{{ 'assets/images/photos/WiringSchematic.png' | relative_url }}"
  desc: Schematic for the wiring of the complete cloud chamber.
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
