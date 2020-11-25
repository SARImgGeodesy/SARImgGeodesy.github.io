---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

**Space imaging geodesy reveals near circular, coseismic block rotation during the 2016 Mw 7.8 Kaikōura earthquake, New Zealand**  
**空间影像大地测量在2016年新西兰凯库拉地震中揭示的近圆形同震块体旋转**  

Large earthquakes usually rupture plate boundary faults, releasing the accumulated stress as displacements localized along smooth, narrow faults. However, certain earthquakes initiate off main faults, rupturing adjacent, secondary faults. The mechanisms of such atypical stress release remain enigmatic, partly due to a lack of detailed geodetic evidence. Here using the 3D coseismic displacement field derived from space imaging geodesy, we detect 10‐km‐scale, nearly‐circular coseismic block rotation during the 2016 Mw 7.8 Kaikōura earthquake in New Zealand. Together, geodetic observations, longer term local paleomagnetic data, analytical, and discrete element modeling imply that localized block rotation occurred south of the Hope fault along weak, steep, bedding‐parallel boundaries within a narrow, ~20‐km‐wide dextral shear zone. That stress near plate boundary faults can be partially released in zones of distributed ruptures absorbing coseismic rotation may retard rupture along main faults. Our observations also suggest that coseismic rotation may help accomodate plate boundary propagation.

大地震通常会通过在板块边界断层发生破裂，将累积的应力以局部位移和应变的形式，沿平滑、狭窄的断层释放出来。然而，某些地震从主断层外开始成核，只破裂相邻的次级断层。这种非典型的应力释放的机制仍然是个谜，部分原因是缺乏详细的大地测量证据。这里，利用空间影像大地测量获得的三维同震形变场，我们在2016年新西兰Mw7.8凯库拉地震中发现了十公里尺度、近圆形的块体旋转。大地测量观测、古地磁数据和有限离散元模型共同揭示：在一个约20公里宽的狭窄右旋剪切带内，沿着弱的、陡峭的、层理面平行的边界，在Hope断层南部发生了局部的块体旋转。沿板块边界断层积累的应力可以在吸收同震旋转的分布式断裂区中部分释放，可能延缓了主断层的断裂。我们的观测结果还表明，同震块体旋转可能有助于调整板块边界传播。

----------
# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
