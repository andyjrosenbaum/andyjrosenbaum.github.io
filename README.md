## Blog Posts

### [Using large language models (LLMs) to synthesize training data](https://www.amazon.science/blog/using-large-language-models-llms-to-synthesize-training-data)

**Andy Rosenbaum**, Saleh Soltan, Wael Hamza

Amazon Science \| January 2023

## Publications

### CALICO: Conversational Agent Localization via Synthetic Data Generation

**Andy Rosenbaum**, Pegah Kharazmi, Ershad Banijamali, Lu Zeng, Christopher DiPersio, Vivi Wei, Gokmen Oz, Clement Chung, Karolina Owczarzak, Fabian Triefenbach, Wael Hamza

> Abstract: We present CALICO, a method to fine-tune Large Language Models (LLMs) to localize conversational agent training data from one language to another. For slots (named entities), CALICO supports three operations: verbatim copy, literal translation, and localization, i.e. generating slot values more appropriate in the target language, such as city and airport names located in countries where the language is spoken. Furthermore, we design an iterative filtering mechanism to discard noisy generated samples, which we show boosts the performance of the downstream conversational agent. To prove the effectiveness of CALICO, we build and release a new human-localized (HL) version of the MultiATIS++ travel information test set in 8 languages. Compared to the original human-translated (HT) version of the test set, we show that our new HL version is more challenging. We also show that CALICO out-performs state-of-the-art LINGUIST (which relies on literal slot translation out of context) both on the HT case, where CALICO generates more accurate slot translations, and on the HL case, where CALICO generates localized slots which are closer to the HL test set.

Presented at [NeurIPS 2023 Workshop on SyntheticData4ML 2023](https://www.syntheticdata4ml.vanderschaar-lab.com) \| New Orleansa, LA, USA \| December 16, 2023

[Amazon Science](https://www.amazon.science/publications/calico-conversational-agent-localization-via-synthetic-data-generation)

### GeMQuAD: Generating Multilingual Question Answering Datasets from Large Language Models Using Few Shot Learning

Amani Namboori, Shivam Mangale, **Andy Rosenbaum**, Saleh Soltan

> Abstract: The emergence of Large Language Models (LLMs) with capabilities like In-Context Learning (ICL) has ushered in new possibilities for data generation across various domains while minimizing the need for extensive data collection and modeling techniques. Researchers have explored ways to use this generated synthetic data to optimize smaller student models for reduced deployment costs and lower latency in downstream tasks. However, ICL-generated data often suffers from low quality as the task specificity is limited with few examples used in ICL. In this paper, we pro-pose GeMQuAD - a semi-supervised learning approach, extending the WeakDAP framework, applied to a dataset generated through ICL with just one example in the target language using AlexaTM 20B Seq2Seq LLM. Through our approach, we iteratively identify high-quality data to enhance model performance, especially for low-resource multilingual setting in the context of Extractive Question Answering task. Our framework outperforms the machine translation-augmented model by 0.22/1.68 F1/EM (Exact Match) points for Hindi and 0.82/1.37 F1/EM points for Spanish on the MLQA dataset, and it surpasses the performance of model trained on an English-only dataset by 5.05/6.50 F1/EM points for Hindi and 3.81/3.69 points F1/EM for Spanish on the same dataset. Notably, our approach uses a pre-trained LLM for generation with no fine-tuning (FT), utilizing just a single annotated example in ICL to generate data, providing a cost-effective development process.

Presented at [NeurIPS 2023 Workshop on SyntheticData4ML 2023](https://www.syntheticdata4ml.vanderschaar-lab.com) \| New Orleansa, LA, USA \| December 16, 2023

[Amazon Science](https://www.amazon.science/publications/gemquad-generating-multilingual-question-answering-datasets-from-large-language-models-using-few-shot-learning)

### Recipes for Sequential Pre-training of Multilingual Encoder and Seq2Seq Models

Saleh Soltan, **Andy Rosenbaum**, Tobias Falke, Qin Lu, Anna Rumshisky, Wael Hamza

Presented at Findings of [ACL 2023](https://2023.aclweb.org) (The 61st Annual Meeting of the Association for Computational Linguistics) and [SustaiNLP 2023](https://sites.google.com/view/sustainlp2023) (Fourth Workshop on Simple and Efficient Natural Language Processing) \| Toronto, ON, Canada \| July 9-14, 2023

[ACL Anthology](https://aclanthology.org/2023.findings-acl.598/) \| [Amazon Science](https://www.amazon.science/publications/recipes-for-sequential-pre-training-of-multilingual-encoder-and-seq2seq-models) \| [arXiv](https://arxiv.org/abs/2306.08756)

### Sampling bias in NLU models: Impact and mitigation

Zefei Li, Anil Ramakrishna, Anna Rumshisky, **Andy Rosenbaum**, Saleh Soltan, Rahul Gupta

Presented at [Interspeech 2023](https://interspeech2023.org) \| Dublin, Ireland \| August 20-24, 2023

[Amazon Science](https://www.amazon.science/publications/sampling-bias-in-nlu-models-impact-and-mitigation)

### PLACES: Prompting Language Models for Social Conversation Synthesis

Maximillian Chen, Alexandros Papangelis, Chenyang Tao, Seokhwan Kim, **Andy Rosenbaum**, Yang Liu, Dilek Hakkani-Tür

Presented at [EACL 2023](https://2023.eacl.org/) (The 17th Conference of the European Chapter
of the Association for Computational Linguistics) \| Dubrovnik, Croatia \| May 2-6, 2023

[ACL Anthology](https://aclanthology.org/2023.findings-eacl.63/) \| [Amazon Science](https://www.amazon.science/publications/places-prompting-language-models-for-social-conversation-synthesis) \| [arXiv](https://arxiv.org/abs/2302.03269)

### Weakly Supervised Data Augmentation Through Prompting for Dialogue Understanding

Maximillian Chen, Alexandros Papangelis, Chenyang Tao, **Andy Rosenbaum**, Seokhwan Kim, Yang Liu, Zhou Yu, Dilek Hakkani-Tur

Presented at [SyntheticData4ML @ NeurIPS 2022](https://www.syntheticdata4ml.vanderschaar-lab.com/) \| New Orleans, LA, USA \| December 2, 2022

[Amazon Science](https://www.amazon.science/publications/weakly-supervised-data-augmentation-through-prompting-for-dialogue-understanding) \| [arXiv](https://arxiv.org/abs/2210.14169)

### CLASP: Few-Shot Cross-Lingual Data Augmentation for Semantic Parsing

**Andy Rosenbaum**, Saleh Soltan, Wael Hamza, Amir Saffari, Marco Damonte, Isabel Groves

Presented at [AACL-IJCNLP 2022](https://www.aacl2022.org/) (The 2nd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 12th International Joint Conference on Natural Language Processing) \| Online \| November 20-23, 2022

[ACL Anthology](https://aclanthology.org/2022.aacl-short.56/) \| [Amazon Science](https://www.amazon.science/publications/clasp-few-shot-cross-lingual-data-augmentation-for-semantic-parsing) \| [arXiv](https://arxiv.org/abs/2210.07074)

### LINGUIST: Language Model Instruction Tuning to Generate Annotated Utterances for Intent Classification and Slot Tagging

**Andy Rosenbaum**, Saleh Soltan, Wael Hamza, Yannick Versley, Markus Boese

Presented at [COLING 2022](https://coling2022.org) (The 29th International Conference on Computational Linguistics) \| Gyeongju, Republic of Korea \| October 12-17, 2022.

[ACL Anthology](https://aclanthology.org/2022.coling-1.18/) \| [Amazon Science](https://www.amazon.science/publications/linguist-language-model-instruction-tuning-to-generate-annotated-utterances-for-intent-classification-and-slot-tagging) \| [arXiv](https://arxiv.org/abs/2209.09900)

### AlexaTM 20B: Few-Shot Learning Using a Large-Scale Multilingual Seq2Seq Model

Saleh Soltan, Shankar Ananthakrishnan, Jack FitzGerald, Rahul Gupta, Wael Hamza, Haidar Khan, Charith Peris, Stephen Rawls, **Andy Rosenbaum**, Anna Rumshisky, Chandana Satya Prakash, Mukund Sridhar, Fabian Triefenbach, Apurv Verma, Gokhan Tur, Prem Natarajan

August 2022

[Amazon Science Paper](https://www.amazon.science/publications/alexatm-20b-few-shot-learning-using-a-large-scale-multilingual-seq2seq-model) \| [Amazon Science Blog Post](https://www.amazon.science/blog/20b-parameter-alexa-model-sets-new-marks-in-few-shot-learning) \| [Amazon Science Code](https://www.amazon.science/code-and-datasets/alexa-teacher-model-alexatm-20b) \| [arXiv](https://arxiv.org/abs/2208.01448)

### Alexa Teacher Model: Pretraining and Distilling Multi-Billion-Parameter Encoders for Natural Language Understanding Systems

Jack FitzGerald, Shankar Ananthakrishnan, Konstantine Arkoudas, Davide Bernardi, Abhishek Bhagia, Claudio Delli Bovi, Jin Cao, Rakesh Chada, Amit Chauhan, Luoxin Chen, Anurag Dwarakanath, Satyam Dwivedi, Turan Gojayev, Karthik Gopalakrishnan, Thomas Gueudre, Dilek Hakkani-Tur, Wael Hamza, Jonathan Hueser, Kevin Martin Jose, Haidar Khan, Beiye Liu, Jianhua Lu, Alessandro Manzotti, Pradeep Natarajan, Karolina Owczarzak, Gokmen Oz, Enrico Palumbo, Charith Peris, Chandana Satya Prakash, Stephen Rawls, **Andy Rosenbaum**, Anjali Shenoy, Saleh Soltan, Mukund Harakere Sridhar, Liz Tan, Fabian Triefenbach, Pan Wei, Haiyang Yu, Shuai Zheng, Gokhan Tur, Prem Natarajan

Presented at [KDD 2022](https://kdd.org/kdd2022/) (The 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining) \| Washington, DC, USA \| August 14-18, 2022

[Amazon Science](https://www.amazon.science/publications/alexa-teacher-model-pretraining-and-distilling-multi-billion-parameter-encoders-for-natural-language-understanding-systems) \| [arXiv](https://arxiv.org/abs/2206.07808)

## Patents

### Active Learning for Lexical Annotation

Alok Ulhas Parlikar, **Andrew Jake Rosenbaum**, Jeffrey Paul Lilly, Jeffrey Penrod Adams 

Abstract: Features are disclosed for active learning to identify the words which are likely to improve the guessing and automatic speech recognition (ASR) after manual annotation. When a speech recognition system needs pronunciations for words, a lexicon is typically used. For unknown words, pronunciation-guessing (G2P) may be included to provide pronunciations in an unattended (e.g., automatic) fashion. However, having manually (e.g., by a human) annotated pronunciations provides better ASR than having automatic pronunciations that may, in some instances, be wrong. The included active learning features help to direct these limited annotation resources.

2014

[Google Patents](https://patents.google.com/patent/US9508341B1/en) \| Patent Number: US 9,508,341 B1

## Education

* M.A. in Computational Linguistics \| Brandeis University \| 2014
* B.S. in Mathematics and Minor in Linguistics \| University of Florida \| 2011

## Licenses and Certifications

* Deep Learning Specialization \| Coursera \| 2018
	* Neural Networks and Deep Learning
	* Structuring Machine Learning Projects
	* Convolutional Neural Networks
	* Sequence Models
	* Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization
* Machine Learning \| Coursera \| 2017
* Trinity College London Certificate in Teaching English to Speakers of Other Languages (TESOL) \| Active Language Institute \| Cádiz, Spain \| 2011

## Languages

* English: Native
* Spanish: Full Working Proficiency
* Esperanto: Full Working Proficiency
* French: Limited Working Proficiency
* Mandarin Chinese: Elementary Proficiency
* Hebrew: Elementary Proficiency

## Sites

* [Google Scholar](https://scholar.google.com/citations?user=r3HxDqAAAAAJ&hl=en)
* [Semantic Scholar](https://www.semanticscholar.org/author/Andrew-Rosenbaum/146177177)
* [Twitter](https://twitter.com/andyjrosenbaum) (@andyjrosenbaum)
* [LinkedIn](https://www.linkedin.com/in/andyjrosenbaum) (@andyjrosenbaum)
