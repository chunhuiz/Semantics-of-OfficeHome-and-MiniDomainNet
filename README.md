# Semantic Annotations for Office-Home and Mini-DomainNet

Welcome to our repository where we provide semantic annotations for the Office-Home [1] and Mini-DomainNet [2] datasets. The annotations are intended to facilitate research in cross-domain generalized zero-shot learning.

## Repository Contents

This repository contains three main files:

- `LLM_semantics_MiniDomainNet.docx`
- `LLW_semantics_Officehome.docx`
- `attr_matrix_Officehome.xlsx`

### Description of the Files

1. **LLM_semantics_MiniDomainNet.docx**: This document contains text that has been automatically generated by a large language model (LLM) based on the class categories within the Mini-DomainNet dataset. Users are encouraged to independently validate the relevance and accuracy of the content, as we do not guarantee the precision of the text produced by the LLM.

2. **LLW_semantics_Officehome.docx**: Similar to the Mini-DomainNet document, this file includes text produced by a large language model for the Office-Home dataset. Again, the user is responsible for confirming the authenticity of the information provided.

3. **attr_matrix_Officehome.xlsx**: This Excel file contains hand-annotated semantic attributes for the Office-Home dataset. 

## Usage Guidelines

If you wish to use the semantics provided in this repository in your research or publications, please ensure to cite the relevant work as follows:

@article{Yue_CDGZSL2024,
title={Less but Better: Enabling Generalized Zero-shot Learning Towards Unseen Domains by Intrinsic Learning from Redundant LLM Semantics},
author={Jiaqi Yue, Jiancheng Zhao, and Chunhui Zhao},
year={2024}
}

## Disclaimer

The semantic text documents (`LLM_semantics_MiniDomainNet.docx` and `LLW_semantics_Officehome.docx`) are generated by a large language model and are provided "as is" without any guarantees of accuracy. We encourage users to review and verify the content before using it in their scholarly work.

The `attr_matrix_Officehome.xlsx` file, while hand-annotated, could also be subject to human error. 

[1] H. Venkateswara, J. Eusebio, S. Chakraborty, and S. Panchanathan, “Deep hashing network for unsupervised domain adaptation,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2017, pp. 5018–5027.

[2] K. Zhou, Y. Yang, Y. Qiao, and T. Xiang, “Domain adaptive ensemble learning,” IEEE Transactions on Image Processing, vol. 30, pp. 8008–8018, 2021.