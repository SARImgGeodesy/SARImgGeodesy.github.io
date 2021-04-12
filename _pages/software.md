---
layout: archive
title: "Software"
permalink: /software/
author_profile: true

---

{% include base_path %}

{% for post in site.software reversed %}
  {% include archive-single.html %}
{% endfor %}

 
<div style="text-align: center;"> <img src="/images/softwareTitleEn.png" alt="softwareTitleEn" width="875"> </div>
 

The Sentinel-1 interferometry processor is developed by the [Radar Imaging Geodesy Group](https://sarimggeodesy.github.io/) at Peking University. The software package is designed for large-scale InSAR processing with Sentinel-1 TOPS images, which includes 4 modules:


<div style="text-align: center;"> <img src="/images/software_icons_EN.png" alt="software_icons_EN" width = "500"> </div>

 

## Key features include.

1. The processing is based on Sentinel-1’s burst configuration, allowing for flexible processing strategy. The mosaic of burst interferogram is unlimited. The software can not only process single-burst interferogram, but also mosaic **any number of frames** to form an interferogram spanning thousands of kilometers.

2. The software is fully parallelized based on multi-thread algorithms. The processing time for producing one full-frame geocoded interferogram (90m resolution) is only **5 minutes and 5 seconds** (test environment: Thinkpad Laptop, Intel(R) 6-core i7-8850H CPU @2.60GHz, 32 GB RAM, SSD hard drive).

3. The entire process is **fully automatized**. According to the application requirements, users only need to set the multilook factors, filter parameters, baseline thresholds for interferometric configuration and a few parameters regarding to the area of interest. After that, the data processing can be done without human interaction.

4. The software uses a de-reference SLC storage strategy, which allows for less storage space occupation, fast and flexible processing. Users can **quickly generate any interferograms based on given baseline configuration**. After the burst-based processing, the processing time for producing a geocoded full-frame interferogram (90 meters) is less than one minute.

5. Interferograms are stored in geotiff format, and the radar parameter files are stored in text files. Users can choose any area in the map interface to export the result to StaMPS format for time-series InSAR analysis.

6. Windows **graphical user interface**, easy to operate, easy to use, no professional training is required to generate interferograms for various applications.

 

 <div style="text-align: center;"> <img src="/images/softwareTitleCn.png" alt="softwareTitleCn" width="600"> </div>

Sentinel-1 干涉处理器是北京大学[雷达影像测地学团队](https://sarimggeodesy.github.io/)针对Sentinel-1 TOPS数据开发的广域InSAR数据处理软件。包含四大模块：  

 
<div style="text-align: center;"> <img src="/images/software_icons_CN.png" alt="software_icons_CN" width = "500"> </div>

 

## 主要特点包括：

1. 数据处理基于Burst进行，更加灵活可控。拼接无限制，既可以处理单个burst，也可以拼接**任意多frame**的数据，形成数千公里长的干涉图。

2. 采用CPU多线程并行算法，干涉处理速度快于市面上所有哨兵1号SAR数据处理软件，处理一个标准副干涉影像对，从影像配准到地理编码干涉图（90米分辨率）**5****分5****秒**（测试环境为Thinkpad笔记本电脑，Intel(R) 6核i7-8850H CPU @ 2.60GHz，32 GB内存，SSD硬盘）。

3. 整个处理过程基本**全自动化**进行。只需根据应用需求设置多视、滤波等参数，其他数据处理参数无需人为干预。

4. 采用去参考相位SLC存储策略，一次配准后即可**快速生成任意基线组合干涉图（****90****米分辨率干涉图小于一分钟一对）**，存储空间占用少，干涉处理快速、灵活。

5. 干涉图为通用geotif格式存储，雷达参数文件以文本方式存储。可在地图界面选择任意区域将结果导出为StaMPS处理格式进行时序处理。

6. Windows系统下专业**图形界面**，操作方便、易于上手，无需专业培训即可生成各种应用场景下的干涉图。  

<div style="text-align: center;"> <img src="/images/software_cases.jpg" alt="software_cases" width = "500"> </div>  

## Click to download

If you'd like to use the trail version for teaching, much appreciate if you could let us know your affiliation and some basic information about your class. Feedbacks from you and your students will help us improve the software.

<img src="/images/Trial version logo.png" width = "40" height = "40" /> [Trial version](https://github.com/Wu-Patrick/MyDownload/raw/master/Sentinel-1Processor-PublicRelease.zip) (can process images acquired in 2019 and 2020)

<img src="/images/Full version logo.png" width = "40" height = "40" /> Full version [(contact us)](mailto:wang.teng@pku.edu.cn)

## Manual

<img src="/images/manual logo.png" width = "40" height = "40" /> [中文](/files/哨兵1数据处理软件手册-v1.0.pdf)

<img src="/images/manual logo.png" width = "40" height = "40" /> [English](/files/Sentinel1Processor_Mannual-v1.0.pdf)

