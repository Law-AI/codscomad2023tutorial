# Resources for Law-AI
This repository contains links to different Law-AI resources such as datasets and tools.

# Task-specific Resources
This section contains resources for different automation tasks in the legal domain

## Legal Named Entity Recognition

This task aims to identify different entities in legal documents. Entities may be classified into different groups that have different legal meanings, such as the parties (appellants, respondents), lawyers, judges and so on.

+ <a href="https://github.com/elenanereiss/Legal-Entity-Recognition"> A Dataset of German Legal Documents for Named Entity Recognition </a> (<a href="https://aclanthology.org/2020.lrec-1.551.pdf">Lietner et al., 2020</a>)
+ <a href="https://github.com/Legal-NLP-EkStep/legal_NER"> Named Entity Recognition in Indian court judgments </a> (<a href="https://arxiv.org/pdf/2211.03442.pdf">Kalamkar et al., 2022</a>)

## Legal Judgment Prediction

Broadly speaking, this task aims to determine the outcomes of court cases. In many settings, this may be composed of several sub-tasks, which are addressed in the forthcoming sections.

+ <a href="https://github.com/koc-lab/law-turk"> Natural language processing in law: Prediction of outcomes in the higher courts of Turkey </a> (<a href="https://www.sciencedirect.com/science/article/pii/S0306457321001692?via%3Dihub">Mumcuoglu et al., 2021</a>)
+ <a href="https://pub.cl.uzh.ch/wiki/public/pacoco/swiss_legislation_corpus"> Building corpora for the philological study of Swiss legal texts </a> (<a href="https://www.zora.uzh.ch/id/eprint/54761/">Hofler et al., 2011</a>)
+ <a href="https://github.com/Exploration-Lab/CJPE"> ILDC for CJPE: Indian Legal Documents Corpus for Court Judgment Prediction and Explanation </a> (<a href="https://aclanthology.org/2021.acl-long.313.pdf">Malik et al., 2021</a>)
+ <a href="https://github.com/masha-medvedeva/ECtHR_crystal_ball"> Judicial Decisions of the European Court of Human Rights: Looking into the Crystal Ball </a> (<a href="http://martijnwieling.nl/files/Medvedeva-submitted.pdf">Medvedeva et al., 2018</a>)
+ <a href="https://github.com/thunlp/CAIL"> CAIL2018: A Large-Scale Legal Dataset for Judgment Prediction </a> (<a href="https://arxiv.org/pdf/1807.02478.pdf">Xiao et al., 2018</a>)

## Identifying Legal Articles and Charges

Often considered a sub-task of Legal Judgment Prediction, this task aims to identify the relevant legal articles and charges given the facts of a case.

+ <a href="https://github.com/Law-AI/LeSICiN"> LeSICiN: A Heterogeneous Graph-based Approach for Automatic Legal Statute Identification from Indian Legal Documents </a> (<a href="https://ojs.aaai.org/index.php/AAAI/article/view/21363">Paul et al., 2022</a>)
+ <a href="https://github.com/IntelligentLaw/HMN"> Hierarchical Matching Network for Crime Classification </a> (<a href="https://dl.acm.org/doi/pdf/10.1145/3331184.3331223">Wang et al., 2019</a>)
+ <a href="https://github.com/Law-AI/automatic-charge-identification"> Automatic Charge Identification from Facts: A Few Sentence-Level Charge Annotations is All You Need </a> (<a href="https://aclanthology.org/2020.coling-main.88.pdf">Paul et al., 2020</a>)
+ <a href="https://github.com/nlp208/legal_attention"> Charge Prediction with Legal Attention </a> (<a href="https://link.springer.com/chapter/10.1007/978-3-030-32233-5_35">Bao et al., 2019</a>)

## Semantic Segmentation / Rhetorical Role Labeling

Court case documents are composed of several functional parts such as Facts, Arguments, Ruling, etc. which may not be clearly demarcated. This task aims to automate the process of segmenting a court case document into these parts.

+ <a href="https://github.com/Law-AI/semantic-segmentation"> Identification of Rhetorical Roles of Sentences in Indian Legal Judgments </a> (<a href="https://arxiv.org/pdf/1911.05405.pdf">Bhattacharya et al., 2019</a>)
+ <a href="https://datasets.doctrine.fr/"> The French Court Decision Structure dataset — FCD12K </a>
