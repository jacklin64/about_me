## About Me
Hi, I'm a Ph.D. student supervised by [Jimmy Lin](https://cs.uwaterloo.ca/~jimmylin/) in the [David R. Cheriton School of Computer Science](https://cs.uwaterloo.ca/) at the University of Waterloo starting from 2020. My research focuses on dense retrieval for text search, including how to integrate lexical and semantic features into dense representations, its application to broader scenario, such as conversationa, multilingual and multimodal search.  

I previously interned as a research scientist in Meta, Vectara and Nvidia and had a chance to lead the project to build state-of-the-art English text, [DRAGON](https://huggingface.co/facebook/dragon-plus-context-encoder), multilingual text, [mAggretriever](https://aclanthology.org/2023.emnlp-main.715/), and universal multimodal dense retrieval model, [MM-Embed](https://huggingface.co/nvidia/MM-Embed). In addition, I have led a project, [FLAME](https://arxiv.org/pdf/2405.01525)), to improve large language models' factuality. 

## Publications
MM-Embed: Universal Multimodal Retrieval with Multimodal LLMs.
<ins>Sheng-Chieh Lin</ins>, Chankyu Lee, Mohammad Shoeybi, Jimmy Lin, Bryan Catanzaro, and Wei Ping.
[[model](https://huggingface.co/nvidia/MM-Embed)][[arxiv](https://arxiv.org/abs/2411.02571)]

FLAME: Factuality-Aware Alignment for Large Language Models.  
<ins>Sheng-Chieh Lin</ins>\*, Luyu Gao, Barlas Oguz, Wenhan Xiong, Jimmy Lin, Wen-tau Yih, Xilun Chen\*.  
NeurIPS (just accepted), Dec 2024. [[arxiv](https://arxiv.org/pdf/2405.01525)]

[Unifying Multimodal Retrieval via Document Screenshot Embedding.](https://aclanthology.org/2024.emnlp-main.373/)  
Xueguang Ma, <ins>Sheng-Chieh Lin</ins>, Minghan Li, Wenhu Chen, Jimmy Lin.  
EMNLP, Nov 2024. [[arxiv](https://arxiv.org/abs/2406.11251)]

[mAggretriever: A Simple yet Effective Approach to Zero-Shot Multilingual Dense Retrieval](https://aclanthology.org/2023.emnlp-main.715/).  
<ins>Sheng-Chieh Lin</ins>, Amin Ahmad, and Jimmy Lin.  
EMNLP, Nov 2023. [[code](https://github.com/castorini/dhr)]

[How to Train Your DRAGON: Diverse Augmentation Towards Generalizable Dense Retrieval](https://aclanthology.org/2023.findings-emnlp.423/).  
<ins>Sheng-Chieh Lin</ins>\*, Akari Asai, Minghan Li, Barlas Oguz, Jimmy Lin, Yashar Mehdad, Wen-tau Yih, and Xilun Chen\*.    
EMNLP Findings, Nov 2023. [[code](https://github.com/facebookresearch/dpr-scale/tree/main/dragon)][[model](https://huggingface.co/facebook/dragon-plus-context-encoder)][[arxiv](https://arxiv.org/abs/2302.07452)]  

[One Blade for One Purpose: Advancing Math Information Retrieval using Hybrid Search](https://dl.acm.org/doi/10.1145/3539618.3591746).  
Wei Zhong, <ins>Sheng-Chieh Lin</ins>, Jheng-Hong Yang, and Jimmy Lin.    
SIGIR, Jul 2023.

[SLIM: Sparsified Late Interaction for Multi-Vector Retrieval with Inverted Indexes](https://dl.acm.org/doi/abs/10.1145/3539618.3591977).  
Minghan Li, <ins>Sheng-Chieh Lin</ins>, Xueguang Ma, and Jimmy Lin.    
SIGIR, Jul 2023.

[Improving Conversational Passage Re-ranking with View Ensemble](https://dl.acm.org/doi/abs/10.1145/3539618.3592002).  
Jia-Huei Ju, <ins>Sheng-Chieh Lin</ins>, Ming-Feng Tsai, Chuan-Ju Wang.  
SIGIR, Jul 2023. [[arxiv](https://arxiv.org/abs/2304.13290)]  

[CITADEL: Conditional Token Interaction via Dynamic Lexical Routing for Efficient and Effective Multi-Vector Retrieval](https://aclanthology.org/2023.acl-long.663/).  
Minghan Li, <ins>Sheng-Chieh Lin</ins>, Barlas Oguz, Asish Ghoshal, Jimmy Lin, Yashar Mehdad, Wen-tau Yih, Xilun Chen.    
ACL, Jul 2023. [[code](https://github.com/facebookresearch/dpr-scale/tree/citadel)][[arxiv](https://arxiv.org/abs/2211.10411)]  

[Aggretriever: A Simple Approach to Aggregate Textual Representation for Robust Dense Passage Retrieval](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00556/116046/Aggretriever-A-Simple-Approach-to-Aggregate).  
<ins>Sheng-Chieh Lin</ins>, Minghan Li, Jimmy Lin.  
Transactions of the Association for Computational Linguistics, May 2023. [[code](https://github.com/castorini/dhr)][[arxiv](https://arxiv.org/abs/2208.00511)]  

[A Dense Representation Framework for Lexical and Semantic Matching](https://dl.acm.org/doi/10.1145/3582426).  
<ins>Sheng-Chieh Lin</ins>, Jimmy Lin.  
ACM Transactions on Information Systems, Apr 2023. [[code](https://github.com/castorini/dhr)][[arxiv](https://arxiv.org/abs/2206.09912)]  

[Contextualized Query Embeddings for Conversational Search](https://aclanthology.org/2021.emnlp-main.77/).  
<ins>Sheng-Chieh Lin</ins>, Jheng-Hong Yang, Jimmy Lin.  
EMNLP, Nov 2021. [[code](https://github.com/castorini/CQE)][[Pyserini](https://github.com/castorini/chatty-goose/blob/master/docs/conversation_dense_retrieval_experiments.md)][[arxiv](https://arxiv.org/abs/2104.08707)]

[In-Batch Negatives for Knowledge Distillation with Tightly-Coupled Teachers for Dense Retrieval](https://aclanthology.org/2021.repl4nlp-1.17/).  
<ins>Sheng-Chieh Lin</ins>\*, Jheng-Hong Yang\*, Jimmy Lin.  
ACL workshop on Representation Learning for NLP (RepL4NLP), Aug 2021. [[code](https://github.com/castorini/tct_colbert)][[model](https://huggingface.co/castorini/tct_colbert-v2-hnp-msmarco)][[Pyserini](https://github.com/castorini/pyserini/blob/master/docs/experiments-tct_colbert-v2.md)][[arxiv](https://arxiv.org/abs/2010.11386)]   

[Multi-Stage Conversational Passage Retrieval: An Approach to Fusing Term Importance Estimation and Neural Query Rewriting](https://dl.acm.org/doi/10.1145/3446426).  
<ins>Sheng-Chieh Lin</ins>\*, Jheng-Hong Yang\*, Rodrigo Nogueira, Ming-Feng Tsai, Chuan-Ju Wang, and Jimmy Lin.  
ACM Transactions on Information Systems, Aug 2021. [[code](https://github.com/castorini/chatty-goose)][[arxiv](https://arxiv.org/abs/2005.02230)]

[Efficiently Teaching an Effective Dense Retriever with Balanced Topic Aware Sampling](https://dl.acm.org/doi/10.1145/3404835.3462891).  
Sebastian Hofstätter, <ins>Sheng-Chieh Lin</ins>, Jheng-Hong Yang, Jimmy Lin, and Allan Hanbury.  
SIGIR, July 2021. [[code](https://github.com/sebastian-hofstaetter/tas-balanced-dense-retrieval)][[model](https://huggingface.co/sebastian-hofstaetter/distilbert-dot-tas_b-b256-msmarco)] 

[Chatty Goose: A Python Framework for Conversational Search](https://dl.acm.org/doi/10.1145/3404835.3462782).  
Edwin Zhang, <ins>Sheng-Chieh Lin</ins>, Jheng-Hong Yang, Ronak Pradeep, Rodrigo Nogueira, and Jimmy Lin.  
SIGIR (Demonstrations), July 2021. [[code](https://github.com/castorini/chatty-goose)]  

[Pyserini: A Python Toolkit for Reproducible Information Retrieval Research with Sparse and Dense Representations](https://dl.acm.org/doi/10.1145/3404835.3463238).  
Jimmy Lin, Xueguang Ma, <ins>Sheng-Chieh Lin</ins>, Jheng-Hong Yang, Ronak Pradeep, and Rodrigo Nogueira.  
SIGIR (Resource), July 2021. [[code](https://github.com/castorini/pyserini)]

[Designing Templates for Eliciting Commonsense Knowledge from Pretrained Sequence-to-Sequence Models](https://aclanthology.org/2020.coling-main.307/).  
Jheng-Hong Yang\*, <ins>Sheng-Chieh Lin</ins>\*, Rodrigo Nogueira, Ming-Feng Tsai, Chuan-Ju Wang, and Jimmy Lin.  
COLING, December 2020. [[arxiv](https://arxiv.org/abs/2003.08380)] 

[Personalized TV Recommendation: Fusing User Behavior and Preferences](https://arxiv.org/abs/2009.08957).  
<ins>Sheng-Chieh Lin</ins>\*, Ting-Wei Lin\*, Jing-Kai Lou, Ming-Feng Tsai, Chuan-Ju Wang.  
arXiv:2104.08707, August 2020. 

[Negative-Aware Collaborative Filtering](http://ceur-ws.org/Vol-2431/paper9.pdf).  
<ins>Sheng-Chieh Lin</ins>, Yu-Neng Chuang, Sheng-Fang Yang, Ming-Feng Tsai and Chuan-Ju Wang.  
RecSys (Late-Breaking Results), September 2019.  
