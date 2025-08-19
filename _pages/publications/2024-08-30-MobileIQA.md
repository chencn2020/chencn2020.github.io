
<div class='paper-box'>
<div class='paper-box-image-text'>
<div class='paper-box-image'><div><div class="badge">ECCVW 2024</div><img src='images/publications/MobileIQA.jpg' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">
<div style="margin-bottom: 5px; font-size:1.2em">
    <b>MobileIQA: Exploiting Mobile-level Diverse Opinion Network For No-Reference Image Quality Assessment Using Knowledge Distillation</b>
</div>

**Zewen Chen**, Sunhan Xu, Yun Zeng et al.

<b style="color:rgb(140, 27, 19)"> TL;DR: </b> We exlpore a lightweight IQA network (MobileIQA) for high resolution image quality assessment.

<div style="margin-top: 5px;">
    <a href="https://dl.acm.org/doi/10.1007/978-3-031-91856-8_1" target="_blank"><img src="https://img.shields.io/badge/Paper-blue" style="max-width: 100%; height: auto;"></a>
    <a href="https://github.com/chencn2020/MobileIQA" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github" style="max-width: 100%; height: auto;"></a>
</div>


</div>
</div> 
<details>
    <summary><b>Quick Read (Click Me)</b></summary> With the rising demand for high-resolution (HR) images, No-Reference Image Quality Assessment (NR-IQA) gains more attention, as it can ecaluate image quality in real-time on mobile devices and enhance user experience. However, existing NR-IQA methods often resize or crop the HR images into small resolution, which leads to a loss of important details. And most of them are of high computational complexity, which hinders their application on mobile devices due to limited computational resources. To address these challenges, we propose MobileIQA, a novel approach that utilizes lightweight backbones to efficiently assess image quality while preserving image details through high-resolution input. MobileIQA employs the proposed multi-view attention learning (MAL) module to capture diverse opinions, simulating subjective opinions provided by different annotators during the dataset annotation process. The model uses a teacher model to guide the learning of a student model through knowledge distillation. This method significantly reduces computational complexity while maintaining high performance. Experiments demonstrate that MobileIQA outperforms novel IQA methods on evaluation metrics and computational efficiency.
</details>
</div>
