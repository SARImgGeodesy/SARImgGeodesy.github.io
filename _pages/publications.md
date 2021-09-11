---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
<b>2021-#3</b>  
<div style="text-align: center;">
<b>Selective Kernel Res-Attention UNet: Deep Learning for Generating Decorrelation Mask with Applications to TanDEM-X Interferograms</b>  
<br><b>基于深度学习生成失相干掩膜及其在TanDEM-X干涉图中的应用</b>  
<br><a href="https://ieeexplore.ieee.org/document/9516966">Zhang, Q., T. Wang, Y. Pei, and X. Shi (2021), Selective Kernel Res-Attention UNet: Deep Learning for Generating Decorrelation Mask with Applications to TanDEM-X Interferograms, IEEE J. Sel. Top. Appl. Earth Obs. Remote Sens., 14, 8537–8551.</a>
</div>
Synthetic aperture radar interferometry (InSAR) is a remote sensing tool that can accurately map terrain and surface deformation with high resolution. Decorrelation is one of the main limitations for InSAR. Masking decorrelated pixels is crucial for retrieving information from SAR interferograms. However, for traditional masking methods, manually drawing masks is time-consuming and may be unfeasible when decorrelation areas are with complicated and blurred boundaries. Setting a single coherence threshold is also difficult, if not impossible, to mask out all decorrelated pixels without losing valid phases. Here, we propose a deep-learning segmentation network (Mask Net) based on Selective Kernel Res-Attention UNet, for generating decorrelation masks with applications to TanDEM-X interferograms. We conduct several experiments to determine the training strategy and parameters, including sample size, batch size, loss function, and down-sampling scheme, to optimize network performance. Afterwards, we compare the performance of Mask Net with other classical segmentation networks. Our evaluation metrics show that Mask Net outperforms the best performance of other segmentation networks by IoU of 6.32% and F1 Score of 3.97%, respectively. It also possesses the fastest inferring speed, 0.4505 s on sample size of 1024-by-1024 pixels, which is at least ∼50% faster than other segmentation networks. We applied Mask Net to three TanDEM-X interferograms of Kīlauea crater in Hawaii, metropolitan region of Wuhan, and Muztagata Glacier in China. Our results show that comparing with coherence threshold method, Mask Net can clearly mask out all decorrelation regions, rarely causing loss of valid phases. It also exhibits better segmentation performance than other deep-learning segmentation networks, especially for those complex decorrelation boundaries, with less computational time. We believe that in the InSAR big data era, such a network can greatly reduce time and labor.

合成孔径雷达干涉测量（InSAR）是一种能够高分辨率精确测绘地形和地表形变的遥感工具。失相干是其主要的限制之一。通过掩膜去除干涉图中的失相干相位对提取有效信息至关重要。然而，对于传统的掩膜方法，手工绘制掩模的方法费时费力，并且在失相干相位的边界十分复杂和模糊时，这种方法几乎不可行。对于阈值法，单一的相干阈值很难或几乎不可能在不造成有效相位损失的情况下对所有的失相干相位进行掩膜。因此，我们提出一个深度学习语义分割网络，Selective Kernel Res-Attention UNet (Mask-Net)，用于生成失相干掩模，并将其应用于TanDEM-X卫星干涉图。为了最大化网络的分割性能，我们设计了多组的权衡实验来确定最佳的网络训练策略，包括最佳样本大小、批训练样本量、损失函数以及下采样方案。然后，我们将本网络与其他经典的分割网络的性能进行了比较。结果表明，Mask-Net的分割性能优于其他经典的分割网络，其中语义分割评价指标IoU和F1-Score分别优于其他经典分割网络最佳性能的6.32%和3.97%。并且本网络具有最快的处理速度，在1024×1024 像素的样本尺寸上仅为0.4505s，超过其他分割网络的最快速度推理速度约50%。最后我们将本网络应用到美国夏威夷Kīlauea火山口、中国武汉城区以及中国西部穆兹塔加塔冰川的TanDEM-X干涉图上，结果表明，Mask-Net可以在那些模糊、微小和复杂的失相干边界上生成准确的掩模。与相干阈值法相比，本网络可以准确地掩膜失相干相位，而很少造成有效相位的损失或破坏其连续性。与其他经典的分割网络相比，本网络在那些微小复杂，模糊的失相干边界上具有更好的分割性能，同时具有最快的推理速度。我们相信，在InSAR大数据时代，这样的网络可以大大节省时间和人力。

<div style="text-align: center;"> <img src="/images/zhangqi.png" alt="softwareTitleEn" width="900"> <br>Decorrelation masks of the TanDEM-X interferogram covering the Wuhan metropolitan region in china using deep-learning networks and different coherence thresholds. (A) Interferogram of Wuhan district (in radar coordinate: 2832-by-5699 pixels). (B) Masked interferogram by applying the Mask Net. (a) Interferogram of ROI (in radar coordinate: 1440-by-992 pixels). (b–e) represent interferograms of ROI-masked by the Mask Net, DeeplabV3+, ResUNet, FCN-8s, respectively. (f–i) represent interferograms of ROI masked by coherence thresholds of 0.2, 0.4, 0.6, 0.8, respectively 
<br>使用深度学习网络及相干性阈值法得到的中国武汉城区TanDEM-X掩膜干涉图 (A) 中国武汉城区TanDEM-X干涉图 （雷达坐标系：2832×5699 像素）。(B) Mask-Net得到的掩膜干涉图 (a) ROI区域的干涉图 （雷达坐标系：1440×992 像素）。(b-e) 表示分别使用Mask-Net, DeepLabV3+, ResUnet，FCN-8s得到ROI区域的掩膜干涉图。 (f-i) 分别表示使用相干性阈值分别为0.2,0.4,0.6,0.8得到的ROI区域的掩膜干涉图。</div>

---

<b>2021-#2</b>  
<div style="text-align: center;">
<b>Small Fractures Caused by the 2019 Ridgecrest Earthquake Sequence: Insights from 3D coseismic displacement and uniaxial loading rock experiments</b>  
<br><b>由2019年Ridgecrest地震序列引起的地表小裂隙:基于三维同震位移和单轴加载岩石实验的研究</b>  
<br><a href="https://doi.org/10.3389/feart.2021.672809">Xu, A., Y. Zhao, T. Wang*, C. Ren, and H. Yue (2021), Small Fractures Caused by the 2019 Ridgecrest Earthquake Sequence: Insights From 3D Coseismic Displacement and Uniaxial Loading Rock Experiments. Frontiers in Earth Science, 9(June), 1–11.</a>
</div>


The moment magnitude (Mw) 6.4 and 7.1 Ridgecrest earthquake sequence occurred on 4th and 6th July 2019, ruptured a conjugate fault system within the eastern California shear zone. In addition to the ~50 km surface ruptures, the sequence activated a series of structures with lengths ranging from 1 to 10 km, which are well illuminated by phase gradient maps of Synthetic Aperture Radar (SAR) interferograms. The deformation patterns and mechanisms of these fractures has been well studied, yet the controlling factors of their spatial distribution are less discussed, which are important for understanding how the accumulated strain is released via distributed faulting in the earthquake cycle. Here, we use multi-source SAR images to derive 3-dimensional (3D) surface displacement along the main ruptures and the east-west strain across the detected small fractures caused by the 2019 Ridgecrest earthquake sequence. We find that the distribution of these fractures is related to the displacement pattern along the main rupture. Specifically, more fractures appeared in areas with larger slips normal to the main rupture as well as in the junction of the conjugated ruptures. We also conduct uniaxial loading rock experiments to evaluate the strain distribution before the samples were broken. Rock experiments show that rupturing of a conjugated fault system may produce local strain concentration along the main rupture, indicating the important role of the orthogonal faults in generating small fractures with different striking angles and deformation patterns. The 2019 Ridgecrest earthquake sequence exhibits complicated crust behaviors by rupturing an immature fault system, implying that the simple elastic rebound theory may be insufficient to model the coseismic deformation during the earthquake cycle, particularly in the zone with weak crust.

2019年7月4日和6日矩震级为6.4和7.1的Ridgecrest地震序列，破裂了加利福尼亚东部剪切带 (eastern California shear zone, ECSZ) 内的一个共轭断层系统。这个地震序列除了造成约50 km的地表破裂外，还激活了一系列被合成孔径雷达 (Synthetic Aperture Radar, SAR) 干涉相位梯度图所揭示的长度为1~10公里的小裂隙。这些小裂隙的变形模式和机制已经得到了很好的研究，但关于它们空间分布的控制因素的讨论却很少，这些因素对于理解地震周期中积累的应变是如何通过分布断层释放的具有重要意义。这里，我们使用了多源SAR图像获取了2019年Ridgecrest地震序列引起的主破裂带沿线的三维地表位移和小裂隙所在位置的东西向应变。我们发现这些小裂隙的分布与主破裂沿线的位移模式有关。具体来说，在主破裂法向位移较大的区域以及共轭断层的交界处，小裂隙的密度较高。我们还进行了单轴加载岩石试验以评估岩石样品破坏前的应变分布。岩石实验的结果表明，共轭断层系统在破裂过程中可能会沿着主破裂产生局部应变集中，这也显示了正交断层对不同走向和变形模式的小裂隙形成所起的重要作用。2019年的Ridgecrest地震序列通过破坏一个不成熟的断裂系统表现出复杂的地壳形变行为，这意味着简单的弹性回跳理论可能不足以模拟地震周期内的同震变形，特别是在地壳较弱的地区。

<div style="text-align: center;"> <img src="/images/xuandong.png" alt="softwareTitleEn" width="500"> <br>Strain fields observed before the broken of marble samples. Colors represent the strain in the direction of X-axis (A) and Y-axis (B) of the marble sample with only one prefabricated fault and of the marble sample with two orthogonal prefabricated faults (C and D, respectively). Positive values indicate tensional strain along the corresponding axis while the negative values indicate compressional strain along the axis. The black line indicates the prefabricated fault and the loading direction is along the negative direction of Y-axis. The principal strain axes within the red rectangles in (C) are shown in (E). The red lines indicate the prefabricated faults, and the black lines represent the compression while the magenta lines represent extension. Surface fractures produced by earthquake sequence in the corresponding areas are shown in (F) for comparison.  
<br>大理岩样品破裂前的应变场特征。颜色代表只有一条预制裂纹的大理岩样品 (A~B) 和两条正交共轭预制裂纹裂纹的大理岩样品 (C~D) 在X方向上和Y方向上的应变。正值表示相应方向的拉张应变，负值表示相应方向的压缩应变。黑色直线显示的是预制裂纹的位置，加载的方向沿Y轴负向。图 (C) 中红色矩形区域内的主应变轴如图 (E) 所示。红色线表示预制裂纹，黑色线表示压缩应变，品红色线表示拉张应变。相应地区地震序列产生的地表破裂如图 (F) 所示。</div>

---

<b>2021-#1</b>  
<div style="text-align: center;">
<b>Deriving centimeter-level coseismic deformation and fault geometries of small-to-moderate earthquakes from time-series Sentinel-1 SAR images</b>  
<br><b>基于时序哨兵雷达数据获取中小地震的厘米级同震地表形变及其断层几何</b>  
<br><a href="https://doi.org/10.3389/feart.2021.636398">Luo, H., Wang, T., Wei, S., Liao, M., and Gong, J. (2021). Deriving Centimeter-Level Coseismic Deformation and Fault Geometries of Small-To-Moderate Earthquakes From Time-Series Sentinel-1 SAR Images. Frontiers in Earth Science 9.</a>
</div>


Small-to-moderate earthquakes (e.g. ≤Mw5.5) occur much more frequently than large ones (e.g. >Mw6.0), yet are difficult to study with InSAR due to their weak surface deformation that are severely contaminated by atmospheric delays. Here we propose a stacking method using time-series SAR images that can effectively suppress atmospheric phase screens and extract weak coseismic deformation in centimeter to sub-centimeter level. Using this method, we successfully derive coseismic surface deformations for three small-to-moderate (Mw∼5) earthquakes in Tibet Plateau and Tienshan region from time-series Sentinel-1 SAR images, with peak line-of-sight deformation ranging from 5mm to 13 mm. We also propose a strategy to downsample interferograms with weak deformation signal based on quadtree mesh obtained from preliminary slip model. With the downsampled datasets, we invert for the centroid locations, fault geometries and slips of these events. Our results demonstrate the potential of using time-series InSAR images to enrich earthquake catalog with geodetic observations for further study of earthquake cycle and active tectonics.

中小型地震(≤Mw5.5)的发生频率远高于大型地震(>Mw6.0)，但由于其微弱的地表形变易受到大气延迟的严重干扰，这些地震往往难以利用InSAR进行研究。因此，我们提出了一种基于时间序列SAR影像的stacking方法，该方法可以有效地抑制大气相位屏，提取厘米级甚至亚厘米级的微弱同震地表形变。利用该方法，基于时间序列哨兵 SAR影像，我们成功地提取了西藏和天山地区3个中小地震(Mw∼5)的同震地表形变，其视线向形变峰值为5-13mm。针对这种微小同震形变，我们还提出了一种新的降采样策略，该策略基于初步滑移模型得到的四叉树网格对原始观测数据进行二次降采样。基于这些降采样数据，我们反演了这些地震的震中位置、断层几何和滑移向量。我们的结果表明，时间序列SAR数据具有巨大的潜力对震源模型提供大地测量观测约束，从而促进地震周期和活动构造的研究。

<div style="text-align: center;"> <img src="/images/research_34_1.png" alt="softwareTitleEn" width="600"> <br>Single coseismic interferograms and final deformations derived using the proposed method. From top to bottom rows: the 2017 Mw5.5 Kuche, 2016 Mw5.2 Nierong, and 2017 Mw5.2 Zhongba earthquakes  
<br>同震干涉图结果和基于时间序列SAR数据stacking处理及降采样后的同震形变分布。从上到下分别为：2017 Mw5.5 库车地震, 2016 Mw5.2 聂荣地震和2017 Mw5.2 仲巴地震</div>

---

<b>2020-#1</b>  
<div style="text-align: center;">
<b>Space imaging geodesy reveals near circular, coseismic block rotation during the 2016 Mw 7.8 Kaikōura earthquake, New Zealand</b>  
<br><b>空间影像大地测量在2016年新西兰凯库拉地震中揭示的近圆形同震块体旋转</b>  
<br><a href="https://www.doi.org/10.1029/2020GL090206">Wang, T., Jiao, L., Tapponnier, P., Shi, X., & Wei, S. (2020). Space imaging geodesy reveals near circular, coseismic block rotation during the 2016 Mw 7.8 Kaikōura earthquake, New Zealand. Geophysical Research Letters, 47, e2020GL090206.</a>
</div>


Large earthquakes usually rupture plate boundary faults, releasing the accumulated stress as displacements localized along smooth, narrow faults. However, certain earthquakes initiate off main faults, rupturing adjacent, secondary faults. The mechanisms of such atypical stress release remain enigmatic, partly due to a lack of detailed geodetic evidence. Here using the 3D coseismic displacement field derived from space imaging geodesy, we detect 10‐km‐scale, nearly‐circular coseismic block rotation during the 2016 Mw 7.8 Kaikōura earthquake in New Zealand. Together, geodetic observations, longer term local paleomagnetic data, analytical, and discrete element modeling imply that localized block rotation occurred south of the Hope fault along weak, steep, bedding‐parallel boundaries within a narrow, ~20‐km‐wide dextral shear zone. That stress near plate boundary faults can be partially released in zones of distributed ruptures absorbing coseismic rotation may retard rupture along main faults. Our observations also suggest that coseismic rotation may help accomodate plate boundary propagation.

大地震通常会通过在板块边界断层发生破裂，将累积的应力以局部位移和应变的形式，沿平滑、狭窄的断层释放出来。然而，某些地震从主断层外开始成核，只破裂相邻的次级断层。这种非典型的应力释放的机制仍然是个谜，部分原因是缺乏详细的大地测量证据。这里，利用空间影像大地测量获得的三维同震形变场，我们在2016年新西兰Mw7.8凯库拉地震中发现了十公里尺度、近圆形的块体旋转。大地测量观测、古地磁数据和有限离散元模型共同揭示：在一个约20公里宽的狭窄右旋剪切带内，沿着弱的、陡峭的、层理面平行的边界，在Hope断层南部发生了局部的块体旋转。沿板块边界断层积累的应力可以在吸收同震旋转的分布式断裂区中部分释放，可能延缓了主断层的断裂。我们的观测结果还表明，同震块体旋转可能有助于调整板块边界传播。

<div style="text-align: center;"> <img src="/images/research_33_1.png" alt="softwareTitleEn" width="800"> <br>Three-dimensional (3D) coseismic displacement along the Hope fault, revealing a new rupture pattern as block rotation.  
<br>Hope断层附近三维同震形变场揭示的块体旋转破裂模式 </div>

----------
# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
