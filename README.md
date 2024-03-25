# Retrieval Helps or Hurts? A Deeper Dive into the Efficacy of Retrieval Augmentation to Language Models 	

[![Conference](https://img.shields.io/badge/naacl-2024-red)]()
[![arXiv](https://img.shields.io/badge/arxiv-2402.13492-success)](https://arxiv.org/abs/2402.13492)

This repository is the codebase of our paper "Retrieval Helps or Hurts? A Deeper Dive into the Efficacy of Retrieval Augmentation to Language Models". 

![WiTQA data creation overview](/figures/WiTQA_images.png)

## Citations
```bibtex
@inproceedings{maekawa2024retrieval,
      title = "Retrieval Helps or Hurts? A Deeper Dive into the Efficacy of Retrieval Augmentation to Language Models", 
      author = "Seiji Maekawa and Hayate Iso and Sairam Gurajada and Nikita Bhutani",
      year = "2024",
      booktitle= "Proceedings of the 2024 Annual Conference of the North American Chapter of the Association for Computational Linguistics",
      publisher = "Association for Computational Linguistics",
      url = "https://arxiv.org/abs/2402.13492",
}
```

# Dataset overview (WiTQA)
| Description                                       | Count     |
|---------------------------------------------------|-----------|
| Questions                                         | 14,837    |
| Unique subject entities                           | 13,251    |
| Unique object entities                            | 7,642     |
| Average length of supporting passages (characters)| 214.3     |
| Questions added in first roundtrip                | 12,856    |
| Questions added in second roundtrip               | 823       |
| Questions added in third roundtrip                | 283       |
| Questions written by annotators                   | 743       |

| ID  | Dataset | Copyright Holder       | Source Link                                                       | License            | 
|-----|---------|------------------------|-------------------------------------------------------------------|--------------------|
| 1   | WiTQA | Megagon Labs | [Wikipedia dump](https://archive.org/download/enwiki-20211020/), [OpenAI API](https://openai.com/blog/openai-api) | CC BY-SA 4.0 license |

# Disclosure
Embedded in, or bundled with, this product are open source software (OSS) components, datasets and other third party components identified below. The license terms respectively governing the datasets and third-party components continue to govern those portions, and you agree to those license terms, which, when applicable, specifically limit any distribution. You may receive a copy of, distribute and/or modify any open source code for the OSS component under the terms of their respective licenses, which may be BSD 3 clause license and Apache 2.0 license. In the event of conflicts between Megagon Labs, Inc., license conditions and the Open Source Software license conditions, the Open Source Software conditions shall prevail with respect to the Open Source Software portions of the software. 
You agree not to, and are not permitted to, distribute actual datasets used with the OSS components listed below. You agree and are limited to distribute only links to datasets from known sources by listing them in the datasets overview table below. You are permitted to distribute derived datasets of data sets from known sources by including links to original dataset source in the datasets overview table below. You agree that any right to modify datasets originating from parties other than Megagon Labs, Inc. are governed by the respective third party’s license conditions. 
All OSS components and datasets are distributed WITHOUT ANY WARRANTY, without even implied warranty such as for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE, and without any liability to or claim against any Megagon Labs, Inc. entity other than as explicitly documented in this README document. You agree to cease using any part of the provided materials if you do not agree with the terms or the lack of any warranty herein.
While Megagon Labs, Inc., makes commercially reasonable efforts to ensure that citations in this document are complete and accurate, errors may occur. If you see any error or omission, please help us improve this document by sending information to contact_oss@megagon.ai.