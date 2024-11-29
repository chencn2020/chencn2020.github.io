
<div class='paper-box'>
<div class='paper-box-image-text'>
<div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/publications/PromptIQA.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">
<div style="margin-bottom: 5px; font-size:1.2em">
    <b>PromptIQA: Boosting the Performance and Generalization for No-Reference Image Quality Assessment via Prompts</b>
</div>

**Zewen Chen**, Haina Qin, Juan Wang, Chunfeng Yuan et al.

<b style="color:rgb(140, 27, 19)"> TL;DR: </b> We propose a novel IQA network (PromptIQA) for all-in-one IQA and fast adaptation on new assessment requirements.

<div style="margin-top: 5px;">
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-73232-4_14" target="_blank"><img src="https://img.shields.io/badge/Paper-blue" style="max-width: 100%; height: auto;"></a>
    <a href="https://arxiv.org/abs/2403.04993" target="_blank"><img src="https://img.shields.io/badge/Arxiv-red" style="max-width: 100%; height: auto;"></a>
    <a href="https://github.com/chencn2020/PromptIQA" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github" style="max-width: 100%; height: auto;"></a>
    <a href="https://huggingface.co/spaces/Zevin2023/PromptIQA" target="_blank"><img src="images/open-in-hf-spaces-sm-dark.svg" alt="Open in Spaces" style="max-width: 100%; height: auto;"></a>
</div>


</div>
</div> 
<details>
    <summary><b>Quick Read (Click Me)</b></summary> Due to the diversity of assessment requirements in various application scenarios for the IQA task, existing IQA methods struggle to directly adapt to these varied requirements after training. Thus, when facing new requirements, a typical approach is fine-tuning these models on datasets specifically created for those requirements. However, it is time-consuming to establish IQA datasets. In this work, we propose a Prompt-based IQA (PromptIQA) that can directly adapt to new requirements without fine-tuning after training. On one hand, it utilizes a short sequence of Image-Score Pairs (ISP) as prompts for targeted predictions, which significantly reduces the dependency on the data requirements. On the other hand, PromptIQA is trained on a mixed dataset with two proposed data augmentation strategies to learn diverse requirements, thus enabling it to effectively adapt to new requirements. Experiments indicate that the PromptIQA outperforms SOTA methods with higher performance and better generalization.
</details>
</div>
