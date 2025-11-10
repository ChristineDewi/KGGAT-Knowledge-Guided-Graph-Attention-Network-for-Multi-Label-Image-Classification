### KGGAT:Knowledge-Guided Graph Attention Network for Multi-Label Image Classification

Christine Dewi, Dhananjay R Thiruvady, Nayyar Zaidi 

### Abstract

Multi-label image classification requires understanding not only the visual features of individual objects but also their semantic relationships within a scene. To address this challenge, we propose KGGAT—a Knowledge-Guided Graph Attention Network that integrates external knowledge graphs with attention-based visual reasoning. Unlike conventional transformer-based models that rely solely on visual correlations, KGGAT incorporates structured semantic priors from ConceptNet-55 and OpenAI-derived knowledge graphs to explicitly model inter-label dependencies. A dual-path architecture couples a Graph Attention Network (GAT) for label reasoning with a transformer-based visual encoder, enabling cross-modal alignment between visual and semantic spaces. In addition, an element-wise addition fusion strategy and an Asymmetric Loss (ASL) objective enhance feature interaction and effectively mitigate class imbalance. Extensive experiments on MS-COCO and Pascal VOC 2007 demonstrate that KGGAT achieves state-of-the-art performance, attaining 89.21% mAP and 96.85% mAP, respectively. Qualitative analyses further show that KGGAT provides accurate object localization and interpretable label reasoning across diverse scenes, validating its effectiveness in knowledge-guided multi-label image classification. Code and pretrained models will be released to facilitate future research on knowledge-guided visual understanding.


<img width="500" height="507" alt="image" src="https://github.com/user-attachments/assets/3410fcf9-8b98-437a-88f8-6a5d72ae4c00" />

<img width="518" height="511" alt="image" src="https://github.com/user-attachments/assets/536ff8b5-09d6-4161-82ce-6967aa0ebf65" />


### Clone the project from :

https://github.com/SlongLiu/query2labels

"Query2Label: A Simple Transformer Way to Multi-Label Classification". 

### Knowledge Graph

<img width="1298" height="398" alt="graph2" src="https://github.com/user-attachments/assets/548e522a-bab9-4413-b3c4-7cac4b38f955" />
<img width="1007" height="452" alt="RealDataUnion Fusion" src="https://github.com/user-attachments/assets/b48cfa55-5446-4157-bdaa-a1897958dd9b" />

Comparison of semantic relation graphs derived from
different knowledge sources. CN55 (ConceptNet-55) encodes
commonsense relations, OA (OpenAI LLM-based) provides con-
textual links, and their fusion OA-FU (OpenAI-Fused Union)
yields a denser, more balanced semantic graph. 

### Result on MS COCO

<img width="1097" height="422" alt="image" src="https://github.com/user-attachments/assets/6d437211-0c1c-4be8-85a5-ada60ab6300e" />

### Result on VOC 2007 Dataset

<img width="1108" height="390" alt="image" src="https://github.com/user-attachments/assets/0536d01d-9580-4e97-af34-0acf2d8e4c75" />

### Ablation Study

<img width="1180" height="600" alt="image" src="https://github.com/user-attachments/assets/4f42ca4f-ae2a-4c28-9f55-2cffad4d3ec2" />

<img width="1178" height="408" alt="image" src="https://github.com/user-attachments/assets/ace1e95b-cd46-496f-ad56-ecdb5bae627d" />

### Visualization and Interpretability

<img width="570" height="698" alt="image" src="https://github.com/user-attachments/assets/786c0353-7957-49e5-b3a4-167d7c8fa34d" />




