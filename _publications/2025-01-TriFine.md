---
title: "TriFine: A Large-Scale Dataset of Vision-Audio-Subtitle for Tri-Modal Machine Translation and Benchmark with Fine-Grained Annotated Tags"
collection: publications
category: conferences
permalink: /publication/2025-01-TriFine
excerpt: 'This paper introduces TriFine, the first large-scale dataset for tri-modal (vision, audio, subtitle) machine translation with fine-grained annotated tags, and proposes a novel translation method FIAT that leverages this fine-grained information to achieve superior translation performance.'
date: 2025-01-15
venue: '<span style="background-color:rgb(32, 98, 168); color: white; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-style: normal;">CCF B</span> COLING 2025'
paperurl: 'https://aclanthology.org/2025.coling-main.547.pdf'
codeurl: 'https://github.com/BoyuGuan/TriFine'
dataseturl: 'https://github.com/BoyuGuan/TriFine'
slidesurl: '/files/paper-TriFine/oral-TriFine.pdf'
videourl: # '#'
posterurl: #'#'
demourl: # '#'
authors: '**Boyu Guan**, Yining Zhang, Yang Zhao<sup>#</sup>, Chengqing Zong'
acceptance_status: 'Oral (9.8%)'
header:
  teaser: 'paper-TriFine/TriFine.png'
citation: 'TriFine: A Large-Scale Dataset of Vision-Audio-Subtitle for Tri-Modal Machine Translation and Benchmark with Fine-Grained Annotated Tags (Guan et al., COLING 2025)'
---

# Abstract 

Current video-guided machine translation (VMT) approaches primarily use coarsegrained visual information, resulting in information redundancy, high computational overhead, and neglect of audio content. Our research demonstrates the significance of finegrained visual and audio information in VMT from both data and methodological perspectives. From the data perspective, we have developed a large-scale dataset TriFine, the first vision-audio-subtitle tri-modal VMT dataset with annotated multimodal fine-grained tags. Each entry in this dataset not only includes the triples found in traditional VMT datasets but also encompasses seven fine-grained annotation tags derived from visual and audio modalities. From the methodological perspective, we propose a Fine-grained Information-enhanced Approach for Translation (FIAT). Experimental results have shown that, in comparison to traditional coarse-grained methods and text-only models, our fine-grained approach achieves superior performance with lower computational overhead. These findings underscore the pivotal role of fine-grained annotated information in advancing the field of VMT.

# TriFine

<!-- ![示例图片](../files/paper-TriFine/TriFine.png) -->


<figure style="display: table; margin: auto;">
  <img src="../files/paper-TriFine/TriFine.png" alt="The Construction Process of TriFin" style="width:90%; display: block; margin: auto;">
  <figcaption style="text-align: center; font-size: 0.9em; color: gray;">The Construction Process of TriFine</figcaption>
</figure>

<br>

<figure style="display: table; margin: auto;">
  <img src="../files/paper-TriFine/1.png" alt="Statistics of the TriFine Dataset" style="width:40%; display: block; margin: auto;">
  <figcaption style="text-align: center; font-size: 0.9em; color: gray;">Statistics of the TriFine Dataset</figcaption>
</figure>

<br>

<figure style="display: table; margin: auto;">
  <img src="../files/paper-TriFine/2.png" alt="Statistical comparison between the TriFine dataset and other VMT datasets" style="width:90%; display: block; margin: auto;">
  <figcaption style="text-align: center; font-size: 0.9em; color: gray;">Statistical comparison between the TriFine dataset and other VMT datasets. “# FG” denotes the number of fine-grained tag types. “Amb” and “Info-spec” refer to the ambiguity and information-specific test sets, respectively. “A-S Align” indicates whether audio-subtitle alignment is provided.
Note: Although BigVideo initially reported 4.5 million clips, only 3.3 million are publicly available due to privacy restrictions.</figcaption>
</figure>



# FIAT

<figure style="display: table; margin: auto;">
  <img src="../files/paper-TriFine/3.png" alt="FIAT framework architecture" style="width:90%; display: block; margin: auto;">
  <figcaption style="text-align: center; font-size: 0.9em; color: gray;">FIAT framework architecture</figcaption>
</figure>

<br>

<figure style="display: table; margin: auto;">
  <img src="../files/paper-TriFine/4.png" alt="Main Experimental Results of the FIAT Method" style="width:90%; display: block; margin: auto;">
  <figcaption style="text-align: center; font-size: 0.9em; color: gray;">Main Experimental Results of the FIAT Method</figcaption>
</figure>


<!-- <figure style="text-align:center;">
  <img src="../files/paper-TriFine/2.png" alt="Statistics of the TriFine Dataset" style="width:90%;">
  <figcaption style="text-align:center; font-size: 0.9em; color: gray;">Statistical comparison between the TriFine dataset and other VMT datasets. “# FG” denotes the number of fine-grained tag types. “Amb” and “Info-spec” refer to the ambiguity and information-specific test sets, respectively. “A-S Align” indicates whether audio-subtitle alignment is provided.
Note: Although BigVideo initially reported 4.5 million clips, only 3.3 million are publicly available due to privacy restrictions.</figcaption>
</figure> -->

<!-- <div style="text-align:center;">
<img src="../files/paper-TriFine/TriFine.png" alt="The Construction Process of TriFine" style="width:90%;"/>
<figcaption style="font-size: 0.9em; color: gray;">图 1：这是图片的说明文字</figcaption>
</div> -->



