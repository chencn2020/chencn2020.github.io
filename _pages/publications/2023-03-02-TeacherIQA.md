
<div class='paper-box'>
<div class='paper-box-image-text'>
<div class='paper-box-image'><div><div class="badge">ACCV 2022</div><img src='images/publications/teacherIQA.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">
<div style="margin-bottom: 5px; font-size:1.2em">
    <b>Teacher-Guided Learning for Blind Image Quality Assessment</b>
</div>

**Zewen Chen**, Juan Wang, Bing Li et al.

<b style="color:rgb(140, 27, 19)"> TL;DR: </b> We introduce a novel NR-IQA framework that leverages an image restoration teacher network (TN) to transfer semantic and distortion knowledge to a student network (SN), enabling superior BIQA performance on limited annotated data with validated generalization, robustness, and effectiveness.

<div style="margin-top: 5px;">
    <a href="https://openaccess.thecvf.com/content/ACCV2022/html/Chen_Teacher-Guided_Learning_for_Blind_Image_Quality_Assessment_ACCV_2022_paper.html" target="_blank"><img src="https://img.shields.io/badge/Paper-blue" style="max-width: 100%; height: auto;"></a>
    <a href="https://github.com/chencn2020/TeacherIQA"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github
    " target="_blank" style="max-width: 100%; height: auto;"></a>
</div>

</div>
</div> 
<details>
    <summary><b>Quick Read (Click Me)</b></summary> The performance of deep learning models for blind image quality assessment (BIQA) suffers from annotated data insufficiency. However, image restoration, as a closely-related task with BIQA, can easily acquire training data without annotation. Moreover, both image semantic and distortion information are vital knowledge for the two tasks to predict and improve image quality. Inspired by these, this paper proposes a novel BIQA framework, which builds an image restoration model as a teacher network (TN) to learn the two aspects of knowledge and then guides the student network (SN) for BIQA. In TN, multi-branch convolutions are leveraged for performing adaptive restoration from diversely distorted images to strengthen the knowledge learning. Then the knowledge is transferred to the SN and progressively aggregated by computing long-distance responses to improve BIQA on small annotated data. Experimental results show that our method outperforms many state-of-the-arts on both synthetic and authentic datasets. Besides, the generalization, robustness and effectiveness of our method are fully validated.
</details>
</div>
