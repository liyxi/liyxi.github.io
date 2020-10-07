---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
show_sidebar: false
menubar: index_menu
---

## News

- ***Adapting Neural Architectures Between Domains*** is accepted by NeurIPS 2020.
- ***Neural Architecture Search in a Proxy Validation Loss Landscape*** is accepted by ICML 2020.

## Publications

<!-- ## Journal Papers: -->

#### Conference Papers:

<span class='publication_index'></span> Li, Y., Yang, Z., Wang, Y., & Xu, C. (2020). ***Adapting Neural Architectures Between Domains***. In Neural Information Processing Systems (NeurIPS).
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

<span class='publication_index'></span> Li, Y., Dong, M., Wang, Y., & Xu, C. (2020). ***Neural architecture search in a proxy validation loss landscape***. In International Conference on Machine Learning (ICML).
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


<script type='text/javascript'>

    var publication_count = 1;
    var publication_indices = document.getElementsByClassName("publication_index");
    for (var i = 0; i <= publication_indices.length - 1; i++) {
        publication_indices[i].innerHTML = publication_count + '.';
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
