---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
show_sidebar: false
menubar: index_menu
---

## 🎓 Education

<div style="display: inline-block; margin: 1em 0 0 0; width: 100%">
    <div style="float: left;">
        <img src="/img/icon/usyd.png" alt="USYD" style="width: 3em; margin: 0 1em 1em 1em">
    </div>
    <div style="float: left; margin: 0 0 0 1em">
        <h5>Doctor of Philosophy</h5>
        <div>School of Computer Science, Faculty of Engineering</div>
        <div>The University of Sydney, Australia</div>
        <div style="color: grey;">Oct. 2021 - Now</div>
    </div>
</div>

<div style="display: inline-block; margin: 1em 0 0 0; width: 100%">
    <div style="float: left;">
        <img src="/img/icon/usyd.png" alt="USYD" style="width: 3em; margin: 0 1em 1em 1em">
    </div>
    <div style="float: left; margin: 0 0 0 1em">
        <h5>Master of Philosophy</h5>
        <div>School of Computer Science, Faculty of Engineering</div>
        <div>The University of Sydney, Australia</div>
        <div style="color: grey;">Oct. 2019 - Sept. 2020</div>
    </div>
</div>

<div style="display: inline-block; margin: 1em 0 0 0; width: 100%">
    <div style="float: left;">
        <img src="/img/icon/cnu.png" alt="CNU" style="width: 3em; margin: 0 1em 1em 1em">
    </div>
    <div style="float: left; margin: 0 0 0 1em">
        <h5>Bachelor of Engineering</h5>
        <div>Faculty of Electronic and Information Engineering</div>
        <div>Capital Normal University, China</div>
        <div style="color: grey;">Sept. 2014 - June 2018</div>
    </div>
</div>

## 📝 Publications

> Contributed as the first author to **1 TPAMI** paper, **2 NeurIPS** papers, **2 ICML** papers, **1 CVPR** paper, and **1 AAAI** paper.

#### Journal Papers

* 2022

    **<span class='publication_index'></span>**&nbsp;&nbsp; **Yanxi Li**, Minjing Dong, Yunhe Wang & Chang Xu. "*Neural Architecture Search via Proxy Validation*". In IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**). <span style="color: red; font-weight: bold;">NEW</span> 🚩.

    **<span class='publication_index'></span>**&nbsp;&nbsp; **Yanxi Li**, Minjing Dong, Yixing Xu, Yunhe Wang & Chang Xu. "*Neural Architecture Tuning with Policy Adaptation*". In Neurocomputing.

#### Conference Papers

* 2023

    **<span class='publication_index'></span>**&nbsp;&nbsp; **Yanxi Li** & Chang Xu. "*Trade-off between Robustness and Accuracy of Vision Transformers*". In The IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**). <span style="color: red; font-weight: bold;">NEW</span> 🚩.

    **<span class='publication_index'></span>**&nbsp;&nbsp; Zhi Cheng, **Yanxi Li**, Minjing Dong, Xiu Su, Shan You & Chang Xu. "*Neural Architecture Search for Wide Spectrum Adversarial Robustness*". In The AAAI Conference on Artificial Intelligence (**AAAI**). <span style="color: red; font-weight: bold;">Distinguished Paper Award</span> 🚩.

* 2022

    **<span class='publication_index'></span>**&nbsp;&nbsp; **Yanxi Li**, Xinghao Chen, Minjing Dong, Yehui Tang, Yunhe Wang & Chang Xu. "*Spatial-channel Token Distillation for Vision MLPs*". In International Conference on Machine Learning (**ICML**).

    **<span class='publication_index'></span>**&nbsp;&nbsp; Yehui Tang, Kai Han, Jianyuan Guo, Chang Xu, **Yanxi Li**, Chao Xu & Yunhe Wang. "*An Image Patch Is a Wave: Phase-Aware Vision MLP*". In The IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**).

* 2021

    **<span class='publication_index'></span>**&nbsp;&nbsp; **Yanxi Li**, Zean Wen, Yunhe Wang & Chang Xu. "*One-shot Graph Neural Architecture Search with Dynamic Search Space*". In The AAAI Conference on Artificial Intelligence (**AAAI**).

    **<span class='publication_index'></span>**&nbsp;&nbsp; **Yanxi Li**, Zhaohui Yang, Yunhe Wang & Chang Xu. "*Neural Architecture Dilation for Adversarial Robustness*". In Advances in Neural Information Processing Systems (**NeurIPS**).

    **<span class='publication_index'></span>**&nbsp;&nbsp; Xiu Su, Tao Huang, **Yanxi Li**, Shan You, Fei Wang, Chen Qian, Changshui Zhang & Chang Xu. "*Prioritized Architecture Sampling With Monto-Carlo Tree Search*". In The IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**).

* 2020

    **<span class='publication_index'></span>**&nbsp;&nbsp; **Yanxi Li**, Minjing Dong, Yunhe Wang & Chang Xu. "*Neural Architecture Search in A Proxy Validation Loss Landscape*". In International Conference on Machine Learning (**ICML**).
    {% comment %}
    [<a href="javascript:toggle_element('abs_li2020neural')"><u>Abstract</u></a>,
     <a href="https://proceedings.icml.cc/static/paper_files/icml/2020/439-Paper.pdf" target="_blank"><u>PDF</u></a>,
     <a href="javascript:open_new_page('@inproceedings{li2020neural,<br>
            title={Neural architecture search in a proxy validation loss landscape},<br>
            author={Li, Yanxi and Dong, Minjing and Wang, Yunhe and Xu, Chang},<br>
            booktitle={International Conference on Machine Learning},<br>
            year={2020}<br>
        }')"><u>BibTex</u></a>,
     <a href="https://github.com/liyxi/PVLL-NAS" target="_blank"><u>Code</u></a>].
     <div id="abs_li2020neural" style="text-align: justify; display: none; margin: 0 0 0 4em">
        <p>
            This paper searches for the optimal neural architecture by minimizing a proxy of validation loss. Existing neural architecture search (NAS) methods used to discover the optimal neural architecture that best fits the validation examples given the up-to-date network weights. However, back propagation with a number of validation examples could be time consuming, especially when it needs to be repeated many times in NAS. Though these intermediate validation results are invaluable, they would be wasted if we cannot use them to predict the future from the past. In this paper, we propose to approximate the validation loss landscape by learning a mapping from neural architectures to their corresponding validate losses. The optimal neural architecture thus can be easily identified as the minimum of this proxy validation loss landscape. A novel sampling strategy is further developed for an efficient approximation of the loss landscape. Theoretical analysis indicates that the validation loss estimator learned with our sampling strategy can reach a lower error rate and a lower label complexity compared with a uniform sampling. Experimental results on benchmarks demonstrate that the architecture searched by the proposed algorithm can achieve a satisfactory accuracy with less time cost.
        </p>
    </div>
    {% endcomment %}

    **<span class='publication_index'></span>**&nbsp;&nbsp; **Yanxi Li**, Zhaohui Yang, Yunhe Wang & Chang Xu. "*Adapting Neural Architectures Between Domains*". In Advances in Neural Information Processing Systems (**NeurIPS**).
    {% comment %}
    [<a href="javascript:toggle_element('abs_li2020adapting')"><u>Abstract</u></a>,
     <a href="javascript:open_new_page('Coming soon.')"><u>PDF</u></a>,
     <a href="javascript:open_new_page('@inproceedings{li2020adapting,<br>
            title={Adapting Neural Architectures Between Domains},<br>
            author={Li, Yanxi and Yang, Zhaohui and Wang, Yunhe and Xu, Chang},<br>
            booktitle={Advances in Neural Information Processing Systems},<br>
            year={2020}<br>
        }')"><u>BibTex</u></a>,
     <a href="https://github.com/liyxi/AdaptNAS" target="_blank"><u>Code</u></a>].
    <div id="abs_li2020adapting" style="text-align: justify; display: none; margin: 0 0 0 4em">
        <p>
            Neural architecture search (NAS) has demonstrated impressive performance in automatically designing high-performance neural networks. The power of deep neural networks is to be unleashed for analyzing a large volume of data (e.g. ImageNet), but the architecture search is often executed on another smaller dataset (e.g. CIFAR-10) to finish it in a feasible time. However, it is hard to guarantee that the optimal architecture derived on the proxy task could maintain its advantages on another more challenging dataset. This paper aims to improve the generalization of neural architectures via domain adaptation. We analyze the generalization bounds of the derived architecture and suggest its close relations with the validation error and the data distribution distance on both domains. These theoretical analyses lead to AdaptNAS, a novel and principled approach to adapt neural architectures between domains in NAS. Our experimental evaluation shows that only a small part of ImageNet will be sufficient for AdaptNAS to extend its architecture success to the entire ImageNet and outperform state-of-the-art comparison algorithms.
        </p>
        <br>
    </div>
    {% endcomment %}

<script type='text/javascript'>

    var publication_count = 1;
    var publication_indices = document.getElementsByClassName("publication_index");
    for (var i = 0; i <= publication_indices.length - 1; i++) {
        publication_indices[i].innerHTML = '[' + publication_count + ']';
        publication_count++;
    }

    function open_new_page(text)
    {
        var bib_page = window.open("", "_blank");
        bib_page.document.write(text);
    }

    function toggle_element(element_id) {
        var element = document.getElementById(element_id);
        if (element.style.display === "none") {
            element.style.display = "block";
        } else {
            element.style.display = "none";
        }
    }

</script>

## 🖥 Industrial Experience

<div style="display: inline-block; margin: 1em 0 0 0; width: 100%">
    <div style="float: left;">
        <img src="/img/icon/ibm.png" alt="IBM" style="width: 3em; margin: 0 1em 1em 1em">
    </div>
    <div style="float: left; margin: 0 0 0 1em">
        <h4>Development Intern</h4>
        <div>IBM China Development Lab</div>
        <div style="color: grey;">Apr. 2018 - June 2018</div>
    </div>
</div>
